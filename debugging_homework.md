# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
A breakpoint is used to pause the code and activate the debugger, allowing for the values of data to be checked at different points in the program.


2. Does the line of code on a breakpoint run when you start debugging?
Putting a breakpoint on a line pauses the program *before* that line is run.


3. How do we debug the next line of code?
To run the next line, we use the 'step over' command. It will pause on the next line too.


4. What does the step into command do?
The 'step into' command allows us to move into another file or piece of code (for example a method which has been called) while a breakpoint has paused the program. This allows us to debug a method which is being called from elsewhere.


5. What is the difference between evaluate expression and evaluate code fragment?
Evaluate Expression is used to apply Java code to objects which have already been created by the program. However, it can only be used to apply one line of code at a time. Evaluate Code Fragments allows us to apply multiple lines of code at once and also create temporary variables for debugging purposes.
 