
# Download and install Windows Terminal

## Requirements

- Run the script as administrator using PowerShell
  
## Installation

- Right click on the Windows Start icon 🪟 then select Windows PowerShell (Admin).
- Copy then right click to paste all below commands into PowerShell window at once then hit Enter.
- Allow system to running a script: https://go.microsoft.com/fwlink/?LinkID=135170

```ps
Set-ExecutionPolicy Bypass -Scope Process -Force
$url="https://raw.githubusercontent.com/bonben365/terminal-installer/main/install.ps1"
iex ((New-Object System.Net.WebClient).DownloadString($url))
```
➡️Please inspect https://raw.githubusercontent.com/bonben365/terminal-installer/main/install.ps1 prior to running any of these scripts to ensure safety. We already know it's safe, but you should verify the security and contents of any script from the internet you are not familiar with.

## Screenshots

![App Screenshot]()

## Documentation

[🌍https://bonben365.com/](https://bonben365.com/)

