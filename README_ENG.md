<div align="center">

![photo_2025-09-28_20-33-38(1)](https://github.com/user-attachments/assets/bcd4418f-46c8-4ff2-9e48-521d010cf0f0)
  
# RuClick
Auto Clicker with Macro Recording for Windows

[![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet)](https://dotnet.microsoft.com/)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?logo=windows)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![WPF](https://img.shields.io/badge/WPF-XAML-blue)](https://github.com/dotnet/wpf)

**English** | [Русский](README.md)

</div>

---

## Features

### Mouse
- **Different click types**: single, double, triple, or hold the button
- **Position options**: click where cursor is, or at a specific screen point (capture with F9)
- **Click spread**: adds small variations to position to look more natural
- **Position preview**: shows on screen exactly where the click will be
- **Cursor lock**: cursor won't move from the set point during operation
- **High speed**: up to 500+ clicks per second with a minimum interval of 1 millisecond

![animation(1)](https://github.com/user-attachments/assets/40c68149-1eed-4a7e-a3e7-2a7391b44d7d)
<img width="697" height="685" alt="{079E6D70-B66A-4B90-8CC4-B94AF87EDB33}" src="https://github.com/user-attachments/assets/865a8b14-5464-4f30-a783-b9f958ad9493" />

### Keyboard
- **Key pressing**: automate any keyboard button
- **Interval settings**: from 1 millisecond to several hours
- **Repeat count**: infinite or a set number of times
<img width="697" height="520" alt="{35977830-A1B8-48CC-B2CF-BBC2626C353E}" src="https://github.com/user-attachments/assets/225b4026-44db-449b-a875-ccae063d686b" />

### Macros
- **Recording**: the program remembers mouse clicks and key presses
- **Playback**: repeats what was recorded with desired settings
- **Macro management**: save, load, and delete through the menu
<img width="658" height="304" alt="{3F5F8B10-43D7-41FB-8AA0-D4EB15013D4B}" src="https://github.com/user-attachments/assets/b6b67b01-051f-4da2-a98c-c301b79f9812" />

### Profiles
- **Saving profiles**: you can save all program settings
- **Quick loading**: pick a profile from the list
- **Reset settings**: select placeholder to return everything to defaults
- **Storage location**: profiles are stored in `%APPDATA%\RuClick\Profiles\`

### Extra
- **Reset**: return the program to default settings with one button
- **System commands**: quick launch of Win+R, Task Manager, and other Windows functions
- **12 languages**: pick the language you need, interface changes instantly
- **Dark theme**: comfortable dark interface
<img width="697" height="670" alt="{C53E5F7B-A12C-4B0F-976B-9D05B38230C7}" src="https://github.com/user-attachments/assets/3950d56a-3d99-4825-bed9-465b8899ea88" />

### Statistics
- **Click counter**: shows how many clicks were performed
- **Session stats**: how long you've been working right now
- **Daily stats**: what was done today
- **Runtime**: total time using the program
- **Auto-save**: statistics are saved automatically to `%APPDATA%\RuClick\`
<img width="697" height="682" alt="{327EB681-DEC2-4948-807E-C542F69568C6}" src="https://github.com/user-attachments/assets/c66337fd-a213-4553-a924-13f6317cc8c2" />

---

## Getting Started

### Download and run
1. Download `RuClick.exe` from [Releases](../../releases)
2. Run the file — no installation needed
3. Data folder will be created automatically in `%APPDATA%\RuClick\`

> **Note**: Windows SmartScreen might show a warning about "unknown app" because the file isn't digitally signed. This is normal for open-source projects. Click **"More info"** → **"Run anyway"**.

### Build it yourself
```bash
# Download code
git clone https://github.com/Akzeptiert/RuClick.git
cd RuClick/RuClick

# Build project
dotnet build -c Release

# Create single exe file
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

The ready file will be in `bin\Release\net8.0-windows\win-x64\publish\`

---

## Hotkeys

| Key | What it does |
|---------|----------|
| **F6** | Start/stop auto clicker |
| **F7** | Start/stop macro recording |
| **F8** | Play macro |
| **F9** | Remember cursor position |

---

## Languages

RuClick has 12 languages with full translation:

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
<img width="427" height="343" alt="{50E354CA-4844-4BB1-ADBA-222FF075CBB2}" src="https://github.com/user-attachments/assets/8ca3cfa8-ea63-4e4c-be87-e26cbef58bca" />

Language changes in the dropdown menu. When you reset settings, language goes back to English.

---

## What's used

- **Framework**: .NET 8.0
- **Interface**: WPF (Windows Presentation Foundation)
- **Architecture**: MVVM (Model-View-ViewModel)
- **Language**: C# 12
- **Build**: single exe file with everything included

---

## Where data is stored

All program files are in `%APPDATA%\RuClick\`:

<img width="658" height="619" alt="Снимок экрана 2025-10-02 204803" src="https://github.com/user-attachments/assets/6a5a6657-0be4-4efb-bccd-de6d6695b92a" />

Benefits:
- Data won't disappear when updating the program
- No admin rights needed
- Easy to backup or move to another computer
- To delete everything — just delete this folder

---

## System Requirements

- **OS**: Windows 10 (64-bit) or Windows 11
- **Memory**: Low (less than 50 MB)
- **Disk space**: about 70 MB for the exe file
- **Permissions**: Admin not needed
- **.NET Runtime**: Not needed (everything is built-in)

---

## License

The project is under the MIT License — details in [LICENSE](LICENSE) file.

---

## Important

The program is made for legal automation. You're responsible for how you use it and for following the rules of apps you automate. Developers are not responsible for misuse.

---

<div align="center">

[Report Bug](../../issues) · [Suggest Idea](../../issues)

</div>


