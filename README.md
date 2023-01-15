# Swoop

A WIP fork of [David Barr's Sweep](https://github.com/davidphilipbarr/Sweep), which is itself based on the fabulous [Ferris by Pierre Chevalier](https://github.com/pierrechevalier83/ferris).

<span>
  <a href="https://discord.com/invite/JxfcFuUGhR">
    <img src="https://img.shields.io/static/v1?label=Join Discord:&message=Absolem Club&color=6e85ce">
  </a>
  <img src="https://img.shields.io/github/last-commit/jimmerricks/swoop">
</span>

## Swoop MX / Howarya 🦞

![](./images/howarya_small.jpg)

| Front | Back |
| :---: | :---: |
| ![front](/images/exports/howarya/front.png) | ![back](/images/exports/howarya/back.png) |

### Features
⭕ Cherry MX style switches  
⭕ Hotswap support  
⭕ Per-key RGB LEDs (mini-e)  
⭕ Up to 2 encoders  
⭕ Oled screens  
⭕ Power switch for battery management  
⭕ Bluetooth support w/ nice!nano  
⭕ Plate style case with mcu cover

### Components list

To build and use a Swoop MX you will need:

* 1× PCB Kit
* 2× promicro compatible boards or 2 nice!nanos.
* 34-36× Cherry MX style switches
* 34-36× Kailh hotswap sockets
* 34-36× SK6812 Mini-E RGB SMD Leds (optional; not recommended for wireless)
* 34-36× keycaps
* 36× diodes (Surface-mount or Through-hole)
* 2× Rotary encoders & knobs (optional; ALPS EC11)
* 2× OLED LCD Display 128x32 SSD1306 (optional)
* 2× reset switches (optional; B3U-1000P(M))
* Some little rubber feet/bumpers
* 2× power switches (wireless only; MSK 12C02)
* 2× lipo batteries (wireless only; 301230 or 301228)
* 1× TRRS (not TRS!) cable (wired only)
* 2× TRRS Jack [PJ-320A] (wired only)
* 1× USB Cable (depends on your micro-controller choice)  

**For the case:**

* 32× M2 Screws (3mm thread length)  
* 10× M2 Standoff for the plates (7mm)
* 6× M2 Standoff for the controller cover (8mm)

### How to build it

<a href="https://youtu.be/pvvNYPsMyz4" target="_blank">
  <img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

### Firmware

The firmware is available in QMK as `bluebell/swoop`.  
You can get started by using QMK's [online configurator](https://config.qmk.fm/#/bluebell/swoop/LAYOUT_split_3x5_3). Or check the [Swoop README file](https://github.com/qmk/qmk_firmware/blob/master/keyboards/bluebell/swoop/readme.md) to see how to compile the firmware locally.
