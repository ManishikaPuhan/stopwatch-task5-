# stopwatch-task5-
Purpose
The Stopwatch Application is a console-based Java program that mimics the functionality of a traditional stopwatch. It allows users to measure the elapsed time between the activation and deactivation of the stopwatch. This application serves as a practical exercise for learning basic Java programming concepts, including user input handling, time management, and object-oriented programming.

Features
Start Functionality:

Users can start the stopwatch, which begins tracking the elapsed time from the moment of activation.
Stop Functionality:

The stopwatch can be paused, and it calculates the total elapsed time up to that point. This allows users to see how much time has passed since activation.
Reset Functionality:

Users can reset the stopwatch to zero, clearing any recorded time and preparing it for a new session.
User Commands:

The application supports simple text-based commands:
start: Activates the stopwatch.
stop: Pauses the stopwatch and displays the elapsed time.
reset: Resets the stopwatch to zero.
exit: Closes the application.
Elapsed Time Display:

The application continuously displays the current elapsed time, formatted as HH:MM:SS, while the stopwatch is running.
Code Overview
Class Structure:

The application is structured around a Stopwatch class that encapsulates all the functionality required to manage the stopwatch.
The main method serves as the entry point, handling user commands and interactions.
Methods:

start(): Begins timing and stores the current system time.
stop(): Stops timing and calculates the elapsed time.
reset(): Resets the elapsed time to zero.
getElapsedTime(): Returns the formatted elapsed time as a string.
User Interaction:

The application uses a Scanner object to capture user input and responds to commands in real-time, providing feedback on the current state of the stopwatch.
Example Usage
The user runs the application.
They enter the command start to activate the stopwatch.
After a period of time, the user enters stop to pause the stopwatch and view the elapsed time (e.g., 00:01:30).
The user can then choose to enter reset to clear the time or exit to close the application.
