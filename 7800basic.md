# 7800basic

This list currently focuses on libraries, tutorials, books and other resources for building games for the Atari 7800 in BASIC.

* [7800basic by Mike Saarna](https://github.com/7800-devtools/7800basic) ![GitHub stars](https://img.shields.io/github/stars/7800-devtools/7800basic?cacheSeconds=604800) ![GitHub last commit](https://img.shields.io/github/last-commit/7800-devtools/7800basic?cacheSeconds=86000): 7800basic is a BASIC-like language for creating Atari 7800 games.  It is a compiled language that runs on a computer, and it creates a binary files that can be run with Atari 7800 emulators and flash carts, or the binary files can be used to create a cartridge that will operate on a real Atari 7800.

Note: Official documentation is included in the download and is also hosted online at [Random Terrain](https://www.randomterrain.com/7800basic.html)

* [7800 Programming Forum on AtariAge](https://forums.atariage.com/forum/52-atari-7800-programming/): Not exclusive to 7800basic.

## Learning

* [Getting Started](#getting-started)

## Reference

* [Sprites](#sprites)
* [Playfields](#playfields)
    * [Title Screen](#title-screen)
* [Sound](#sound)
* [Text](#text)

# Learning

## Getting Started

* [Atari 7800 Basic by Jeff Fulton and Steve Fulton](https://www.youtube.com/playlist?list=PL0cskbD0URcyumwcHgrQSIgT9-DNmWF6Z) 📽️: Learn To program the Atari 7800 in Atari 7800 basic.

* [7800basic for Newbies: A Tutorial by Steve Engelhardt](https://forums.atariage.com/topic/270167-7800basic-for-newbies-a-tutorial-part-1/) 📄: There haven’t really been any good tutorials posted as of yet on how to get started. I’d like to address that with a series of tutorials that start from the very beginning. Once I cover the basics, I’d like to actually go through the process of making a simple game, step by step, with as much detail as I can realistically provide.

* [Official documentation by Mike Saarna](https://github.com/7800-devtools/7800basic) 📚: RTFM.

# Reference

* [Official Samples](https://github.com/7800-devtools/7800basic/tree/master/samples) 🔨: A variety of sample code on the official repository.

* [Eagle Tools](https://7800tools.com) 🔨: A variety of 7800 development tools for game development, graphics, audio, debugging and more.

## Sprites

* [Aseprite](https://www.aseprite.org) 🔨💵: Sprite editor and animator.

## Playfields

* [Creating 7800basic compatible maps with the Tiled app by Steve Engelhardt](https://forums.atariage.com/topic/227696-creating-7800basic-compatible-maps-with-the-tiled-app/) 📄: I thought I'd review the steps on how to create a tiled background image for use with 7800basic, specifically for a map that will work with the 160A display mode along with 'set doublewide on' in your code. It works great and is a big time saver.

* [Eagle Tools](https://www.atari.org.pl/informacje/eagle-maria-painter-dla-atari-7800/2723) 🔨: Atari 7800 ProSystem has remained in the shadow of eight-bit Atari XL/XE computers for years, and it also lacks such a rich toolbase. Eagle Maria Painter is to change that by offering an advanced online graphics editor, created specifically for the unique MARIA layout and its 160B mode.

### Title Screen

* [Ditherton Image Converter by Steven Hugg](https://8bitworkshop.com/dithertron/#sys=c64.multi&image=seurat.jpg) 🔨: A web-based image conversion utility designed to take modern, high-resolution digital images (like JPGs and PNGs) and crunch them down to fit the Atari 2600 among other platforms.

## Sound

* [7000 Jukebox: A simple POKEY music engine with some ported NES songs](https://forums.atariage.com/topic/390663-a-simple-pokey-music-engine-with-some-ported-nes-songs/) 🔨: A lot of 7800 programmers prefer using RMT (Raster Music Tracker) as a way to create their sound files for POKEY.  My approach has been a little different.  The program I have built (the POKEY Jukebox) is rather bare-bones with a focus on keeping RAM / ROM / CPU limited while still trying to sound decent.

* [7800 TIA SFX Library, sound2tia by Mike Saarna](https://forums.atariage.com/topic/301293-7800-tia-sfx-library-sound2tia/) 🕹️: I've expanded the library of sound effects that come with the 7800basic "soundtest" program. Currently there's 116 fairly distinct sound effects. 

## Text

* [New Fonts for 7800basic by Steve Engelhardt](https://forums.atariage.com/topic/340313-new-fonts-for-7800basic/) 🕹️: I worked on creating some new fonts off and on today and I thought I'd share my progress.  I've got a few more in mind I'd like to create and I'll share them in this thread when I'm finished. Feel free to use any of these in of your own projects.

* [Atari Font Maker by Martin Šimeček](https://github.com/matosimi/atari-fontmaker)  🔨: Atari FontMaker is a Windows tool used for creating and editing Atari 8-bit/5200 fonts and font-based graphics.
