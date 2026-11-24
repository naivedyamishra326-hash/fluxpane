# FluxPane

Portable Windows x64 app that opens ChatGPT in a Chromium window, with always-on-top support, hide/show controls, and screenshot tools.

## Download

[Download FluxPane 1.0.4 for Windows x64](https://github.com/naivedyamishra326-hash/fluxpane/releases/download/v1.0.4/fluxpane-portable-v1.0.4.zip)

This repository distributes the portable app. The complete application is attached to the [v1.0.4 release](https://github.com/naivedyamishra326-hash/fluxpane/releases/tag/v1.0.4).

## Run

1. Download and extract the entire ZIP into a folder.
2. Run `fluxpane.exe`. Keep all bundled DLLs, Chromium files, and the `locales` folder beside it.
3. Optionally run `install-cli.cmd` to add the CLI folder to your user PATH. Open a new Command Prompt and run `fluxpane`. Run `uninstall-cli.cmd` to remove it.

## Shortcuts

| Shortcut | Action |
| --- | --- |
| Alt + backtick | Hide or show the window |
| Ctrl + Left Alt + S | Take a screenshot and copy it to the clipboard |
| Ctrl + Left Alt + Q | Close the window |

Use the Hide and Unhide buttons to restore the same page and draft. Drag screenshot thumbnails into the page or paste the copied image.

The app reuses the Ultralay Desktop profile at `%LOCALAPPDATA%\UltralayDesktop\cef-cache`. See the README inside the ZIP for startup options and additional details.

## Third-party notices

The ZIP includes `CEF-LICENSE.txt` and `CEF-CREDITS.html` for the bundled Chromium Embedded Framework components.
