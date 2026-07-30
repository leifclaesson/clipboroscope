# Clipboroscope

**Clipboard Observation Instrument.** Do not tap on the glass.

CLIPBOROSCOPE.EXE is a DPI-aware clipboard viewer for Windows -- see exactly
what is on your clipboard, in every format at once, razor-sharp on any
display. A modern replacement for the old Windows `clipbrd.exe`.

### [Download Clipboroscope](https://leifclaesson.github.io/clipboroscope/)

Or grab the installer straight from
[the latest release](https://github.com/leifclaesson/clipboroscope/releases/latest).
Windows 10 and 11, 64-bit, signed installer.

## What it does

- Every format on the clipboard at once -- text, Unicode, images, HTML, rich
  text, file drops, audio, and raw bytes -- picked from a slide-out drawer
- Renders what it understands: GDI bitmaps, EMF/WMF metafiles, formatted RTF,
  full WAV waveforms with sinc-reconstructed zoom
- Per-format zoom, remembered separately for text-like formats and images
- Live refresh -- copy something new and it updates instantly
- OLE bookkeeping formats (`DataObject`, `Ole Private Data`) tagged as
  plumbing so they never hijack the view
- DPI-aware, and now says when a format's DPI genuinely wasn't stamped

## About this repository

This repo is the **public face**: the landing page and the releases. The
source code is not public and is not included. Clipboroscope is free to use,
for personal and commercial purposes alike, under the terms in
[LICENSE.txt](LICENSE.txt).

Please link people here rather than mirroring the installer, so nobody ends
up running a stale copy.

Part of a small family of sharp little tools. The rest are on their way.
