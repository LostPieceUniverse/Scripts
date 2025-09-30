# My BASH scripts
## Description

These scripts were crafted out of a combination of laziness and a love for tinkering. They serve various purposes, 
from automating mundane tasks to experimenting with different programming concepts.

## Scripts

**Bash:** ```Bash <filename>```
- Creates a Bash script file (filename.sh) with the shebang pre-written.
- Automatically adds executable permissions to the created script.
- Opens the file in your default editor for immediate editing.

**c#:** ```c# <project name>```
- Generates a new C# console application using `dotnet new console --use-program-main` with provided project name.
- Opens the generated Program.cs file in Neovim for immediate editing.
- Note: Requires .NET SDK.

**mdToPdf:** ```mdToPdf <markdownfile.md>```
- Converts a Markdown file to a PDF.
- Uses Pandoc for the conversion, which is convenient when working with Markdown files frequently.

**Update:** ```sudo /path/to/Update``` or ```sudo $(which Update)```
  - Run as root
  - Colored output with timestamps
  - Internet connectivity check
  - Updates pacman, AUR (yay), Flatpak
  - Firmware updates (fwupdmgr)
  - Cache cleaning
  - Reboot notifications
  - Error handling with `set -euo pipefail`
  - Note: Because sudo uses a restricted PATH, you must either:
    - Use the full path to the script (e.g., `/home/user/scripts/Update` or `/usr/local/bin/Update`)
    - Use command substitution: `sudo $(which Update)`
    - Alternatively, add an alias to your shell config: `alias update='sudo $(which Update)`'

