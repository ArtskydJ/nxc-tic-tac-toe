nxc-tic-tac-toe
===============

The classic game of Tic-Tac-Toe, now on your NXT!

Compile with the NXC compiler.

I don't believe this requires the enchanced NBC/NXC firmware.

# Known Issues

- The AI moves randomly, unless it is able to win, or block a win

# To Do

- Change the coding style. I wrote it over 2 years ago and it looks ugly now. :)

# Build

## Prerequisites

- [BricxCC]()

## Compile to the NXT

You have a few options:

1. Open the TicTacToe.nxc file in BricxCC, and click Download
2. Run this from the command line: `"C:\Program Files (x86)\BricxCC\nbc.exe" -s=usb -d TicTacToe.nxc`
3. Run this from the command line: `"C:\Program Files (x86)\BricxCC\nbc.exe" -s=usb -d -sm- TicTacToe.nxc` (for quieter output)
4. Use Sublime Text 3's build system, along with [my tutorial](http://www.josephdykstra.com/compiling-nxc-using-sublime-build)

# License

[VOL](http://veryopenlicense.com)
