# FlashVSR — AMD port (Radeon 8060S)

One-click Windows installer for FlashVSR, ported from NVIDIA-only to AMD. Free.

## What it does

FlashVSR is a video super-resolution tool — it upscales video to a higher resolution, processing it as a stream.

## Tested on

- AMD Ryzen AI Max+ 395 with Radeon 8060S (gfx1151)
- BOSGAME M5

Reported test results from our developer team's testing of the previous 1.1.2 build on that machine: a full-size run upscaled an 85-frame clip from 384 to 1536 resolution, and a short-clip regression run passed; silent install and uninstall passed. This 1.2.0 build supersedes 1.1.2.

## Before you install

**You need the AI Video Suite installed first.** This port uses the Suite's Python and model weights read-only. It is not a standalone package.

**Hardware check — please read first.** The installer checks your hardware before it installs. This build is made for a machine with an AMD Radeon 8060S (gfx1151) and the Suite's PyTorch ROCm stack.

If your machine does not match, the installer shows the specs it found and offers to let you send them to us for review. It then exits without installing anything (exit code 10). Other hardware is not supported by this build.

## Download

Installer: `FlashVSR-AMD-Setup-1.2.0.exe` — 50,791,531 bytes
SHA-256: `3f7434df34dd8044be42dca4268106189893e3b92890f506291f7942bde19a9f`

## We port NVIDIA software to AMD

Hi I'm Hal ports AI software that was made for NVIDIA only, so it runs on AMD hardware.

Got a program you'd like to see ported? Suggest it. And if your AMD machine isn't on our tested list, you can offer your specs for testing through our compatibility program.

Contact us at https://hiimhal.com

## Licence and credit

Licence: Apache License 2.0 (upstream FlashVSR).

Upstream project: https://github.com/OpenImagingLab/FlashVSR — credit to the FlashVSR authors. This port is not affiliated with or endorsed by the upstream project.

Ported by a developer from Ontario.
Home and full catalogue: https://hiimhal.com
Support: hello@hiimhal.com
