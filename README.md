# PC Fixer

## Overview
PC Fixer is a simple and intuitive tool designed to help maintain and optimize your Windows PC. Created by CeresF3B and improved by Trae AI, this tool performs various system maintenance tasks with just a few clicks.

## Features

- **One-Click Maintenance**: Fully automated or customizable system optimization.

- **Main Functions**:

    - 🗑️ **Temp/Prefetch Cleaning**: Aggressively removes junk files from %TEMP%, Windows\Temp, and Prefetch.

    - 🔧 **System Repairs**:
        - SFC /scannow for file integrity checks.
        - DISM /CheckHealth for an initial system health assessment.
        - DISM /ScanHealth for a more thorough system scan.
        - DISM /RestoreHealth for complete operating system image repair.

    - 🌐 **Network Reset**: Flushes DNS cache, resets Winsock and IP configurations.

    - 🔋 **Battery Report**: Generates an HTML diagnostic report on battery health.
    
    - ⚡ **Full Automatic Mode**: Runs all tasks in sequence for hands-free maintenance.

- **Easy to Use**:

    - Interactive menu with colored status updates (✅ success, ❌ errors).

    - Automatic administrator rights elevation through batch file.

    - Clear exit message with thank you note.
    
    - Also available in Rubber Ducky version for advanced automation.

## Usage

- **No Technical Knowledge Required**: This tool is designed for all users, regardless of computer experience.

- **Simple Operation**:
    - Double-click on `PCFixer_Launcher.bat` (no manual administrator rights needed).
    - When prompted, click "Yes" to allow administrator permissions.
    - Choose an option from the menu by typing the number (1-5) or Q to exit.
    - Wait for the selected operation to complete.

- **Direct Execution via PowerShell**:
    - Open PowerShell.
    - Copy and paste this command: `irm https://raw.githubusercontent.com/CeresF3b/PC-Fixer/main/PCFixer.ps1 | iex`
    - The script will execute directly without downloading any files.
    - Follow the on-screen menu instructions.

- **Options**:
    - **Quick Fix**: Select 5 for full automatic maintenance.
    - **Manual Control**: Choose specific tasks (1-4).
    - **Exit**: Press Q to exit with a thank you message.
    
- **Rubber Ducky Version**:
    - Use the `PCFixer.txt` file for automation via Rubber Ducky devices.
    - The Rubber Ducky script uses the direct PowerShell command method for simplified execution.

## System Requirements
- Windows 10 or Windows 11
- Administrator privileges (automatically requested by the launcher)

## Notes
- The battery report function is only useful for laptop users
- Some operations may take several minutes to complete
- All operations are safe and follow Microsoft's recommended maintenance procedures
- Rubber Ducky script is available for advanced automation
