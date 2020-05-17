+++
title = "Projects"
date = "2014-04-09"
+++

### [znes - Zac's Nintendo Entertainment System](https://github.com/ZacJoffe/znes)
I loved working on Chip8, and was ready to write another emulator. With the release of [One Lone Coder's excellent NES series](https://www.youtube.com/watch?v=nViZg02IMQo&list=PLrOv9FMX8xJHqMvSGB_9G9nZZ_4IgteYf), I knew this was going to be my next big project. The scope of this considerably larger than Chip8, and any other of my previous projects, but after months of development, I can finally say that it's mostly done. It runs over 1000 games seamlessly, more than I would ever have time to play through. I was even surprised to find out that games from the Japanese equivalent of the NES, the Famicon, work perfectly! Demos can be seen on the project's [readme](https://github.com/ZacJoffe/znes/blob/master/README.md).

Like with Chip8, I used Rust and the [SDL2 bindings](https://github.com/Rust-SDL2/rust-sdl2) to build the emulation engine. What impressed me the most about researching this project was the fantastic community of NES reverse engineers who have documented everything you could ever need. The [Nesdev Wiki](https://wiki.nesdev.com/w/index.php/Nesdev_Wiki), in particular, is an indisposable resource for anything NES related. I learnt a lot about hardware, lower-level programming and computers in general during development, and I can't wait to keep improving znes once the school term is over.

### [Chip8 Emulator](https://github.com/ZacJoffe/chip8-emulator)
Emulators have always fascinated me. While I've been recently working hard implementing more complex systems, I started off with emulating the [Chip8](https://en.wikipedia.org/wiki/CHIP-8) interpreted programming language. The project was a great experience and I love writing Rust!

### [Tetris](https://github.com/ZacJoffe/sdl-tetris)
I've always wanted to write a Tetris clone. Last year I started writing it in Lua with the LÖVE framework (which I experimented with back in high school) but got bogged down by school and job searching to really get into it. So when I realized I had the time, I jumped on the opportunity. I took this project as a way to further familiarize myself with C++ and learn about SDL2 and game development. 

It was a lot of work, but I'm thrilled with the results and cannot wait to do something like this again in the future! My goal was to make an accurate clone of the original game. I developed several data structures to handle things like the tetromino queue, screen objects, and piece holding. It was an enjoyable project; I learnt a lot about C++, 2D graphics, game development and SDL2. 

### [Screenshot App](https://github.com/ZacJoffe/screenshot)
This is mainly a command line app written in Golang to automate taking and sharing screenshots for my Linux system. Inspired by ShareX, an app I used to love back when I used Windows, this app takes screenshots of a screen region and copies it to the clipboard. With a flag, you can instead upload the screenshot to Imgur. To do this, I wrote a library to consume Imgur's REST API, as well as reverse-engineering the request to use quad.pe, a lightweight alternative to Imgur. 

I also wrote libraries to use Gfycat for uploading gifs. To get the clipboard working, I wrote wrapper libraries for both xclip and xsel. And, lastly, the app was written using Cobra, the same framework used to write the CLI for Docker and Kubernetes. I've bound keys to run the command via my hotkey manager (which can be found in my dotfiles repository, link to that below), so I don't even need a terminal to use it! It was designed specifically for that task and does everything I need it to do. 

### [Dotfiles](https://github.com/ZacJoffe/dotfiles)
Over the last 2 years or so, I've put a lot of effort into writing configuration files for various *nix programs. I've focused on creating simplistic configurations that suite needs and optimize my workflow, and continue improving and adding to what's already there.

### [Rubik's Cube Solving Robot](https://github.com/ZacJoffe/two-by-two-solver)
For our final project in my first semester, we had to build a Lego Mindstorm EV3 robot to do something interesting. Two other people and I made a robot that solves a 2x2 Rubik's cube. We used an algorithm that determines a near-optimal solution of a given scramble (10 turns or less) and programmed the robot to execute the moves to solve the cube. 
