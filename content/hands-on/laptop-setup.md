---
title: "Get Your Laptop Ready"
description: "What to install on your laptop so you can write code and flash a Raspberry Pi Pico."
weight: 50
tile: false
---

Your laptop is how you write code and flash your board, so a little setup before the meeting
means more time building. Pick **one** of the options below. If you're not sure, start with
Thonny. Windows, macOS and Linux all work.

These steps are written for the [starter kit](/hands-on/starter-kits/)'s Raspberry Pi Pico, and
work the same for a Pico W.

## Option 1: MicroPython with Thonny (easiest)

Python on the board, and one small app on your laptop.

1. Install [Thonny](https://thonny.org/)
2. Hold the Pico's **BOOTSEL** button while you plug it in with the USB cable
3. In Thonny's interpreter settings, choose **MicroPython (Raspberry Pi Pico)** and use
   **Install or update MicroPython** to put MicroPython on the board
4. Type code in the editor and press **Run**. It runs on the Pico

You only do steps 2 and 3 once per board.

## Option 2: Piper Make in the browser (no install)

Drag-and-drop blocks, good for a first project or younger builders.

1. Open [Piper Make](https://make.playpiper.com/) in **Chrome** or **Edge** (it needs Web Serial,
   which other browsers lack)
2. Follow its setup the first time you connect a Pico

## Option 3: C/C++ with the Arduino IDE

If you already know Arduino, or want to write C/C++.

1. Install the [Arduino IDE](https://www.arduino.cc/en/software)
2. In **Preferences**, add this to **Additional boards manager URLs**:
   `https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json`
3. In the **Boards Manager**, install **Raspberry Pi Pico/RP2040**, then select
   **Raspberry Pi Pico** as the board
4. For the first upload, hold **BOOTSEL** while plugging the Pico in

For the full Raspberry Pi toolchain in VS Code (C/C++ SDK or MicroPython), there's also the
official [Raspberry Pi Pico extension](https://marketplace.visualstudio.com/items?itemName=raspberry-pi.raspberry-pi-pico).
It's more setup, so save it for when you outgrow the options above.

## If the board doesn't show up

- **Use a data cable.** Some USB cables only carry power. The one in the starter kit carries data
- **BOOTSEL mode** makes the Pico show up as a drive called `RPI-RP2`. You can always get back to
  a clean start by dragging a MicroPython `.uf2` file from
  [micropython.org](https://micropython.org/download/RPI_PICO/) onto it
- **On Linux**, your user may need to be in the `dialout` group to use the serial port. Log out
  and back in after adding it

Stuck? Ask at the meeting. Someone will have hit the same thing.
