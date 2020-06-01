---
layout: post
title: EmbeddedTalks #1
---

Hello from embeddedTalks!

## Topics:  

1. Books from [edition LCTHW](https://learncodethehardway.org/): " The vast majority of C programmers out there simply don’t write solid code, and it’s because of something called **Undefned Behavior (UB)**. Undefned Behavior is a part of the American National Standards Institute C standard that lists all of the ways that a C compiler can disregard what you’ve written. There’s actually a part of the standard that says if you write code like this, then all bets are oﬀ and the compiler doesn’t have to do anything consistent. UB oﬀ the end of a string, which is an incredibly common programming error in C."
  * good tool to use against UB: Static code analisys tool - LINT
  * http://www.valgrind.org/info/tools.html


2. Make files and how well we need to know them
  * it is good to know the basics
  * Cmake is becomming more popular https://cmake.org/

3. Embedded software simulators... who how where???
  * http://www.throwtheswitch.org/ceedling
  * https://github.com/meekrosoft/fff
  * Moocking vs faking functions (what is the difference)
  * https://www.raywenderlich.com/9454-introduction-to-unity-unit-testing
  * https://www.qemu.org/ - emulator
  * https://medium.com/@ly.lee/stm32-blue-pill-unit-testing-with-qemu-blue-pill-emulator-9d88002a68b2

4. Architecture of adding new module, example RGB LED:
  * It is important to understand how to create application layers, and in this case we can make:
    * GPIO(PWM) - usualy implemented in HAL
    * RGB LED
    * Functionality
  * if we add new LED we can easily add new functionalities

## Interesting Links:
* https://github.com/tmuxinator/tmuxinator
* https://www.gitkraken.com/ - cool tool fir git

