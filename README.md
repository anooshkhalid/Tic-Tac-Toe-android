# Tic Tac Toe Android Game 

### Itroduction

Tic Tac Toe is an Android Game and also the first app that I developed in the topic of Android Developments. The motivation behind this app is my desire to learn Android Developments, which is one of the most interesting topics in Computer Science nowadays.

### Screenshots

<img src="https://github.com/mtuan93/Tic-Tac-Toe-android/blob/master/app.png" width="200">
<img src="https://github.com/mtuan93/Tic-Tac-Toe-android/blob/master/main.png" width="200">
<img src="https://github.com/mtuan93/Tic-Tac-Toe-android/blob/master/oneplayer.png" width="200">
<img src="https://github.com/mtuan93/Tic-Tac-Toe-android/blob/master/twoplayer.png" width="200">

### How the app works

* `MainMenuScreen`: associates with `main_menu.xml`, which is a menu screen that allows user to choose the type of game. It can either be one-player mode, two-player mode, or exit mode. Each mode is a `Button` that associates with an `onClick` event listener to either switch to `MainActivity` or exit the application.

* `TicTacToeGame` : represents for the entire game, including a 3x3 board - represented by an array of `char`, player one and player two, with a Random object to simulate the computer move if the game is in one-player mode. The class is responsible for each move in the game and a check if there is a winner.

* `MainActivity`: associates with activity_main, will hook up TicTacToeGame with the layout and implements all the listeners handlers. The game timeline will be implemented here.

### Demo:
There are two easy ways to check this application out:
* Since the app is developed in Android Studio, you can clone this app repository and import it into your Android Studio. Then either run it with an emulator or on an actual device (what I do). More information on how to do this is availabe [here](https://developer.android.com/tools/building/building-studio.html).
* You can download the `apk` file [here](https://github.com/mtuan93/Tic-Tac-Toe-android/raw/master/app-debug.apk) and install it into your android device. Since this is an unregistered debug version, make sure that you enable `Unknown sources` in `Security` section of the phone.