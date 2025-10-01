## Disclaimer

This software is provided for legitimate automation purposes. Users are responsible for ensuring their use complies with the terms of service of any applications they automate. The developers assume no liability for misuse.

<div align="center">

![photo_2025-09-28_20-33-38(1)](https://github.com/user-attachments/assets/bcd4418f-46c8-4ff2-9e48-521d010cf0f0)
  
# RuClick
AutoClicker with Macro Support for Windows

[![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet)](https://dotnet.microsoft.com/)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?logo=windows)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![WPF](https://img.shields.io/badge/WPF-XAML-blue)](https://github.com/dotnet/wpf)

</div>

---

## Features

### Mouse Automation
- **Multiple Click Types**: Single, Double, Triple, and Hold clicks
- **Smart Positioning**: Current cursor position or fixed coordinates with F9 hotkey capture
- **Random Spread**: Add randomness to click positions for anti-detection
- **Position Preview**: Real-time visual preview of click location
- **Cursor Lock**: Lock cursor to fixed position during automation to prevent movement

### Keyboard Automation
- **Auto Key Pressing**: Automate any keyboard key
- **Configurable Intervals**: Precise timing from 1 millisecond to hours
- **Repeat Control**: Infinite loop or custom repeat count

### Macro Recording & Playback
- **Record Actions**: Capture mouse clicks and keyboard inputs in real-time
- **Playback Macros**: Replay recorded sequences with customizable repeat settings
- **Macro Management**: Save, load, and delete macros with easy dropdown selection

### Profile Management
- **Save Profiles**: Store complete application configurations
- **Quick Load**: Select profiles from dropdown menu
- **Profile Reset**: Select placeholder to reset all settings to defaults
- **Auto-Location**: Profiles stored in `%APPDATA%\RuClick\Profiles\`

### Advanced Settings
- **Reset Settings**: One-click reset to factory defaults
- **Quick System Commands**: Fast access to Windows shortcuts (Win+R, Task Manager, etc.)
- **Multilingual Support**: 12 languages with automatic UI updates
- **Dark Theme**: Modern, eye-friendly dark interface

### Statistics & Tracking
- **Total Click Counter**: Track all clicks performed
- **Session Statistics**: Monitor current session activity
- **Daily Statistics**: View today's usage
- **Program Uptime**: Total time using the application
- **Persistent Storage**: Statistics saved automatically to `%APPDATA%\RuClick\`

### Download & Run
1. Download the latest `RuClick.exe` from [Releases](../../releases)
2. Run the executable - no installation required
3. Application data will be created in `%APPDATA%\RuClick\`

### Building from Source
```bash
# Clone the repository
git clone https://github.com/Akzeptiert/RuClick.git
cd RuClick/RuClick

# Build the project
dotnet build -c Release

# Publish as single executable
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

The compiled executable will be in `bin\Release\net8.0-windows\win-x64\publish\`

---

## Hotkeys

| Hotkey | Action |
|--------|--------|
| **F6** | Start/Stop Auto Clicker |
| **F7** | Record/Stop Macro |
| **F8** | Play/Stop Macro |
| **F9** | Capture Cursor Position |

---

## Supported Languages

RuClick supports 12 languages with full UI translation:

- English (Default)
- Russian (Русский)
- Ukrainian (Українська)
- German (Deutsch)
- French (Français)
- Spanish (Español)
- Italian (Italiano)
- Portuguese (Português)
- Polish (Polski)
- Turkish (Türkçe)
- Japanese (日本語)
- Chinese (中文)

Language can be changed from the dropdown menu in the interface. When resetting settings, language automatically reverts to English.

---

## Technology Stack

- **Framework**: .NET 8.0
- **UI**: WPF (Windows Presentation Foundation)
- **Architecture**: MVVM (Model-View-ViewModel) pattern
- **Language**: C# 12
- **Build**: Self-contained single-file executable

---

## Data Storage

All application data is stored in `%APPDATA%\RuClick\`:

This ensures:
- Data persists across application updates
- No administrator permissions required
- Easy backup and transfer of settings
- Clean uninstallation (just delete the folder)

---

## System Requirements

- **Operating System**: Windows 10 (64-bit) or Windows 11
- **Memory**: Minimal (< 50 MB RAM)
- **Storage**: ~70 MB for executable
- **Permissions**: No administrator rights required
- **.NET Runtime**: Not required (self-contained build)

[Report Bug](../../issues) · [Request Feature](../../issues)
