# back-and-forth
Marked Programming Assignment 3 of the "C# Class Development" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description

Starting in Unity

All your work for this assignment is in the Mover.cs file; don't change ANY of the code in the other files I've provided to you.

For this assignment, you'll be adding functionality to the Start and Update methods in the provided Mover class stub to implement the required functionality. 

What is the required functionality? When the game starts, the game object the Mover script is attached to starts moving to the right. After (approximately) 1 second, the game object starts moving to the left instead. After another (approximately) 1 second, the game object starts moving to the right again instead. The game object keeps changing direction every second until the game is stopped.

The Unity materials I provided to you contains a stub for the Mover class, but you still have lots of work to do to finish implementing that class (script). 

In the Mover script I provided, add code to the Start method to add a Timer component, set its duration to the TimerDuration constant I provided, and run the timer. Add code to the Update method to check if the timer has finished; if it has, multiply the directionMultiplier field by -1 and run the timer again. After the code you just added, add code to move the game object using the directionMultiplier field, the MoveAmountPerSecond constant I provided, and Time.deltaTime. 

Note: The big idea behind the directionMultiplier field is that if it's set to 1 the game object will move to the right and if it's -1 the game object will move to the left. Given that idea, you should be able to figure out how to use the directionMultiplier field when you're moving the game object.

Run the game. The game object the Mover script is attached to should move back and forth on the screen, changing direction approximately every second.

## Getting Started

n/a

### Dependencies

+ Windows 10
+ .NET
+ Microsoft Visual Studio
+ Unity

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/back-and-forth)

### Executing program

1. Open the project's directory
2. Traverse: ProgrammingAssignment3 -> Build -> Windows -> x86
3. Run _ProgrammingAssignment3_ application

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

n/a
