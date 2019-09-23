# O Labirinto Cego
Game for the Software Infrastructure discipline at UFPE

The discipline required the development of quick game in the Assembly x86 Language.

This game has a total of 8 levels and it's based on memorising a path shown to you.
Before each level, you have a chance to memorize the maze, taking as much time as you'd like.
Once you're ready, you must press a button and the maze will fade to black.
You must walk towards the goal along the path shown to you.

The implementation consists of reading the buttons pressed by the user and comparing with the expected one.
If the button pressed is correct, then the move is processed.
Otherwise, you're taken back to the start of the level.

This game was graded 100% and it has been presented as one of the samples in the presentation of the project.

## Requirements

- _QEMU_
- _NASM_

## Instructions to run the game

Run the following command with the terminal on the game folder:

```
make all
```

Your emulator will show up with a loading screen and the game will follow right after.

(It doesn't really load anything, we just put the text there cause we were told to)
