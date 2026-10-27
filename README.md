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

To make quizzes for free, pick **On this computer** when GoEureka asks, then click **Install the AI**. That one button downloads everything once: [Ollama](https://ollama.com), a free AI engine, from its official release, and the model suggested for your computer (Balanced is 7.6 GB; with the engine about 7.8 GB on a Mac and 9.2 GB on Windows). GoEureka shows how long is left, checks the files, and starts and stops the engine by itself. If Ollama is already installed, GoEureka uses that one. **Choose another model** shows the smaller and bigger models.

No account and no key are needed, and your files never leave your computer.

Your files and results stay in `Documents/GoEureka` on your computer.

GoEureka is free and non-commercial, made by NoesisDev. By using it you agree to the [Terms of use](https://goeureka-omega.vercel.app/terms); see also the [Privacy policy](https://goeureka-omega.vercel.app/privacy).

This repository only holds the installers. Questions or problems: write to [noesis.devs@gmail.com](mailto:noesis.devs@gmail.com) or open an issue here.
