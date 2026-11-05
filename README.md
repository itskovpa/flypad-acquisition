# FlyPad Acquisition

Software for the **FlyPad** capacitive feeding monitor for *Drosophila*: record, review and analyse
feeding at sip resolution, with optional OptoPad closed-loop stimulation, video and live fly tracking.

## Download
**[Latest release](https://github.com/itskovpa/flypad-acquisition/releases/latest)**:
`FlyPad_Acquisition_Setup_<version>_x64.exe` (Windows 10/11, 64-bit).

Run it, then start *FlyPad Acquisition* from the Start menu. "Install for me only" works without
administrator rights. The user manual, quick start and metrics reference (PDF) are attached to each
release and installed with the app (Start menu).

## What it does
- **Acquire**: live traces of all 96 channels, recording in the FlyPad (Bonsai-compatible) format,
  per-condition labels and foods.
- **OptoPad**: closed-loop and open-loop optogenetic stimulation, with catch trials.
- **Video**: USB3 / GigE Vision and webcam-type cameras, synchronised with the FlyPad recording;
  live fly tracking.
- **Review and Analyze**: sips, activity bouts, feeding bursts, preference, time courses, statistics,
  Excel export; behaviour analysis combining tracking and feeding.
- **Tools**: FlyPad firmware update (Atmel-ICE), read-only remote support.

## Support
Questions, problems or feature requests: open an
[issue](https://github.com/itskovpa/flypad-acquisition/issues) or contact Pavel Itskov.
For a problem report, the app's *Tools > Remote support* lets us see its status and log
(read-only, with an access code you give us).

## Licence
[PolyForm Noncommercial 1.0.0](LICENSE): free for noncommercial use, including research at
universities and other noncommercial organisations. Commercial use needs a licence from Pavel Itskov.

Required Notice: Copyright (c) 2026 itskovpa

The installer includes third-party components (ffmpeg, avrdude, Qt and others) under their own
licences, which are in the installation folder (`_internal`).
