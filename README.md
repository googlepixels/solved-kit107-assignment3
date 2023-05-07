Download Link: https://assignmentchef.com/product/solved-kit107-assignment3
<br>
The assignment is to construct a program that given some representation of a maze will find the path through to the end without you lifting a pencil or getting mud on your shoes!

An example of a maze is the following:

The challenge is to find a path from the square marked <strong>Start</strong> to the square marked <strong>Stop!</strong> by moving forwards, turning left, and turning right (with all directions relative to the current direction of travel) without going through “walls” which are indicated as black squares.

The application of this game to computing is the design of a program that allows a starting square to be given and then for the user to be graphically shown a solution derived by the computer.  The computer will select moves by creating a <em>game tree</em>.  A game tree consists of all the possible states of the game and in this assignment the computer determines any possible solution as the best one.  Each node of the game tree has children that indicate the states of the game that follow from the state of the parent for each possible move, i.e. each node in the tree possesses three branches which represent the maximum possible moves from the parent node.




This assignment uses many data structures (trees, linked-lists, stacks, and queues) to solve the puzzle.  The game will be text only.

A sample run of the game is shown below for depth-first:

And breadth-first:

<h2>Task</h2>

A <em>Visual </em>Studio project file is available for download from MyLO.  The project contains many header (.h) and source (.c) files.  All required files are present.




Your task is to complete the functions within the program files which have been declared but for which the function bodies are missing and to update the header comments for the source files that you change.

<h2>Program Style</h2>

Your program should follow the following coding conventions:

<ul>

 <li>const variable identifiers should be used as much as possible, should be written all in upper case and should be declared before all other variables;</li>

 <li>Variable identifiers should start with a lower case letter, be meaningful, and variables should only be declared at the top of a function;</li>

 <li>Every if and if-else statement should have a block of code (i.e. collections of lines surrounded by { and }) for both the if part and the else part (if used);</li>

 <li>Every loop should have a block of code;</li>

 <li>The keyword continue should not be used;</li>

 <li>The keyword break should only be used as part of a switch statement;  Opening and closing braces of a block should be aligned;</li>

 <li>All code within a block should be aligned and indented 1 tab stop (or 4 spaces) from the braces marking this block;  Commenting:

  <ul>

   <li>There should be a block of header comment which includes at least

    <ul>

     <li>file name</li>

     <li>student names</li>

     <li>student identity numbers</li>

     <li>a statement of the purpose of the program</li>

     <li>date o Each variable declaration should be commented</li>

    </ul></li>

   <li>There should be a comment identifying groups of statements that do various parts of the task</li>

   <li>Comments should describe the strategy of the code and should not simply translate the C into English</li>

  </ul></li>

</ul>

Style marks will be awarded proportionally, i.e. if you attempt only half the coding you can expect only half the style marks.