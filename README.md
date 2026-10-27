# GoEureka downloads

GoEureka turns your own lecture notes, PDFs, slides and photos into quizzes, with an explanation from your own material for every answer.

- **Website:** https://goeureka-omega.vercel.app (uses your own Gemini, OpenAI or Claude key)
- **Desktop app:** free, works with a model on your own computer, no key needed. Download it from the [latest release](../../releases/latest).

## Install

| Computer | File |
|---|---|
| Windows 10 or 11 | `GoEureka-<version>-windows-setup.exe` |
| Mac with Apple silicon (M1 and newer) | `GoEureka-<version>-mac-arm64.dmg` |
| Mac with Intel | `GoEureka-<version>-mac-x64.dmg` |

The app is not signed by Apple or Microsoft yet, so the first start needs one extra step:

- **Windows:** if SmartScreen says "Windows protected your PC", click **More info**, then **Run anyway**.
- **Mac:** open the .dmg and drag GoEureka to Applications. Open it once; when macOS refuses, go to **System Settings > Privacy & Security** and click **Open Anyway**.

To make quizzes for free, install the free [Ollama](https://ollama.com) app when GoEureka asks; GoEureka then downloads a model that fits your computer.

Your files and results stay in `Documents/GoEureka` on your computer.

This repository only holds the installers. Questions or problems: open an issue here.
