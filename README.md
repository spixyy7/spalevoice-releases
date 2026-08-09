# SpaleVoice — installers

This repository holds **only the built installers**. There is no source code
here; it lives in a private repository.

**[Download the latest version](https://github.com/spixyy7/spalevoice-releases/releases/latest)**

SpaleVoice is a dictation utility for Windows: hold a key, talk, and what you
say is typed into whatever window you are already in — Serbian, English or
Mandarin, each in its own script.

### Notes for anyone installing it

- The installer is **not code-signed**. Windows SmartScreen will call it an
  unrecognised app; choose *More info* → *Run anyway*. Every release lists the
  installer's SHA-256 so you can check the file you got is the file that was
  published (`Get-FileHash "SpaleVoice Setup 1.0.0.exe"` in PowerShell).
- **No API key is included.** You enter your own the first time you open it, and
  it is written only to your own machine. Every request is billed to your own
  account by whichever transcription service you chose.
- The app checks here for newer versions. It asks before downloading anything
  and installs only when you close it.

Private software. Please do not pass the installer on.
