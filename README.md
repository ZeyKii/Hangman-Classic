# 📜 SUMMARY
1. [Introduction](#golang-hangman-classic)
2. [Requirement](#requirement)
3. [How to start the game](#how-to-start-the-game)
4. [How to use a backup](#how-to-use-a-backup)
5. [Optional feature](#optional-feature)

<br>

# 🎮 Introduction
* Name : Hangman
* Contributors: Ferran Maxance, Mace Léo, Raffanel Guilhem, Bourdoncle Alan

The Hangman project aims to create a game in the *Golang* computer language that runs in a command terminal.

<br>

# 💻 Requirement 
* Golang 
* AZERTY or QWERTY Keyboard 

THE REPO ALREADY HAVE WORDS [ASSETS](./assets/) BUT YOU CAN CREATE YOU OWN ASSETS.

<br>

# 🚀 How to start the game 
1. Clone this repo `git clone [url]`
2. Go to the repo you just cloned using your terminal : `cd .\hangman-classic\`
3. To launch the game you need to execute main.go file and specify the assets (file .txt with the different words used to play) `go run main.go assets/words.txt` (for example)
4. To use optional options you can use different [flags](#optional-feature) `go run main.go [word] [flags]`

<br>

# 💾 How to use a backup
Do you want to take a break during your game ?
No worries, use the backup system.

1. Write *STOP* :
    ```
    Enter letter or word : STOP
    ```
2. **Want to start your save ?** Use this : ` --startWith save.txt` :
    ```
    -- Your save is start --
    ```
3. If a backup is present, decide whether to overwrite it or not :
    ```
    WARNING : Save was found !
    Create a new save delete the oldone.
    Continue ? [y/n]
    ```
4. When starting a game, you will be offered an option to use the save or not :
    ```
    We found a save.
    Want you to launch them ? [y/n]
    ```

<br>

# 💾 Optional feature

## A harder game ?
Using different commands you can more or less manage the difficulty of your game.

**The game is too easy for you ?** Use this flag : ` --hard`
This option modify the rules of the game : 
* Less letter reveal
* Letters already used are not displayed
* Possibility to test 3 vowels, if limit exceeded you lose a attempt (-1)

<br>

## You don't have good eyesight ?

You can use the ASCII ART version, launch the game with that  `--letterFile assets/standard.txt` (other ASCII otion are avaible : assets/shadow.txt ; assets/thinkertoy.txt )

![ASCII_SCREENSHOT](./screenshots/ASCII%20OPTION.png)

<br>

## It's still not enough for you ?

You can use the PISTE NOIRE version in order to have a nice interface, launch the game like this: (without any argument)

```
PS C:\Users\maxfe> cd .\hangman-classic\
PS C:\Users\maxfe\hangman-classic> go run main.go
```

![PISTE_NOIRE_SCREENSHOT](./screenshots/PISTE%20NOIRE%20OPTION.png)

<br>

## Here you know everything. ENJOY ! 🎉
