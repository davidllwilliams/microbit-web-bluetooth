# micro:bit Web Bluetooth

[![Circle CI](https://circleci.com/gh/thegecko/microbit-web-bluetooth.svg?style=shield&circle-token=a6f81fc05746394a595d8fe2b7c02eaf3120794b)](https://circleci.com/gh/thegecko/microbit-web-bluetooth/)
[![npm](https://img.shields.io/npm/dm/microbit-web-bluetooth.svg)](https://www.npmjs.com/package/microbit-web-bluetooth)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://spdx.org/licenses/MIT.html)

Web Bluetooth library for micro:bit implementing the [micro:bit Bluetooth Profile](https://lancaster-university.github.io/microbit-docs/resources/bluetooth/bluetooth_profile.html).

See the [microbit-web-components library](https://github.com/thegecko/microbit-web-components) for some ready-to-use web components which use this library.

## Prerequisites

[Node.js > v10.16.0](https://nodejs.org), which includes `npm`

## Getting Started

Refer to the [micro:bit Web Bluetooth API Documentation](https://thegecko.github.io/microbit-web-bluetooth/) for more information.

## Implementation Status
- [x] micro:bit Discovery
- [x] Service enumeration

### Device Information Service
- [x] Model Number
- [x] Serial Number
- [x] Hardware Revision
- [x] Firmware Revision
- [x] Manufacturer

### LED Service
- [x] LED Matrix State
- [x] LED Text
- [x] Scrolling Delay

### Button Service
- [x] Button A State
- [x] Button A State Changed Event
- [x] Button B State
- [x] Button B State Changed Event

### Temperature Service
- [x] Temperature
- [x] Temperature Changed Event
- [x] Temperature Period

### Accelerometer Service
- [x] Accelerometer Data
- [x] Accelerometer Data Changed Event
- [x] Accelerometer Period

### Magnetometer Service
- [x] Magnetometer Data
- [x] Magnetometer Data Changed Event
- [x] Magnetometer Period
- [x] Magnetometer Bearing
- [x] Magnetometer Bearing Changed Event
- [x] Magnetometer Calibration

### UART Service
- [x] Send
- [x] Receive Event
- [x] SendString
- [x] ReceiveString Event

### Event Service
- [x] MicroBit Requirements
- [x] MicroBit Event
- [x] Client Requirements
- [x] Client Event

### IO Pin Service
- [x] Pin Data
- [x] Pin Data Changed Event
- [x] Pin AD Configuration
- [x] Pin IO Configuration
- [x] PWM Control

### DFU Control Service
- [x] Request DFU
- [x] Request Flash Code



> Open this page at [https://davidllwilliams.github.io/microbit-web-bluetooth/](https://davidllwilliams.github.io/microbit-web-bluetooth/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/davidllwilliams/microbit-web-bluetooth** and import

## Edit this project ![Build status badge](https://github.com/davidllwilliams/microbit-web-bluetooth/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/davidllwilliams/microbit-web-bluetooth** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/davidllwilliams/microbit-web-bluetooth/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
