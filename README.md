# Exploring LabVIEW for Microcontrollers

This is a project for exploring and prototyping possibilities for an open source tool to deploy LabVIEW code to various microcontrollers (e.g. the Raspberry Pi Pico / RP2040 and others).

There have been a variety of projects and related work done on this effort by different people over the years. Here we will start by taking inventory on the work done by others, discuss possibilities, experiment with ideas, develop prototypes, and a share a roadmap toward making this a real capability for LabVIEW developers!

### Current Exploration

*   [Compiling Vireo to a Microcontroller Target (discussion)](https://github.com/labview-for-microcontrollers/exploring-labview-for-microcontrollers/discussions/2) - We're exploring what it would take to get NI's VireoSDK to compile to a microprocessor target.  Vireo can run VI Assembly (VIA) files, which are an output of LabVIEW's Web UI Builder (and LabVIEW NXG). Since Viero is written in C++ this could be a viable option with the right technical expertise.

### How to Help

*   [Join the Discussion](https://github.com/labview-for-microcontrollers/exploring-labview-for-microcontrollers/discussions) - You can post questions and ideas in our [discussion forum](https://github.com/labview-for-microcontrollers/exploring-labview-for-microcontrollers/discussions) here on the github project.
*   Contribute your Expertise - If you have expertise in compilers, microcontrollers, or other skills that could benefit this project, [please let us know by posting in the discussion forum](https://github.com/labview-for-microcontrollers/exploring-labview-for-microcontrollers/discussions)!

### Various Related Projects and Products of Interest

*   [NI LabVIEW C Generator](https://www.ni.com/en-us/support/downloads/software-products/download.labview-c-generator-module.html#322515) - an add-on for LabVIEW from NI that helps you create C code from LabVIEW VIs for specific targets.
*   [NI VireoSDK](https://github.com/ni/VireoSDK) - a compact runtime written in C++ for a subset of LabVIEW, which is maintained by NI.  It runs VI Assembly (VIA) which are an output of LabVIEW (NXG) Web UI Builder. It can be compiled to various environments including Windows, Mac, Linux, JavaScript, and others.
*   [chrisbuerginrogers - LVTargets](https://github.com/chrisbuerginrogers/LVTargets) - LabVIEW NXG add-on to making LabVIEW NXG generate Vireo and add your own plugin to do something with that code.
*   [Raspberry Pi Compatible Compiler for LabVIEW](https://github.com/labviewforRaspi/LabVIEWforRasPi) - An inactive project/product for compiling LabVIEW code to Raspberry Pi (Raspberry Pi 3B+, 4B were not supported)
*   [Arduino Compatible Compiler for LabVIEW](https://www.ni.com/en-us/support/downloads/tools-network/download.arduino--compatible-compiler-for-labview.html#379003) - A commercial product for compiling LabVIEW code to the Arduino
*   [TylorH - C code Generator for LabVIEW](https://github.com/taylorh140/LabVIEWCGen) - A very elementary C code generator for LabVIEW (move of a simple proof of concept)
*   [LabVIEW Hobbyist Toolkit (Linx)](https://www.ni.com/en-us/support/downloads/tools-network/download.labview-hobbyist-toolkit.html#376574) - An add-on for LabVIEW that allows targeting Hobbyist boards with linux OS (like Raspberry Pi and BeagleBone) that can run a port of NI Linux RT
