# ReadListen for Mac

ReadListen for Mac reads your books aloud on the Mac, and is the free companion
to the ReadListen phone apps.

- **Read tab:** add EPUB, PDF and text files (Open, or drag them onto the
  window) and listen with 40 Kokoro voices and 25 newer Phonon voices, each
  word highlighted as it is read.
- **Phones tab:** pair your phone and your Mac prepares its audio, faster and
  easier on the phone's battery, and keeps your place in each book in sync.
- Dark or Light, from the top right of the window.

Everything stays on your phone and your own computer. The Mac app sends
nothing to any outside service.

This repository only hosts the Mac installer. It contains no source code.

## Install

You need a Mac with Apple silicon (M1 or newer) running macOS 14 Sonoma or
newer, and about 1.5 GB of free space. The download is about 560 MB, because
the voices are built in.

1. Open the
   [latest release](https://github.com/jobfinderbyivan/readlisten-mac/releases/latest)
   and download the file ending in `.dmg`.
2. Open it and drag **ReadListen** into **Applications**.
3. Open ReadListen from Applications. It is signed and notarized by Apple, so
   it opens like any other app.
4. On your phone, open ReadListen and connect to your computer. Type the short
   code shown in the Mac window.

The `.sha256` file beside each download is its checksum, if you want to check
it.

## Away from home

At home the phone finds the Mac on your Wi-Fi by itself. If your router allows
it, the phone can also reach the Mac when you are away; the Mac window says
whether that works on your network. The Mac has to be on and awake.

## License

All rights reserved. See [LICENSE](LICENSE). ReadListen for Mac includes
open-source components under their own licences; their notices are inside the
app.
