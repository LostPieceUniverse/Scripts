# My BASH scripts
## Description

These scripts were crafted out of a combination of laziness and a love for tinkering. They serve various purposes, 
from automating mundane tasks to experimenting with different programming concepts.

## Scripts

**Bash:** ```Bash <filename>```
- Creates a Bash script file (filename.sh) with the shebang (#!/usr/bin/env bash) pre-written in it. It's a shortcut to avoid typing the shebang every time.

**c#:** ```c# <filename>```
- Creates a new directory with the provided name as an argument.
- Generates a basic C# console application using ```dotnet new console```.
- Creates a Program.cs file with a basic structure for a C# console application, including a namespace and a Main method.

**mdToPdf:** ```mdToPdf <markdownfile.md>```
- Converts a Markdown file to a PDF.
- Uses Pandoc for the conversion, which is convenient when working with Markdown files frequently.

**Update:** ```sudo Update```
  - Run as root
  - Colored output with timestamps
  - Internet connectivity check
  - Updates pacman, AUR (yay), Flatpak
  - Firmware updates (fwupdmgr)
  - Cache cleaning
  - Reboot notifications
  - Error handling with `set -euo pipefail`

## Note

**Cpp:** <br>
This script is outdated and, frankly, not up to par with my current standards. 
I may revisit it and make improvements in the future, but for now, it remains as is. 
Apologies for any inconvenience!
