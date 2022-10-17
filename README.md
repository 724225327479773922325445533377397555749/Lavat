# lavat

Little program that simulates a lava lamp in the terminal.

## Usage

```
Usage: lavaterm [OPTIONS]
OPTIONS:
  -c COLOR          Set color. Available colours: red, blue, yellow, green, cyan and magenta.
                    Besides those colors the default one is the normal foreground of your terminal.
  -s SPEED          Set the speed, from 1 to 5. (default 1)
  -r RADIUS         Set the radius of the metaballs, from 1 to 10. (default: 5)
  -R RIM            Set a "rim" for each metaball, from 1 to 5. (default: none)
                    This option does not work with the default color
  -b NBALLS         Set the number of metaballs in the simulation, from 2 to 20. (default: 10)
  -h                Print help.

```
## Demo

`lavat -c red -R 1`
[1](https://github.com/AngelJumbo/lavat/blob/main/demo/1.gif?raw=true)


`lavat -c cyan -R 4 -b 20 -r 2`

[2](https://github.com/AngelJumbo/lavat/blob/main/demo/2.gif?raw=true)

## Credits

  - This program was made with [Termbox2](https://github.com/termbox/termbox2).
  - [Metaballs](https://en.wikipedia.org/wiki/Metaballs).
