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
- The breakpoint pauses the application at the line/method you want to inspect and launches the debugger so you can run each line in turn to see what is causing the bug.

2. Does the line of code on a breakpoint run when you start debugging?
- No, it stops the application before the line of code is run.

3. How do we debug the next line of code?
- To run the next line of code you use the 'step over' command. This will run the breakpoiont line then stop at the next line of code.

4. What does the step into command do?
- The 'step into' command will 'step into' a function and stop at the first method associated with that function. You can then step over the method, line by line to debug.

5. What is the difference between evaluate expression and evaluate code fragment?
- 'Evaluate expression' will evaluate individual expressions/methods, 'evaluate code fragment' lets you evaluate several lines of code found within a function and create temporary variables to assign values to. This way you can test if functions are working correctly outside of the main code.
