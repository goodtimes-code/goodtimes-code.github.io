---
layout: default
title: osc2laser - goodtimes | laser crew
---

# osc2laser
osc2laser (***OSC to laser***) enables you to create stunning lasershows - automated by timeline or even by live control. It works on any operating system and with many different applications and laser DACs. It is open-source, driven by the [community](https://github.com/goodtimes-code/osc2laser/graphs/contributors) and [free of charge](#price).

## Use cases
### Timeline lasershow
Use any OSC-enabled software to pre-program your timeline-based lasershow like e.g.
  - [Vezér](https://imimot.com/vezer/) (recommended)
  - [Ableton Live](https://www.ableton.com/live/)
  - Chataigne (free)
  - OSSIA score (free)
  - TWO (free)
  - OSC See
  - Millumin
  - QLab
  - ...

### Live lasershow
Send OSC commands from a software of your choice to control your laser live:
  - [open-stage-control](https://openstagecontrol.ammd.net/) (free)
  - [TouchOSC](https://hexler.net/touchosc)

## Features
- Easy laser output preview (2D)
- Multiple static and animated [laser objects](#laser-objects) included
- Change [parameters](#parameters) of laser objects 
- Many [effects](#effects) for laser objects available

## How it works
1. Start the osc2laser component  ***osc-receiver***. 
 - Provides a 2D preview of your laser output
 - Listens to OSC command from any OSC client
 - Controls the ILDA output of your laser DAC
2. Start any software which sends OSC commands ([some ideas](#use-cases))
 - OSC commands tell the ***osc-receiver*** what to do like...
   - Set laser object (line, circle, dot, wave, ...)
   - Set effect (color, rotatation,...)
   - Set parameters (wave amplitude, length,...)

## Price
However osc2laser is **free** for you, please consider giving something back to the developers to keep their motivation high:
 - [Show and tell us](https://github.com/goodtimes-code/osc2laser/discussions/categories/show-and-tell) what you've built using osclaser.
 - Leave a star for [our GitHub repository](https://github.com/goodtimes-code/osc2laser).
 - [Donate](https://paypal.me/brittabaltz) a small amount to show some thankfullness.

## Download
You can download osc2laser built for your operating system or run the source code on any operating system.

### Download for macOS
 1. Install the .pkg file from our [latest release](https://github.com/goodtimes-code/osc2laser/releases/latest/).

### Download for any OS
1. Checkout the [source code](https://github.com/goodtimes-code/osc2laser).
2. Follow the [tutorial](https://github.com/goodtimes-code/osc2laser#any-os-run-python-code-manually) to adopt it to your operating system.

## Quick start
 1. [Download osclaser](#download) for your operating system.
 2. Follow this [quick start tutorial](https://github.com/goodtimes-code/osc2laser/tree/main?tab=readme-ov-file#quick-start).

## Support
As osc2laser is an open source project, driven by the community, we also only offer community support. Feel free to ask your question in [our forum](https://github.com/goodtimes-code/osc2laser/discussions).

## Contribute
As a ***developer***, feel free to pick any [issue](https://github.com/goodtimes-code/osc2laser/issues), [fork the repository](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and send your [pull request](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) to us.

As a ***laser enthusiast***, feel free to watch [our forum](https://github.com/goodtimes-code/osc2laser/discussions) and answer questions.