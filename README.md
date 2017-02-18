# Tank Island

Tank Island is an open source 2D top down shooter game that was created with Ruby using
[Gosu](http://www.libgosu.org) game development library while writing
[this book](https://leanpub.com/developing-games-with-ruby/).

## Are you a game developer?

I am building an online community portal for indie game developers. You can list your own projects in there, for free: [Game Hero](https://www.gamehero.org)

## Screenshots

![Tank Island Game](https://dl.dropboxusercontent.com/u/176100/tank_island/screen1.png)

![Tank Island Game](https://dl.dropboxusercontent.com/u/176100/tank_island/screen2.png)

[Gameplay video on YouTube](http://youtu.be/c2M_zJ9KcS8)

## Book: Developing Games With Ruby

Complete process of building this game is described step by step in this free to read book:

[Developing Games With Ruby](https://leanpub.com/developing-games-with-ruby/read)

## Installation

Before installing, make sure you have:

- Ruby installed, preferably through [rbenv](https://github.com/sstephenson/rbenv), not rvm.
- ImageMagick (`gem install rmagick` should work).
- Gosu prerequisites for [Mac](https://github.com/jlnr/gosu/wiki/Getting-Started-on-OS-X),
    [Linux](https://github.com/jlnr/gosu/wiki/Getting-Started-on-Linux) or
    [Windows](https://github.com/jlnr/gosu/wiki/Getting-Started-on-Windows)

To install it, run

    $ gem install tank_island

## Starting the game

There are several ways to start the game.

### Running in 800x600 window mode

    $ tank_island

### Running with custom resolution

    $ w=1600 h=1200 tank_island

### Running full screen with custom resolution

    $ fs=1 w=1200 h=800 tank_island

## Controls

### Gameplay

- `W` `A` `S` `D` moves your tank.
- Mouse `left click` shoots.
- `ESC` goes into menu and away from it.

### Debugging

- `R` respawns your tank.
- `T` spawns an enemy tank under mouse cursor.
- `F1` enters debug mode.
- `F2` toggles profiling
