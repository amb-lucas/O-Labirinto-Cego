# O Labirinto Cego
Game for the Software Infrastructure discipline at UFPE

The discipline required the development of quick game in the Assembly x86 Language.

This game has a total of 8 levels and it's based on memorising a path shown to you.
Before each level, you have a chance to memorize the maze, taking as much time as you'd like.
Once you're ready, you must press a button for the maze to fade to black and walk to the goal along the path previously shown to you.

The implementation consists of reading the buttons pressed by the user and checking with the expected one.
If the button pressed is correct, then the move is processed.
Otherwise, you're taken back to the start of the level.

This game was graded 100% and it has been presented as one of the samples in the presentation of the project.

## Instructions

First, you need to install _QEMU_ and _NASM_ on your computer.

(Links to be added soon.)

Afterwards, open the terminal on the game folder and run the following command:

```
make all
```

Then your emulator will show up with a loading screen and the game will follow right after.

(It doesn't really load anything, they just made us put the text there)
