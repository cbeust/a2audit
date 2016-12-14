# Apple II Audit

This repository contains routines to audit Apple II computers (II, II+,
IIe, IIc), providing information about hardware, ROM versions, RAM
configuration, and behavior.

Eventually, it should comprise an emulator test suite, enabling
emulator writers to systematically identify and eliminate perceptible
differences from real hardware. If a difference visible to code can be
found, a test should be added to this suite.

## Status

I'm just getting started, currently working on:

- experimenting with toolchains for automation
- preliminary floating-bus vsync examples
- sha1sum assembly code

This test suite is a step on the way to implementing Apple IIe
(enhanced) support in
[OpenEmulator](http://openemulatorproject.github.io/): I may alternate
adding tests here and features there.