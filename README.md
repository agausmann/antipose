# antipose

A tiny MX switch breakout board.

## Features

- 5 keys
- Hot swap
- Reversible/mirrored layout on both sides (e.g. make one for each hand)
- Simple pin headers to connect

## Motivation

I had a small sample pack of 10 keyboard switches, and I wanted to test how
they feel in osu!mania. I figured I could just attach them to a breadboard and
make a simple keyboard controller out of an Arduino or something, but the PCB
mount pins and the stem cutout got in the way of the breadboard, and they
simply would not fit. So I made this PCB to solve that!

I also realized this is pretty similar to the [ASETNIOP](https://asetniop.com)
layout, hence the name (an anagram of ASETNIOP). I imagine this PCB could also
be used to try out ASETNIOP if you want to.

At first I thought about adding a microcontroller and USB port, but I realized
it's really not worth the hassle (time, money, and design effort) - I have
several MCU boards lying around that I could connect to it non-permanently. So
instead it's just a generic pin header that you can adapt to whatever you have
lying around.
