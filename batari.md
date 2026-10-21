# batari Basic

This list currently focuses on libraries, tutorials, books and other resources for building games for the Atari 2600 in BASIC.  The official documentation, hosted on Random Terrain, is also broken out by topic.

* [batari Basic by Fred Quimby](https://github.com/batari-Basic/batari-Basic) ![GitHub stars](https://img.shields.io/github/stars/batari-Basic/batari-Basic?cacheSeconds=604800) ![GitHub last commit](https://img.shields.io/github/last-commit/batari-Basic/batari-Basic?cacheSeconds=86000): batari Basic (bB) is a BASIC-like language for creating Atari 2600 games. It is a compiled language that runs on a computer, and it creates a binary file that can be run on an Atari 2600 emulator or the binary file may be used to make a cartridge that will operate on a real Atari 2600.

* [batari Basic Commands by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html): batari Basic official documentation hosted on Random Terrain.

* [batari Basic Forum on AtariAge](https://forums.atariage.com/forum/65-batari-basic/): Want an easier way to get your feet wet in Atari 2600 programming? Check out Batari's batari Basic, which lets you create Atari 2600 programs with an easy to understand BASIC syntax. Dive in for more info!

## Learning
* [Getting Started](#getting-started)
    * [VCS Game Maker](#vcs-game-maker)
    * [Core Development Tools](#core-development-tools)
* [Game Design](#game-design)
* [Advanced Concepts](#advanced-concepts)
    * [Display Kernels](#display-kernels)
    * [Compiler Directives](#compiler-directives)
    * [Bankswitching](#bankswitching)
    * [Assembly](#assembly)

## Reference
* [Basic Language Concepts](#basic-language-concepts)
* [Advanced Language Concepts](#advanced-language-concepts)
* [Input](#input)
   * [Collision](#collision)
   * [Movement](#movement)
* [Graphics](#graphics)
* [Playfield](#playfield)
   * [Title Screen](#title-screen)
   * [Score](#score)
* [Players](#players)
* [Missiles](#missiles)
* [Ball](#ball)
* [Sound](#sound)
* [Text](#text)
* [Gameplay](#gameplay)
* [Open Source Games](#open-source-games)
* [Forks](#forks)

# Learning

- [ ] Understand player, missile, ball and playfield limitations
- [ ] Understand kernels and bankswitching to bust limitations

## Getting Started

* [Making a game for the Atari 2600 by Peter Cullen](https://www.youtube.com/playlist?list=PLFH1CEHEtgenlyEO0SwpqivIHUSgUeeIH) 📽️: I'm trying to make a game for the Atari 2600 using bAtari basic. Join me as I learn bits and pieces about bAtari and bit by bit design a game concept and try to bring it to life.

* [batari Basic kickstart by Kirk Isreal](https://alienbill.com/2600/bbkickstart/) 📄: This is meant to be a rough document about getting you to make your first Atari 2600 program using a language called "batari Basic". It is not a full language guide, but rather a kickstart focused on getting your system setup to write and then play Atari 2600 games and have some general idea of what's going on.

* [Batari BASIC Programming Starting & Finished Work... by Uno Caraway](https://www.youtube.com/watch?v=MZ1_ZxPJ9sA) 📽️: In this video I teach the first steps in creating an Atari 2600 game using Visual batari BASIC and scroll through and demonstrate some current works-in-progress and a finished game (Yeet Fighter).  [Part 2](https://www.youtube.com/watch?v=sggxsF-hwuo)

* [Programming Tutorial by Curtis P](https://forums.atariage.com/topic/111938-programming-tutorial/) 📄: Many programming tutorials begin with a Hello World program. This will no exception. Since the 2600 doesn't have a character display, we will need to draw the words hello world on the playfield.

* [Troubleshooting by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#troubleshooting) 📚: Explains some common programming errors and their resolutions.

### VCS Game Maker

* [VCS Game Maker by Haroldo de Oliveira Pinheiro](https://github.com/haroldo-ok/vcs-game-maker/wiki) 🔨: This online tool is a no-code environment designed to allow someone to create a game for Atari 2600 without knowing much about programming and without installing anything on their computer. It uses Blockly to allow the user to implement the logic using blocks and then, behind the scenes, generates a Batari Basic source code, that is then be compiled using batari-basic-js in order to generate an Atari 2600 ROM, which is emulated using Javatari.

* [Block coding for the Atari 2600 by Mike and James Classic Games](https://www.youtube.com/watch?v=v_GOjaD6XUE) 📽️: Walkthrough of the wonderful new VCS Game Maker tool. You can now code Atari 2600 games without coding!  This is part 1 of a 5 part series. [Part 2 - If, Then](https://www.youtube.com/watch?v=Yb2wJcCEjWM), [Part 3 - Backgrounds and Variables](https://www.youtube.com/watch?v=F-uJSwnTHWY), [Part 4 - Colors and Switches](https://www.youtube.com/watch?v=TSaCaGS2lgk), [Part 5 - Visibility and Colors](https://www.youtube.com/watch?v=ruXkkc48wnc)

* [VCS Game Maker - The ATARI Game Engine! by Gamesfromscratch](https://www.youtube.com/watch?v=UvvcEtIfEro) 📽️: Want to create Atari 2600 games?  Of course you do!   An with the VCS game maker game engine, it's stupidly easy to do.  It's got everything you need to create Atari games, using a very simple Scratch-like visual programming language.  You can even create actual hardware compatible ROMS!   Best of all, it's free and open source too!

* [VCS Game Maker tutorial part 1 by Haroldo Pinheiro](https://www.youtube.com/watch?v=4HgKZArUGW0) 📽️: This is my first try on making a tutorial for VCS Game Maker. VCS Game Maker is an online no-code tool designed to allow someone to create a game for Atari 2600 without knowing much about programming and without installing anything on their computer. It uses Blockly to allow the user to implement the logic using blocks and then, behind the scenes, generate a Batari Basic source code, that is then be compiled using batari-basic-js in order to generate an Atari 2600 ROM, which is emulated using Javatari.

### Core Development Tools

* [Visual bB by Jeff Wierer](https://forums.atariage.com/topic/123849-visual-bb-10-a-new-ide-for-batari-basic/) 🔨: Here is a project that I have been working on for some time and it's finally in a shareable state. VisualbB is an integrated development environment for writing Atari 2600 programs in batariBasic. For anybody that is familiar with Microsoft Visual Studio, it has a similar look and feel.

## Game Design

* [Game Standards and Procedures by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-standards-and-procedures.html) 📚: The following documents the user interface desired for 2600 games. This is meant both to provide a guide to development program and as a check list for finished carts.

* [Parts of a Program by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#parts_of_a_program) 📚: I'm just an amateur BASIC programmer, so experts may not agree with everything below, but it still might be helpful to new users who don't have the parts of a game set in their minds. To me, every section of a BASIC program is like a little box or module. Remember, not every game will follow this exact pattern. It's just an outline that can give you guidance if you feel like a plastic bag blowing in the wind.

## Advanced Concepts

### Display Kernels

* [Display Kernel](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#displaykernel) 📚: The display kernel is a carefully-written software routine that renders the television display.

* [Standard Kernel Options by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#kerneloptions) 📚: The standard kernel has options for customizing it including reading paddle input, player colors, turning off blank lines on the playfield, playfield colors, playfield heights and multi-colored playfields.

* [DPC+ Kernel](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpcplus) 📚: The DPC+ kernel has an asymmetric (non-mirrored) multicolored playfield with simultaneous single line background and foreground colors. It also has 10 multicolored single-height sprites instead of 6 mono-colored double-height sprites. Before the DPC+ kernel was added, all bB sprites had double-thick rows, so they weren't as pretty as the sprites that assembly language programmers could make. Thanks to the DPC+ kernel, bB users can create single-height sprites that are as detailed as the ones made by Imagic and Activision.

* [Multisprite Kernel](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#multikernel) 📚: This is an entirely new kernel written from scratch that provides significant features that should be suitable for a wide variety of games. The multisprite kernel was created years before the DPC+ kernel. Many people choose to use the DPC+ kernel instead since it has 10 multicolored single-height sprites instead of 6 mono-colored double-height sprites.

* [Minikernels/HUDs](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#huds) 📚: Minikernels are intended for use as a HUD (Heads-up Display), which is the part of the game that shows lives, health, status, time, etc.  Two minikernels are included, one contains a 'life counter' that can show up to six icons to represent player lives, and the lives have a variety of display configurations. The other minikernel contains a fixed, left-aligned life counter and a 28-unit 'status bar' (for lack of a better term, as the bar could be used to indicate health, time, power, speed, etc.)

* [PXE kernel by Zachary Scolaro](https://forums.atariage.com/topic/385318-pxe-kernel-templates-tutorials-and-documentation/) 🔨: PXE give developers the ability to push classic Atari hardware beyond its original limitations through cartridge-level innovation. Supports 17 sprites, 8-way scrolling, drawing parts of the playfield, create a unique starfield, high score tables that can be saved.  Requires a custom cartridge that does not currently work on 2600+.

Note: More purpose-built mini kernels can be found in other sections.

### Compiler Directives

* [Compiler Directives by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#set) 📚: The set command tells the compiler or the assembler to build your code a certain way.
   - smartbranching: Tells the compiler to generate optimal assembly code when it encounters an if-then statement with a line number or label after the then.
   - tv: Specifies the tv format. Valid options are ntsc or pal. ntsc is the default and is unnecessary.
   - romsize: Allows you to specify the size of the generated binary. 4k is the default. Currently you may generate 2k, 4k, 8k, 16k, 32k, or 64k binaries.
   - optimization: Tells the compiler to try to generate code that runs faster or has a smaller size.
   - kernel: Determines which kernel to use with your game. Currently there are 29 kernels available.
   - kernel_options: These are options for customizing the kernel for various needs. Generally, adding options will mean that some objects will not be displayed. Currently the options only apply to the standard kernel.
   - debug: Used to help find bugs in your bB program. Currently it only helps with determining when too many machine cycles are used in a particular frame.
   - legacy: Version 1.0 of bB has several new features and has been optimized such that code written for earlier versions may not work quite right. To retain more compatibility with old code, a legacy mode has been implemented that will (hopefully) allow the games to work properly without extensive modifications.

### Bankswitching

* [Bankswitching (Up to 64K of ROM for your games!) by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#bankswitching) 📚: The Atari 2600 can only address 4K at a time. Games larger than 4K are possible by additional hardware on the cartridge that can swap in two or more banks of 4K.

* [Superchip RAM by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#superchipram) 📚: The Superchip, also called the SARA chip, provides 128 additional bytes of RAM. Superchip RAM is only used in conjunction with bankswitching.

* [Bankswitching Demo Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program shows how to use bankswitching.  It runs a playfield animation with each playfield change being stored in a different bank.

### Assembly

* [Assembly Language by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#assembly) 📚: batari Basic can work with code written in assembly language.  This is a way you can break out of the batari limitations.
   - Use the asm statement to insert inline assembly language into your program.
   - Include modules in the final binary that are not normally available.
   - Inline asm files.

# Reference

## Basic Language Concepts

* [Basic Questions by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#basic_questions) 📚: The most basic terms and definitions.  (CPU, RAM, ROM, etc)

* [Things You Should Know by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#thingsknow) 📚: Indenting, line numbers, memory, timing, white space, multiple statements on one line, line length and other limitations, DOS compatibility.

* [Miscellaneous by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#miscellaneous) 📚: Comments, reboot, end.

* [Glossary if Terms](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#glossary) 📚: This non-alphabetical glossary is a work in progress. More will be added to it over time.

* [Variables by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#variables) 📚: You have 26 general purpose variables in batari Basic, fixed as a-z. Although they are fixed, you can use the dim command to map an alias to any of these variables.  Includes advice on overcoming variable limitations, temporary variables, constants, bit operations, and fixed point variables.

* [Numbers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#numbers) 📚: Decimals, hexedecimals, binary, and negative values.

* [Math by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#math) 📚: Full expression evaluation for integerAny number without a decimal (positive, negative or zero). A whole number. math is supported by batari Basic. (addition, subtraction, multiplication, division, functions, macros)

* [Labels, Line Numbers and Jumping Around by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#labels) 📚: Alphanumeric labelsCan be made up of letters, numbers, and underscores. are supported by batari Basic. You may use line numbers if you prefer. Some old-school programmers like line numbers, or at least use them as a matter of comfort since they were necessary in early Basics. In any case, labels and line numbers are optional. Typically you will only need them when you want to specify a goto or gosub target.

* [Decision Making by Fred Quimby (Brains of a Game)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#decisionmaking) 📚: Perhaps the most important statement is the if-then statement. These can divert the flow of your program based on a condition.

* [Loops by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#loops) 📚: A common form of a loop is a for…next loop, but a loop in general is any program that repeats. In this sense, all batari Basic programs must be loops, in that the programs never exit.

* [Random Numbers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#randomnumbers) 📚: Randomness will help make your games replayable and more fun. Players will get a fresh experience every time they play your games and they'll really be playing instead of memorizing an exact way to 'beat' your game that is set in stone.

* [drawscreen by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#drawscreen) 📚: The drawscreen command displays the screen. Any objects with changed colors, positions or height will be updated. Internally, this command runs the display kernel.

* [Keywords, Constants, and Registers by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#keywords_const_registers) 📚: A quick list of keywords, special constants, and registers.

* [Quick Reference by Kirk Isreal](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#quick_reference) 📚: A list of keywords by topic: General Core, General Display Loop, General TIA, Advanced Core, Advanced Display Loop / Kernel, DPC+ Display Loop / Kernel, Life Counter/Status Bar Loop/Kernel, General Variables.

## Advanced Language Concepts

* [Data Statements and Arrays (read-only) by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dataarrays) 📚: For convenience, you may specify a list of values that will essentially create a read-only array in ROM. You create these lists of values as data tables using the data statement.

* [256k, 128k, 64k, 32k, Multikernel Frameworks by Mike Saarna](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_multikernel_frameworks) 📚: Build a game out of individual 4k projects that can have their own separate kernels and kernel options.

* [Memory Maps by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#memorymaps) 📚: This section has a Standard Kernel Memory Map, a Multisprite Kernel Memory Map, and a DPC+ Kernel Memory Map.

## Input

* [Joysticks by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#joysticks) 📚: Joysticks are read by using an if-then statement. There are four directional functions and one fire function for each joystick.

* [Console Switches by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#switches) 📚: Reading the console switches (reset, select, Color/BW, Difficulty) is done by using an if-then statement.

* [Atari 7800 by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#atari7800) 📚: The Atari 7800 is reverse-compatible with nearly 100% of Atari 2600 games. All bB games should run on the 7800. However, games that use the COLOR/BW switch may have problems. On the 7800, the switch is meant to be used as a PAUSE switch. On the 2600 this is a toggle or rocker switch, but on the 7800 it is a momentary pushbutton.

* [Read Atari Keyboard Controllers by Curtis P](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_keyboard_controllers) 📚: CurtisP cleaned up SeaGtGruff's code, added left or right keypad selection, and packaged it into a couple of include files. The ZIP file contains the include files, two sample programs, and minimal documentation.

* ["Paddle" Minikernel by Mike Saarna](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#paddle_minikernel) 📚: Draws the paddle graphic without using existing bB objects. It's called a “paddle” minikernel, but there's no reason it couldn't be used for a space ship or whatever, so long as the game object is constrained to the bottom of the screen.

* [Playfield Draw by 8bitworkshop](https://8bitworkshop.com/v3.12.1/?platform=vcs&file=bb%2Fdraw.bas) 🕹️: Uses the joystick and button to draw pictures on the playfield.
  
### Collision

* [Collision Detection by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#collision) 📚: Used for checking if two objects have collided on the screen.

* [Collision Detection (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_collision_detection) 📚: DPC+ collision is pixel perfect, but doesn't take hardware-reflected sprites into account and it doesn't support NUSIZ copies or wide players.

* [Detect Collisions Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to move a sprite and detect a collision.

* [Move Sprite with Playfield Boundaries Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to move a sprite within playfield boundaries.

### Movement

* [Speed Change by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ex_8_8_speed_change) 🕹️: There are two sprites and the ball on screen moving from side to side. Move the joystick up, down, left or right to change the speed of the current object (up/down is faster, left/right is slower).

* [Fixed Point Sprite Movement by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ex_fixed_point_sprite) 🕹️: Use the joystick to move the sprite. Press the fire button while moving the joystick to go faster.

* [Maze With Animated Sprite and Roaming Sprite Using 8.8 Fixed Point Movement by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#maze_32x23) 🕹️: Use the joystick to move the Pac-Man style sprite. An enemy sprite semi-randomly moves around the maze. It knows where you are and will casually go after you, but it can't hurt you.  (3 versions of this sample program are available)

## Graphics

* [Colors by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#labels) 📚: The Atari 2600 can display up to 128 unique colors—that is, 16 unique hues and 8 luminosity levels for each hue for NTSC consoles. PAL consoles can display 104 unique colors (13 hues with 8 luminosity levels.). Sample code is available for pulsating colors, hues and cursor.

* [Flash Colors Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to change color in a loop.

* [Cosmic Ark starfield by Mike Saarna](https://github.com/batari-Basic/batari-Basic/blob/master/samples/bbstarfield.bas) 🕹️: Demo of the Cosmic Ark starfield direction in bB.

* [PXE Demo by Mike Saarna](https://github.com/batari-Basic/batari-Basic/blob/master/samples/pxe_full_playfield.bas) 🕹️: Demonstrates drawing a PXE 40x176 colored playfield.

* [LumaBoost by Jonas Carlsson](https://forums.atariage.com/topic/286939-lumaboost-in-bb-example/) 🕹️: A a flicker management system that uses a brighter version of a sprite to offset flickering.

## Playfield

* [The Playfield by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#playfield) 📚: In the standard kernel, by default, you get a 32 x 11 bitmapped, asymmetric playfield (32 x 12 if you count the hidden row that is only seen if scrolled).

* [TIA Registers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#tia)  📚: Change the properties of the playfield.

* [The Playfield (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_playfield) 📚: You can specify an entire playfield at once by using the playfield: command. Horizontal resolution is 32 playfield pixels across (same as the standard kernel). Vertical resolution with the DPC+ kernel is a little more complicated. The playfield is divided into 4 columns and each column can have a different resolution (pixel height).

* [pfscroll (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_pfscroll) 📚: RevEng added coarse vertical scrolling to the DPC+ kernel back when he was working on batari Basic for a while. There is no horizontal DPC+ scrolling at this time.

* [Playfield Colors (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_playfield_colors) 📚: Specifies colors of each playfield row and must be followed by end.

* [Background Colors (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_background_colors) 📚: Lets you pick a color for each scanline in the background and must be followed by end.

* [Add Playfield Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program simply draws a yellow sprite on a black background and adds a simple playfield to the background.

* [Animate a Playfield Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to animate a playfield.

* [8 x 8 World (64 Rooms) by Karl G](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ex_8x8_world) 🕹️: This example program uses rand and unrand to generate an 8 x 8 world of 64 screens without having to use variables to track what type of screen is in what position. A second version is available that generates a 16 x 16 world with 512 rooms).

* [Atari Background Builder by Kirk Isreal](https://alienbill.com/2600/atari-background-builder/) 🔨: This is a graphical editor for large images that can output code ready to run on an Atari 2600. Want a 48 pixel splash screen minikernel for your batari Basic or assembly game? We got that. Want the properly flipped bits for your assembly Playfield? (Assymmetric, Mirrored, or Repeated?) We got that. Want to import an existing image file as a background graphic? We got that!

### Title Screen

* [Titlescreen Kernel by Mike Saarna](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#titlescreen_kernel) 📚: The Titlescreen Kernel is a custom assembly module that allows you to display a high quality title screen in your batari Basic game, without having to write any assembly code yourself.

* [Simple Titlescreen Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This sample program adds a simple titlescreen to Add Playfield Sample Code.

### Score

* [Score by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#score) 📚: The score keyword is used to change the score. The score is fixed at 6 digits, and it currently resides permanently at the bottom of the screen. Unlike other variables, batari Basic accepts values from 0-999999 when dealing with the score.  Also includes examples for lives and health bar.

* [Score Colors (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_scorecolors) 📚: With the DPC+ kernel, the color of each horizontal row of the score is specified using scorecolors:. This allows for interesting visual effects, like gradients.

* [Playerscores Minikernel by Curtis P](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#playerscores_minikernel) 📚: The playerscores minikernel provides two or four independently colored two-digit scores. The primary use is to display a separate score for each player, while allowing the main six-digit score to be used for something else.

* [Alternative Score Kernels by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_alternative_score_kernels) 📚: Most requested is two 3-digit scores. It's not perfect, as the two scores are on the extreme left and right of the screen, and I don't think there is any other way to pull this off.

* [4scores Minikernel by Karl Garrison](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_4scores)  📚: This minikernel can display 4 separate single-digit player scores in 4 different colors, all on the same line.

* [Racing Timer by Michael Rideout](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_racing_timer) 📚: An example that displays an edited timer—minutes in the 1st position, a colon in the 2nd position, seconds in the 3rd and 4th positions, a decimal point in the 5th position, and tenths of a second in the 6th position.

* [Extra Graphics & Split Score for DPC+ by Omegamatrix](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_dpc_split_score) 📚: You can have an extra six digits worth of graphics for DPC+ at any time.

## Players

* [Player Graphics (Sprites) by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#playergraphics) 📚: The standard kernel can display two player sprites, which are 8 pixels wide and any height (up to 256).

* [TIA Registers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#tia)  📚: Change the size and/or properties of players.

* [Player Graphics (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_sprites) 📚: DPC+ sprites are 8 pixels wide and can be any height (up to 256). Instead of having only two player sprites, you get ten with the DPC+ kernel.

* [Colorplayers by Mike Saarna](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#colorplayers) 📚: This standard kernel mod lets you use no_blank_lines and have two multicolored sprites instead of just one. The trade-offs are the loss of both missiles and the center bytes of the playfield are symmetric.

* [Draw Sprite Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program simply draws a yellow sprite on a black background.

* [Move a Sprite Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to move a sprite.

* [Animate a Sprite Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to animate a sprite.

* [3D Moving Sprite Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to move an animated sprite.  It combines Move a Sprite and Animate a Sprite.

* [Move an Animated Sprite Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to animate a sprite into a growing and shrinking 3D effect.

* [Multicolor Sprite for VCS Game Maker by Marc Vittorini](https://www.youtube.com/watch?v=XtVJPmXzte4) 📽️: Short video on how to easily make multicolored sprite with VCS Game Maker.


## Missiles

* [Missiles by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#missiles) 📚: Two missiles can be displayed on the screen at coordinates that you specify. The missiles are just solid rectangles. Only the width, height, and color can be changed. A missile can be as tall as the screen, but a missile can only be 1 pixel wide, 2 pixels wide, 4 pixels wide, or 8 pixels wide.

* [TIA Registers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#tia)  📚: Change the size and/or properties of missiles.

* [Missiles (DPC+)](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#dpc_missiles)  📚: A hardware limitation causes missile0 to display the colors of player0 and missile1 to display the colors of player1-player9 if they are on the same scanline.

* [Fire a Missile Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to make a sprite fire a missile.

* [Move Animate and Fire Sample Code by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: Demo for moving an animated sprite that can fire a missile in any direction.

## Ball

* [Ball by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ball) 📚: The ball is one of the objects that the Atari 2600 can display in the screen. The ball is the same color as the playfield. If a multicolored playfield is used, the ball will use the color of whatever row it is on.

* [TIA Registers by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#tia)  📚: Change the properties of the ball.

## Sound

* [Sound by Michael Rideout](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#sound) 📚: The Atari 2600's sound is generated by the TIA chip, which has two independent audio channels that work identically (channel 0 and channel 1). Each channel has three registers that determine the sound that will be produced (AUDV0, AUDC0, AUDF0, AUDV1, AUDC1, AUDF1).

* [batari Basic Sound Effects Library by Karl Garrison](https://www.randomterrain.com/rt-bb-sound-effects.html) 📚: At this time this page just has sound effects from RevEng's Sound Effects Collection, but I'll probably add some of my own over time or more from other contributors.

* [AtariVox Support for bB by Mike Saarna](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#atarivox) 📚: How to use the AtariVox Speech Synthesizer with batari Basic.

* [do re bB - the BASICs of batari music by Kirk Isreal](https://alienbill.com/2600/basic/music/) 📄: Music on the Atari 2600 is a little odd. To put it simply, the way an Atari makes sounds means it can't play the "normal" notes that make up Western music.  The good news is that batari BASIC makes it pretty easy to experiment with the sound capabilities of the 2600. It doesn't have built in sound commands, per se, but it's pretty easy to write the logic to set the 6 special TIA variables that control what's coming out of your TV speakers while your bB program is under way.

* [Atari SFX - sound effects usable in batari Basic by Jörg Rittershaus](https://forums.atariage.com/topic/370452-atari-sfx-sound-effects-usable-in-batari-basic/): 🕹️: 16 sound effects for your Atari 2600 games usable in batari Basic!

* [Sequencer Kit by Paul Slocum](https://www.qotile.net/sequencer.html) 🔨: Sequencer Kit is a music driver and music contruction kit for the Atari 2600 game console. Traditionally Atari 2600 games did not have much music aside from a few out-of-tune riffs due to the system only having two voices, 5-bit pitch, and a minuscule 128 bytes of RAM. But I discovered some ways to produce good music using the existing sound chip while only using a tiny amount of RAM and CPU cycles, allowing the driver can easily be integrated into most homebrew games. I even integrated the music driver into some of Atari's original games.

## Text

* [Text Minikernel by Karl Garrison](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#akmme_text_minikernel) 📚: Displays letters, numbers, and special characters with no flicker. The closest thing we're going to get to PRINT with bB. Works with the Standard, Multisprite, and DPC+ kernels.

* [Create Texts with VCS Game Maker by Marc Vittorini](https://www.youtube.com/watch?v=4bGydKacOxo) 📽️: How to create vertical text for Atari 2600 games using a non-programming tool called VCS Game Maker.

* [Hello World by Steven Hugg](https://8bitworkshop.com/v3.12.1/?platform=vcs&file=bb%2Fhelloworld.bas) 🕹️: Draws 'Hello World' on the playfield.

## Gameplay

* [Adventure Light Game by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 👾: This program demonstrates how to move an animated sprite. It combines previous sample programs I've written, and adds an invisible playfield along with the 'light' sprite that surrounds the player in the mazes in the original Atari adventure game.

* [Move Sprite with Enemy Sprite Following by Steve Engelhardt](https://forums.atariage.com/topic/109288-code-snippets-samples-for-bb-beginners/) 🕹️: This program demonstrates how to move a sprite and how to have a second ('enemy') sprite follow it.

* [Sprite Test by Steven Hugg](https://8bitworkshop.com/v3.12.1/?platform=vcs&file=bb%2Fsample.bas) 🕹️: This program demonstrates how to move a sprite and how to have a second ('enemy') sprite follow it.  Similar to Atarius Maximus sample.

* [Zombie Chase by Mike Saarna](https://github.com/batari-Basic/batari-Basic/blob/master/samples/zombie_chase.bas) 👾: A fun game that may help you learn batari Basic! Each level lasts about one minute you must score 1000 points to move on. COLOR/BW switch selects joystick or DC, left difficulty A=stop on collision; B=slow down on collision, right difficulty A=L/R border; B=no border.

* [2P Soccer Game by Steven Hugg](https://8bitworkshop.com/v3.12.1/?platform=vcs&file=bb%2FFIFA1977.bas) 👾:   1v1 soccer match between two players. Players can move about using the joystick directions, ball moves in front of the player currently in possession of it. Players cannot get too close to opponents goal. Players can shoot the ball using joystick fire button. Players can intercept the ball when it is kicked to gain possession. Players can also steal the ball from the other player. Reset game by pressing reset button.

* [Duck Chase by Steven Hugg](https://8bitworkshop.com/v3.12.1/?file=bb%2Fduck_chase.bas&platform=vcs) 👾: A small driving game where you must run over enough ducks in one minute to advance to the next level. 

## Open Source Games

_Organized by lines of code count._

* [Seaweed Assault by Duane Alan Hahn](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ex_seaweed_assault) 👾: A game developed by Random Terrain with lots of code comments that demonstrates bankswitching.  (800 lines)

* [Tinkernut World Deluxe by Fred Quimby](https://www.randomterrain.com/atari-2600-memories-batari-basic-commands.html#ex_tinkernut_world_deluxe) 👾: A cleaned up version of Tinkernut World, a simple game where you shoot a squirrel before he eats you.  This version more closely follows best practices.  Four versions of the program are available for download with slightly modified features.  (1,200 lines)

* [Dino Run by Petar Krstevski](https://github.com/krstevskipetar/Atari2600-DinoRun) 👾: This is a homebrew game for the Atari 2600 inspired by the classic Chrome Dinosaur Game, with some added gameplay tweaks. The core structure of this game is based on the "Tinkernut World Deluxe" example program. The game itself might not be very polished as it was made for fun as a learning exercise. (1,200 lines)

* [Princess Rescue by Chris Spry](https://forums.atariage.com/topic/215171-princess-rescue-batari-basic-source-code/) 👾: A “Super Mario style” game.  (3,000 lines)

* [1942 by Wolfgang Stubig](https://github.com/Al-Nafuur/1942-bB) 👾: In 1984 a great shoot 'em up was released for the Arcade by Capcom and that game was 1942. This is a port for the 2600 written in Batari Basic. (6,000 lines)

## Forks

* [Atarius Maximus](https://github.com/AtariusMaximus/batari-Basic) ![GitHub stars](https://img.shields.io/github/stars/AtariusMaximus/batari-Basic?cacheSeconds=604800) ![GitHub last commit](https://img.shields.io/github/last-commit/AtariusMaximus/batari-Basic?cacheSeconds=86000): Over the past week or so, I've been tinkering under the hood of batariBasic to see how hard it would be to bake some modern quality-of-life features and syntax shortcuts directly into the compiler.  That experiment turned into a complete custom fork.  To be clear, this is a personal experimental project right now with no plans to disrupt the official bB release stream.  I thought it would be nice to have true if...then...endif blocks and built in support for debouncing joystick movement and button presses, among other things.  I added some sample programs to the samples directory to demonstrate the new features.  More information is being tracked on an [AtariAge post](https://forums.atariage.com/topic/393347-bataribasic-amax-branch-new-features-commands-block-ifs-debouncing-switch-cases-more/).
