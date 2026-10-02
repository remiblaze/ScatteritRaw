# Scatterit Raw: one-knob glitch slicer

![Scatterit Raw free one-knob glitch slicer UI](https://raw.githubusercontent.com/RemiBlaze/ScatteritRaw/main/scatteritraw-ui-screenshot.png)

**One knob. Your beats start glitching themselves.**

Scatterit Raw is the free, one-knob version of **Scatterit**, a transient-triggered glitch slicer for tech house, house, and electronic music. Drop it on drums, loops, or vocals, turn the knob, and let the dice decide.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/ScatteritRaw/releases/latest) and pick your platform.

**macOS**
1. Download **`ScatteritRaw_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. Scatterit Raw appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`ScatteritRaw_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. Scatterit Raw appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
One big **SCATTER** knob. Scatterit listens for transients (drum hits, onsets) and, on each one, rolls the dice: play the slice forward, reversed, pitched, or stuttered. Low settings give occasional hiccups; high settings tip into full chaos. At zero it stays clean and passes your signal through.

Under the hood it uses spectral-flux onset detection, a multi-band trigger, and short raised-cosine crossfades between slices to keep the glitches click-free. The scatter pattern is seeded so a saved project reloads to the exact same performance.

The full **Scatterit** adds per-effect probability, one-shot sample replacement and folder cycling, sidechain triggering, scale-locked pitch, stutter and slice-length control, bitcrush, freeze, and Delta listen.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/ScatteritRaw/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/scatterit-raw/](https://remiblaze.com/plugins/scatterit-raw/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
