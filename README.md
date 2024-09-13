Dicee - A Simple Dice Rolling Game

Dicee is a simple, interactive dice-rolling app built using Flutter, the popular cross-platform UI 
toolkit. This app demonstrates basic concepts of state management, widget composition, and randomness 
in Flutter.

Features:

1. Two dices displayed on the screen.

2. Each dice can be rolled by tapping on it, generating a random number between 1 and 6.

3. The dice faces update dynamically every time the dice are rolled.

Technologies Used:

Flutter: The app is built using Flutter, which allows for fast and expressive development of natively compiled applications for mobile, web, and desktop from a single codebase.
Dart: Flutter's programming language is used for the app’s logic and structure.
Stateful Widgets: The dice state is managed with the StatefulWidget class, which allows for the dynamic updating of the dice faces when a button is pressed.
Random Number Generator: The dart:math library is used to generate random numbers between 1 and 6 to simulate dice rolls.
Asset Management: Images for the dice faces are stored and accessed from the app’s assets directory.

How the logic works:

1. The app displays two dice (using images) in a row.
2. When the user taps on either die, both dice roll and display a new random number, simulating the action of rolling dice.
3. The random numbers are generated using the Random() function from the dart:math library.
4. This app is perfect for demonstrating the basics of interactive UI in Flutter, and it can easily be extended with more features.

