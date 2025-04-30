# Breadmatrix

## About

This is a neopixel 8x8 matrix, powered by the ESP32-S3-DevkitC. I also added a breadboard-like thing to it, using normal connector footprints.

## Challenges

Since I wanted 64 neopixels for my matrix, I needed a lot more current than the Devkit´s 500mA. Since this was originally a pixeldust project (before I submitted [an easier one](https://github.com/hackclub/pixeldust/tree/master/submissions/glowstick)), I used the PD manager and the buck converter from the approved parts list. I have never used them before, so I spent days melting my brain in their datasheet to figure out the correct configuration for them.

I´ll also probably need PCBA, since I have never soldered before and the USBC socket, PD manager and buck converter all have a very challenging package with really small pads.
