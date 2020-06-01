---
layout: post
title: EmbeddedTalks-#1
---

First talk about embedded sw - C lenguage, Make files, simulators, etc.

## Topics:  

1. Books from [edition LCTHW](https://learncodethehardway.org/): " The vast majority of C programmers out there simply don’t write solid code, and it’s because of something called **Undefned Behavior (UB)**. Undefned Behavior is a part of the American National Standards Institute C standard that lists all of the ways that a C compiler can disregard what you’ve written. There’s actually a part of the standard that says if you write code like this, then all bets are oﬀ and the compiler doesn’t have to do anything consistent. UB oﬀ the end of a string, which is an incredibly common programming error in C."
  * good tool to use against UB: Static code analisys tool - LINT
  * [valgrind](http://www.valgrind.org/info/tools.html)


2. Make files and how well we need to know them
  * it is good to know the basics
  * [Cmake](https://cmake.org/) is becomming more popular

3. Embedded software simulators... who how where???
  * [throwtheswitch](http://www.throwtheswitch.org/ceedling)
  * [fff](https://github.com/meekrosoft/fff)
  * Moocking vs faking functions (what is the difference)
  * [unit testing](https://www.raywenderlich.com/9454-introduction-to-unity-unit-testing)
  * [qemu](https://www.qemu.org/) - emulator
  * [blue pill on qemu](https://medium.com/@ly.lee/stm32-blue-pill-unit-testing-with-qemu-blue-pill-emulator-9d88002a68b2)

4. Architecture of adding new module, example RGB LED:
  * It is important to understand how to create application layers, and in this case we can make:
    * GPIO(PWM) - usually implemented in HAL
    * RGB LED
    * Functionality
  * if we add new LED we can easily add new functionalities

## Interesting Links:
* [tmuxinator](https://github.com/tmuxinator/tmuxinator)
* [gitkraken](https://www.gitkraken.com/) - cool tool fir git

