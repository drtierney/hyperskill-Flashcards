# hyperskill-Flashcards
Developing an application which allows flashcards to be created and used for remembering definitions of terms.  
https://hyperskill.org/projects/44

<img src="https://github.com/drtierney/hyperskill-Flashcards/blob/master/Flashcards.gif" width="800" height="500" />

## Syntax

| Arg | Valuelist | Comment
| --- | --------- | ------- |
| -import | `<String>` | Not Required<br>Existing filepath<br>Auto import from file on start|
| -export | `<String>` | Not Required<br>(Non)-existing filepath<br>Auto export to file on exit |


```
Flashcards.jar
```

```
Flashcards.jar -import countries.txt
```

```
Flashcards.jar -export 090720.txt
```

```
Flashcards.jar -import words08july.txt -export words09july.txt
```

```
Flashcards.jar -export frenchvocab.txt -import frenchvocab.txt
```

## Stages

**Stage #1 Stage one, card one**  
Display information about a single card on the screen.

**Stage #2 What's on the card?**  
Compare the lines and work with conditions: display the card and the user’s answer on the screen.

**Stage #3 Make it your own**  
Practice arrays and loops: create a new card for the program to play with you.

**Stage #4 A good stack**  
Learn to use hashtables, display key values and work with exceptions in order to fix the problem of repeating cards.

**Stage #5 Menu, please!**  
Work with files: create a menu that allows to add, delete, save and upload saved cards in your game.

**Stage #6 Statistics**  
Using statistics, set a correct answer for each card and teach the game to determine which card was the hardest to solve.

**Stage 7 IMPORTant**  
Enable the user to import files right upon starting the game, working with command-line arguments. 
