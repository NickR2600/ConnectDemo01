# ConnectDemo01

## Before You Begin ##

### About These Lab ###
These labs are an introduction to JFrog Connect, the Internet of Things (IoT), and edge computing. They are part of a Connect 101 workshop. It's introductory/beginner-friendly.

### About JFrog Connect ###
JFrog Connect is a modern Linux-first IoT platform designed to efficiently monitor, manage and update edge and IoT devices at scale. This is performed over a network connection, also known as over the air (OTA). The combined integration of JFrog Connect, with the JFrog Platform, allows automate software deployment from developer to device and avoid security vulnerabilities reaching production devices. Use-cases include manufacturing, automotive, security cameras, kiosks, and robots.

### Target Audience ###
Technical people developing (or curious about) IoT and edge solutions, software engineer, DevOps engineers and architects, R&D, IT architects and managers.

### Contents ###
- The `code` directory contains source code you will need for these labs.
- The `img` directory stores images used in the lab instructions
- Lab: [Readying a Raspberry Pi](/Ready-RPi.md)
- Lab: [Readying a Demo Device](/Ready-demo-device.md)
- Lab: [Push Files to a Device, Compile, and Run](/Initial-files.md)
- Lab: [Update a Device While its Program Runs](/Update-device.md)

## Instructions ##
It's recommended that you have a Raspberry Pi (RPi) for these labs. If you don't have one, Connect can create a demo device.
- [Start here if you have a RPi](Ready-RPi).
- [Start here if you don't have a RPi](Ready-demo-device).

## Workshop Abstract ##
**101 for JFrog Connect - Workshop**

There’s an estimated 12 billion+ networked devices in the world. These makeup the Internet of Things (IoT), which includes robots, kiosks, cars, security cameras, medical devices, and maker devices that run off a Raspberry Pi (RPi). Manually updating software across a large fleet of devices can be a slow process, especially when devices are often in hard-to-reach locations. JFrog Connect lets you quickly update software across fleets of Linux-based IoT and edge computing devices. Updating across a network connection is known as an over-the-air (OTA) update. Connect also monitors device health. This is where DevOps meets IoT. This workshop offers several labs with step-by-step instructions. Bring an RPi or create a virtual demo device in Connect. If you don’t already have Connect, we’ll show you how to access a free-tier instance. Lab files are available through GitHub. We’ll cover these topics:
- The Story of Chips, Sensors, and Devices
  - What are IoT and edge computing?
  - Industry use-cases, potentials, and risks
- Lab 1: Readying a RPi or Virtual Demo Device
  - Required RPi hardware and setup
  - Access a free-tier instance of Connect
  - Register a device using Connect and the Connect Agent
  - What is the Connect Agent?
- OTA Updates
  - Lab 2: Push files to a device, compile, and run
  - Lab 3: Update a device while its program runs
- At Scale
  - Tips and good practices
  - Security considerations
