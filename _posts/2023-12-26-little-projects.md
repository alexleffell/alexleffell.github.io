---
layout: post
title:  the sound of goop
date: 2024-01-24 21:01:00
description: bloop bloop
tags: creative dabbles
categories: feeds
thumbnail: 
---
I'm slowly working on a squishy creepy silicone instrument that's also some kind of sculpture. I want to sonicate all sorts of 'human' touch, so I've been playing around with unconventional ways of modulating sound.

I love goops and their calming dynamics, so I had the idea to measure the resistance of some conductive goop and use that signal to modulate some sound. 


Using a Teensy with an audio adapter board and my goop tube as a voltage divider I tried playing the raw signal, but the timescales were too slow. So in the video above I use it to frequency modulate a triangle wave. It has some potential, but it doesn't seem that different from what you'd get from messing around with an accelerometer. I want to try having multiple probes in the goop and have the conductances between them cross modulate some audio signal. I should also find a sweet spot between conductance and viscosity/elasticity that works best to transduce the jiggle of the goop to sound.

<iframe width="560" height="315" src="https://youtube.com/embed/zMojMFyHQ88" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
