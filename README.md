# Awesome Atari

A collection of awesome resources for Atari developers.
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1d/Atari_Logo.png" align="right">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
![last commit](https://img.shields.io/github/last-commit/scottkuhl/awesome-atari?cacheSeconds=86400)

Be sure to set a Watch on All Activity to be notified of new content.

Contributions are always welcome! Please take a look at the [contribution guidelines](CONTRIBUTING.md) pages first.

## Introduction

The Atari 2600 launched in 1977 and ended its official run in 1992. But now, 50 years later, it’s still going thanks to a dedicated homebrew community, a video game retro revolution and an official Atari company revival of new games and hardware.

The web is filled with scattered resources to help you build homebrew games for Atari consoles.
This repo's goal is to "organize the chaos" to make finding information easier whether you are trying to make your first game or your hundredth.

### What We Track

The site tracks:
- [batari Basic](batari.md) for creating Atari 2600 games in BASIC.
- [7800basic](7800basic.md) for creating Atari 7800 games in BASIC.
- [2600 Assembly](2600asm.md) for creating Atari 2600 games in Assembly language.
- [7800 Assembly](7800asm.md) for creating Atari 7800 games in Assembly language.

Currently most of the content is for batari Basic.

### Iconography
- 📚: Official documentation
- 📄: Article
- 📔: Book
- 📽️: Video
- 🔨: Tool or application
- 🕹️: Sample code
- 👾: Source code for full game
- 💵: Paid resource
- 🤖: Artificial Intelligence

## Table of Contents

* [Learning](#learning)
* [All systems and languages](#all-systems-and-languages)
  * [Core Development Tools](#core-development-tools)
  * [More Development Tools](#more-development-tools)
  * [Notable Works](#notable-works)
  * [Game Design](#game-design)
  * [Publishing](#publishing)
  * [Hardware](#hardware)
* [2600](#2600)
  * [Graphics](#2600-graphics)
  * [Sound](#2600-sound)
  * [Hardware](#2600-hardware)
* [7800](#7800)
  * [Graphics](#7800-graphics)
  * [Sounds](#7800-sound)
  * [Text](#7800-text)
* [Language Specific Pages](#language-specific-pages)
  * [batari Basic](batari.md)
    * [Learning](batari.md#learning)
      * [Getting Started](batari.md#getting-started)
        * [VCS Game Maker](batari.md#vcs-game-maker)
        * [Core Development Tools](batari.md#core-development-tools)
      * [Game Design](batari.md#game-design)
      * [Advanced Concepts](batari.md#advanced-concepts)
        * [Display Kernels](batari.md#display-kernels)
        * [Compiler Directives](batari.md#compiler-directives)
        * [Bankswitching](batari.md#bankswitching)
        * [Assembly](batari.md#assembly)
    * [Reference](batari.md#reference)
      * [Basic Language Concepts](batari.md#basic-language-concepts)
      * [Advanced Language Concepts](batari.md#advanced-language-concepts)
      * [Input](batari.md#input)
        * [Collision](batari.md#collision)
        * [Movement](batari.md#movement)
      * [Graphics](batari.md#graphics)
      * [Playfield](batari.md#playfield)
        * [Title Screen](batari.md#title-screen)
        * [Score](batari.md#score)
      * [Players](batari.md#players)
      * [Missiles](batari.md#missiles)
      * [Ball](batari.md#ball)
      * [Sound](batari.md#sound)
      * [Text](batari.md#text)
      * [Gameplay](batari.md#gameplay)
      * [Open Source Games](batari.md#open-source-games)
      * [Forks](batari.md#forks)
  * [7800basic](7800basic.md)
    * [Learning](7800basic.md#learning)
      * [Getting Started](7800basic.md#getting-started)
    * [Reference](7800basic.md#reference)
      * [Playfields](7800basic.md#playfields)
      * [Text](7800basic.md#text)
  * [2600 Assembly](2600asm.md)
    * [Learning](2600asm.md#learning)
      * [Getting Started](2600asm.md#getting-started)
      * [Books](2600asm.md#books)
      * [Courses](2600asm.md#courses)
      * [Videos](2600asm.md#videos)
  * [7800 Assembly](7800asm.md)
    * [Getting Started](7800asm.md#getting-started)
      * [Videos](7800asm.md#videos)
    * [Reference](7800asm.md#reference)

## Learning

- [ ] Create an account on [AtariAge](https://atariage.com)
- [ ] Review at least one tutorial or book in the Getting Started section for each language to get a lay of the land
- [ ] Pick a language
- [ ] Choose and setup an Integrated Development Environment
- [ ] Build your first, very simple, for learning only game.

## All systems and languages

### Core Development Tools

* [Atari Dev Studio by Matt Smith](https://forums.atariage.com/topic/290365-atari-dev-studio-for-homebrew-development-release/) 🔨: Welcome to Atari Dev Studio for designing homebrew games for the Atari 8-bit systems (Atari 2600 and 7800). Atari Dev Studio is a one-stop-shop for any programmer and includes a number of built-in features to allow you to design, develop and test games for your favourite system. Get started with batari Basic (2600) or 7800basic (7800) using easy to learn BASIC-like languages or go hard-core with assembly using dasm. During development test your creation using the Stella (2600) or A7800 (7800) emulators right from within Atari Dev Studio.

* [8bitworkshop by Steven Hugg](https://8bitworkshop.com) 🔨: It’s a integrated development environment (IDE) for old computers and video games. You can write code for 6502 or Z80-based hardware in C, assembler, etc. We emulate the hardware in the browser via JavaScript. The programming tools also run in your browser, and are usually compiled from C to WebAssembly or asm.js via Emscripten. We also support Verilog HDL for hardware design.

### More Development Tools

* [Ditherton Image Converter by Steven Hugg](https://8bitworkshop.com/dithertron/#sys=c64.multi&image=seurat.jpg) 🔨: A web-based image conversion utility designed to take modern, high-resolution digital images (like JPGs and PNGs) and crunch them down to fit the Atari 2600 among other platforms.

* [Furnace Tracker](https://tildearrow.org/furnace/) 🔨: An open-source chiptune tracker that supports accurate emulation for over 50 different retro sound chips—from the Game Boy and Sega Genesis to obscure arcade boards and the Atari 2600's TIA chip.

### Notable Works

* [Racing the Beam: The Atari Video Computer System by Ian Bogost and Nick Montfort](https://direct.mit.edu/books/monograph/3178/Racing-the-BeamThe-Atari-Video-Computer-System) 📔💵: The Atari Video Computer System dominated the home video game market so completely that “Atari” became the generic term for a video game console. The Atari VCS was affordable and offered the flexibility of changeable cartridges. Nearly a thousand of these were created, the most significant of which established new techniques, mechanics, and even entire genres. This book offers a detailed and accessible study of this influential video game console from both computational and cultural perspectives.

* [Once Upon Atari by Howard Scott Warshaw](https://newonceuponatari.hswarshaw.com) 📔💵: Video games set the world on fire, and Atari lit the match. This is an intimate view into the dramatic rise and fall of the early video game industry, as seen through the eyes of one of its most iconic pioneers. This book offers eye-opening details and insights, laying bare the issues and dynamics still taking place in modern software companies. A must read for anyone in high tech production, delivered in a compelling narrative, with a fresh voice and unorthodox style.

### Game Design

* [Game Design Theory - Chapter 10 - Atari Graphics & Arcade Game Design by Jeffrey Stanton with Dan Pinal](https://www.atariarchives.org/agagd/chapter10.php) 📔: There is no sure-fire way to predict whether a game will be successful, but there are certain attributes that contribute to success. Certainly a game should have a goal without one, what is the point in playing? Rules should be straightforward and logical. The game should also be a challenge; if it requires no skill, you will quickly tire of it. A game should evoke either fantasy or your innate curiosity; if it isn't novel or puzzling, it becomes boring. And lastly, arcade games, that by definition have a lot of action, should be easily controllable.

* [A Theory of Fun by Raph Koster](https://www.theoryoffun.com) 📔💵: An exploration of what fun is, and why games matter. Widely considered a classic. Used in dozens of university-level programs on game design all around the world. A go-to text for gamification, educators, trainers, and interaction designers.

* [The Art of Game Design: A Book of Lenses by Jesse Schell](https://schellgames.com/art-of-game-design) 📔💵: Create world-class games that will be played again and again. Written by Jesse Schell, one of the world’s top game designers, the book and audiobook get to the heart of game design, sharing the tools world-class designers rely on to craft unforgettable games in any genre.

* [2D Game Development: From zero to Hero by Daniele Penazzo](https://therealpenaz91.itch.io/2dgd-f0th) 📔: Another game development book? Yes, but today's game development scene is full of resources that teach you how to use a tool, and I found a severe lack of guides that would help aspiring game developers avoid common mistakes. This book aims to fix both those issues: it won't teach you a specific tool and it will be chock-full of tips and tricks, explained thoroughly, that you can apply to your game. This book aims to be as in-depth as possible, so you can create your own game either from scratch or using one of the many engines available.

* [Video game genre on Wikipedia](https://en.wikipedia.org/wiki/Video_game_genre) 📄: A video game genre is an informal classification of a video game based on how it is played rather than visual or narrative elements. This is independent of setting, unlike works of fiction that are expressed through other media, such as films or books. For example, a shooter game is still a shooter game, or a puzzle game is still a puzzle game, regardless of where or when it takes place. A specific game's genre is open to subjective interpretation. An individual game may belong to several genres at once.

### Publishing

* [Itch.io](https://itch.io) 🔨: A creator-focused platform for indie game developers to host, distribute, and sell their games for digital download.

* [Label Maker 2600](https://www.labelmaker2600.com) 🔨: Create classic labels for your game.

* [Restoring the 2600 Collection - One Box at a Time by Kevin Phillips](https://kevman3d.blogspot.com/2017/03/restoring-2600-collection-one-box-at.html) 📄: Learn how to make boxes for your game.

* Several publishers are available to distribute your games: [AtariAge](https://store.atariage.com), [Champ Games](https://champ.games/presents), [IdiotBox Games](https://idiotboxgames.bigcartel.com), [9bitRobot](https://9bitrobot.com), [Olioni Games](https://olionigamesoficial.wixsite.com/olioni-games-inc)

* Buy your own hardware supplies to make your games: [8-Bit Classics](https://www.8bitclassics.com), [Grand Idea Studio](https://grandideastudio.com/portfolio/gaming/pixels-past/).

* Market your game through influencers and reviews: [ZeroPage Homebrew](https://forums.atariage.com/profile/37205-zeropage-homebrew/), [The Immortal John Hancock](https://forums.atariage.com/profile/7241-swlovinist/), [GenXGrownUp](https://genxgrownup.com), [Retro Bliss Gaming](https://forums.atariage.com/profile/73571-retro-bliss/), [Mike's Gaming Gala](https://www.youtube.com/@mikesgaminggala)

### Hardware

* [AtariVox+ Speech Synthesizer](https://store.atariage.com/products/atarivox-speech-synthesizer) 🔨💵: The AtariVox+ is a self-contained speech/music synthesizer and memory card for the Atari 2600 and 7800, Vectrex, and other video game consoles with compatible controller ports.

## 2600

### 2600 Graphics

* [PlayerPal 2600 by Kirk Isreal](https://alienbill.com/2600/playerpalnext.html) 🔨: A javascript-based editor for atari 2600 graphics, use your mouse to paint on the main canvas.

* [Yaja 2600 Animator by Yaha Studio](https://yajastudio.com/tools) 🔨: Create player-sprite animations for Atari 2600 games with a browser-based editor built for Standard, Multisprite, DPC+, and PXE kernels. Draw, preview, align, and export animation data without wrestling with the hardware’s constraints.

* [Yaja 2600 Painter by Yaha Studio](https://yajastudio.com/tools) 🔨: Design playfield art and animations for the Atari 2600. Create striking visuals with tools that make the console’s limitations easier to work with.

### 2600 Sound

* [Atari 2600 Music And Sound Programming Guide by Paul Slocum](https://www.qotile.net/files/2600_music_guide.txt) 📄: It is difficult to do music on the Atari 2600 due to the limited pitch and two voices, but I've discovered some tricks to produce some pretty good music.  This document covers most of what I know. The intended audience is Atari 2600 programmers of any level and musicians who wish to write music for the 2600.  You don't need to know programming to write music for the 2600 (although it helps).  My website has a 2600 music kit you can download with a 2600 music driver and detailed instructions on how to write your own music data files for it along with some examples.  If you're new to 2600 programming, you'll probably want to take a look at my music kit before jumping into this guide.

* [Atari 2600 Sound SFX by Isaac](https://github.com/ElectronicFan/Atari_2600_Sound_SFX) 🔨: Create and edit Atari 2600 sound steps: frequency, control, volume, repeat. Drag-and-drop to reorder steps. Play individual steps or the entire sequence. Save and load JSON tables. Copy frequency and control/volume tables in .byte format.

* [Atari Riff Machine bt Kirk Israel](https://alienbill.com/2600/atari-riff-machine/) 🔨: The atari-riff-machine is a semi-serious, semi-fun tool to let Atari 2600 programmers generate simple looping music.

* [Atari Sound Editor by Dan Manning](https://github.com/dmanning23/atari-sound-editor) 🔨: Design sound effects and compose music visually, preview them in real time, and export ready-to-use 6502 assembly for your game.

* [Atari Sound Forger by Kirk Isreal](https://alienbill.com/2600/atari-sound-forger/) 🔨: This is meant as a fun real-time tool for exploring Atari 2600 Sounds and recording loops you can then play back on an Atari.

* [Slocum Tracker by Paul Slocum](https://www.igorski.nl/apps/slocum-tracker) 🔨: Slocum Tracker is a utility that enables people to write musical compositions for the Atari 2600 using a tracker-style interface, directly from their web browser.

* [webTune2600 by Kirk Isreal](https://alienbill.com/2600/basic/music/tune2600.html) 🔨: A web-based utility for Atari 2600 developers designed to help find the closest matching pitches on the Atari 2600's TIA sound hardware for standard musical notes.

* [Yaja 2600 Composer by Yaha Studio](https://yajastudio.com/tools) 🔨: Create music and sound effects for the Atari 2600 with our browser-based composer. Create melodies and sound effects with the TIA sound chip's unique tones, then export them for use in your games.

### 2600 Hardware

* [Making Your Own Atari Game Cartridge by Programmer Dan](https://www.youtube.com/watch?v=MrB4F9vA0vo) 📽️: In this video, I'll show how to make our own Atari 2600 Cartridge from start to finish ourselves.

* [Custom Atari 2600 Cartridge from AtariAge](https://store.atariage.com/products/custom-atari-2600-cartridge) 🔨💵: We can make a custom cartridge of an Atari 2600 binary you send to us, complete with custom, printed die-cut labels. You simply send us the binary you want programmed, along with the label artwork you'd like us to print, and we'll create your custom, labeled cartridge.

* [Atari 2600 Game Cartridge Shells from Hoskbrew](https://hoskinson-industries.myshopify.com/collections/atari-2600-game-cartridge-shells) 🔨💵: Cartridges shells for distributing your own games.

* [Melody Boards from AtariAge](https://store.atariage.com/pages/melody-board) 🔨💵: The Melody is a new circuit board developed by AtariAge that provides several advantages to the typical circuit boards used for new Atari 2600 homebrew games.

* [Atari 2600 Circuit Boards from Hoskbrew](https://hoskinson-industries.myshopify.com/collections/atari-2600-other/products/atari-2600-retro-circuit-rev-b) 🔨💵: PCBs for distributing your own games.

* [Harmony Cartridge by Fred Quimby](https://harmony.atariage.com/Site/Harmony.html) 🔨💵: The Harmony Cartridge is a flash-based device that allows you to load an entire library of games into a single cartridge.

## 7800

* [Eagle Tools](https://7800tools.com) 🔨: A variety of 7800 development tools for game development, graphics, audio, debugging and more.

### 7800 Graphics

* [Aseprite](https://www.aseprite.org) 🔨💵: Sprite editor and animator.

* [Maria Painter](https://www.atari.org.pl/informacje/eagle-maria-painter-dla-atari-7800/2723) 📄: Atari 7800 ProSystem has remained in the shadow of eight-bit Atari XL/XE computers for years, and it also lacks such a rich toolbase. Eagle Maria Painter is to change that by offering an advanced online graphics editor, created specifically for the unique MARIA layout and its 160B mode.

### 7800 Sound

* [7000 Jukebox: A simple POKEY music engine with some ported NES songs](https://forums.atariage.com/topic/390663-a-simple-pokey-music-engine-with-some-ported-nes-songs/) 🔨: A lot of 7800 programmers prefer using RMT (Raster Music Tracker) as a way to create their sound files for POKEY.  My approach has been a little different.  The program I have built (the POKEY Jukebox) is rather bare-bones with a focus on keeping RAM / ROM / CPU limited while still trying to sound decent.

* [7800 TIA SFX Library, sound2tia by Mike Saarna](https://forums.atariage.com/topic/301293-7800-tia-sfx-library-sound2tia/) 🕹️: I've expanded the library of sound effects that come with the 7800basic "soundtest" program. Currently there's 116 fairly distinct sound effects.

### 7800 Text

* [Atari Font Maker by Martin Šimeček](https://github.com/matosimi/atari-fontmaker)  🔨: Atari FontMaker is a Windows tool used for creating and editing Atari 8-bit/5200 fonts and font-based graphics.

## Language Specific Pages

* **[batari Basic](batari.md)**
* **[7800basic](7800basic.md)**
* **[2600 Assembly](2600asm.md)**
* **[7800 Assembly](7800asm.md)**
