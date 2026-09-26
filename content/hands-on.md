---
title: "Hands-On Opportunities"
description: "Build something at a CARPE meeting — bring your own devices or borrow ours. The only hard requirement is a laptop."
---

Every CARPE meeting has room to get hands-on. **Bring your own devices, or borrow ours at the
meetup** — either way works, and you can mix the two.

**The only hard requirement is a laptop**, so you can work on code and flash your devices. Bring
a USB cable that fits your board if you have one.

## Bring your own devices

Bring your breadboard, microcontrollers and sensors — a Pico W, an ESP32, an Arduino, whatever
you're working with. Finished project or a bag of parts, it all fits.

For multi-device projects, the **Deevnet Mobile Factory** — a portable IoT platform one of our
members brings to meetings — gives your devices a network and ready-made back-end services:
MQTT messaging, logs and dashboards, declared from your own Terraform, with no cloud account.
It's optional: plenty of projects need nothing but a USB cable.
[How the Mobile Factory works →](https://deevnet.github.io/deevnet-docs/)

## Borrow devices at the meetup

### Starter kits

New to electronics? A couple of **starter kits** are on hand so you can try things out — blink
your first LED, put something on a display, or play with a few simple sensors. We'll help you
get set up.

### Project kits

A **project kit** is a complete project that comes pre-wired and already running reference
firmware. You borrow it for the evening, see it work in minutes, then change it and make it
yours. Each kit teaches one pattern you can reuse in your own builds.

These are in the works. Wiring, parts lists and reference firmware will be published in the
[carpe-tech GitHub organization](https://github.com/carpe-tech) as each kit is built.

| Kit | What it does | What it teaches |
|---|---|---|
| **Motion show** | A motion sensor triggers an RGB LED strip and sound through an I2S amp. It started life as a Halloween pumpkin, but the combo fits plenty of other builds | Sense, then react with light and sound |
| **Environment station** | Temperature, humidity, pressure and light readings, charted on a dashboard | Sense and publish |
| **Button ↔ buzzer pair** | Press a button on one table, and a buzzer and light go off on another | Two devices talking through a broker |
| **Sound meter** | An I2S microphone measures sound levels and charts them | Streaming audio data |
| **Shared pixel canvas** | An LED matrix that anyone in the room can send pixels to | Many publishers, one display |
| **Camera with object detection** | An ESP32 camera takes snapshots and detects what's in them | Images, and where the heavy lifting runs |
| **Colour screen** | A small colour TFT display showing messages and status sent to it | Driving a graphical display |
| **Serial screen** | A character display driven over a serial connection | The simplest display there is |

Have an idea for a kit, or a project you'd lend out? Mention it in
[Discord](https://discord.gg/JjqR5dPYem) or at a meeting.

### Borrowing a project kit onto the Mobile Factory

A project kit joins the Mobile Factory as a device in **your own** tenant, with your own Wi-Fi
key and broker account, and you hand it back at the end of the night with nothing of yours left
on it. The platform side of borrowing and returning a kit is in the Deevnet docs:
[Project Kits](https://deevnet.github.io/deevnet-docs/docs/runbook/tenant/project-kits/).
