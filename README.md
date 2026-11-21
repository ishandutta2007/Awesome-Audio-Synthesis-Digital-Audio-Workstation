# Awesome-Audio-Synthesis-Digital-Audio-Workstation

## Top Audio Synthesis & Digital Audio Workstation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser-Based DAWs, Real-Time Synthesis & Self-Hosted Audio Workstations*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Audio Synthesis & Digital Audio Workstations (DAWs)**. These tools help musicians, producers, and developers create music, synthesize sound, and mix audio—covering everything from collaborative cloud DAWs with generous free tiers to open-source workstations that run entirely in your browser with no account required.

**Examples** include BandLab, Soundtrap, Audiotool, Amped Studio, AudioSauna, openDAW, GridSound, and WAM-Studio (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted browser DAWs, open-source audio synthesis engines, and community-driven music production—ideal for developers and producers seeking full control over their signal chain, local-first data storage, and no subscription lock-in. The open-source landscape is genuinely functional: **openDAW** provides a next-generation web DAW with 30+ stock plugins and a roadmap to 1.0 , **GridSound** follows the Web Audio API as a half-open-source workstation , and **WAM-Studio** is an academic open-source demonstrator with synchronized audio/MIDI recording .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[BandLab](https://www.bandlab.com/)**  
  **Completely free browser and mobile DAW with social collaboration.** **436+ virtual instruments, 250,000+ royalty-free loops and one-shots, and 50 collaborators per project** . **Free mastering** with presets by Grammy-winning engineers. **AI tools**: SongStarter (idea generator) and Splitter (stem isolation) . **No paid tier required for core music creation**—Pro/Max plans add extra stems and voice cleanup . Best for beginners and mobile-first creators wanting a zero-cost entry into music production .

- **[Soundtrap (Spotify)](https://www.soundtrap.com/)**  
  **Browser-based collaborative DAW with Spotify backing.** **Free tier: 7,760+ loops, 450+ instruments, 20+ vocal presets** . **Sound Starter: $9.59/mo** (annual); **Music Production: $15.59/mo**; **Production & Vocals: $14.79/mo** with 39,820+ loops and 1,800+ instruments . **7-day free trial** for paid plans . Best for education and indie markets needing a polished, Spotify-integrated workflow .

- **[Audiotool](https://www.audiotool.com/)**  
  Advanced collaborative browser DAW with built-in synthesizers, samplers, mixers, and effects. Positioned for real-time online music production .

- **[Amped Studio](https://ampedstudio.com/)**  
  **Full-featured browser DAW with VST3 plugin hosting via VST Remote.** **Free DAW** for recording, beats, MIDI, instruments, effects, and mixing—**no time limit, no demo restrictions** . **AI stem separation** and **AI multitrack sketch generation** built in. **Cloud project storage** accessible from any computer . Best for producers wanting desktop-DAW power in a browser with VST plugin access .

- **[AudioSauna](https://chromewebstore.google.com/detail/audiosauna/lkgfemnodkdnenmfkblebnkjpckkjcae)**  
  **Legacy browser audio workstation with virtual analog and FM synthesizers.** **100,000 users** on Chrome Web Store. **Two synths** (analog and 4-operator FM modeled on Yamaha DX-21), **advanced stereo sampler** with ping-pong looping and key range mapping . **⚠️ Last updated February 2014**—not recommended for new projects .

## Open-Source GitHub Projects

- **[openDAW](https://github.com/andremichelle/openDAW)**  
  **Next-generation web-based DAW with 30+ stock plugins and a roadmap to 1.0 in Q3 2026.** **Runs entirely in the browser** with no server roundtrip for audio. **Stock plugins include**: Vaporisateur (subtractive synth), Playfield (sample drum computer), Dattorro Reverb, Autotune, Vocoder, Maximizer, and more . **WebCLAP plugin hosting** for CLAP plugins compiled to WebAssembly. **Roadmap**: WASM Audio-Engine (Q2 2026), UI polish, testing, and **1.0 launch (Q3 2026)** . **Active community with financial supporters** . Best for developers and producers wanting a modern, actively developed open-source browser DAW with a clear path to stability .

- **[GridSound](https://github.com/gridsound/daw)**  
  **Work-in-progress free browser-based DAW following the Web Audio API.** **AGPL-3.0**, JavaScript, **1,839 stars** . **"Half open-source"**—the application is free to use at daw.gridsound.com, but some components may not be fully open . **Active development** (version 2.60.0, updated October 2026) . Best for users wanting a free browser DAW with online project saving, accepting the "work-in-progress" status .

- **[WAM-Studio](https://github.com/BrahimSD/wam-studio)**  
  **Academic open-source DAW demonstrating W3C standards (Web Audio, Web MIDI, WebAssembly, Web Components).** **Developed since 2022**, with publications at ACM Web Conference 2023 and IEEE IS2 2024 . **Features**: robust audio track recording, MIDI tracks, track regions, loop area, plugin FX chain, parameter automation, latency measurement and compensation, cloud project saving, and offline rendering . **Fork Attune** adapted for cochlear implant users . **Docker deployment** available . Best for researchers and developers wanting a standards-based, academically validated open-source DAW foundation .

- **[WAVR PRO](https://github.com/oliego-ai/WavrPro)**  
  **Full-featured browser DAW with zero install, zero account, and local-first data.** **React + Web Audio API**, **entirely client-side**—audio never leaves your machine . **Multi-track timeline** with drag-and-drop, **6-band parametric EQ per track**, **five visualizer modes** (waveform, spectrum, spectrogram, oscilloscope, VU meter), **IndexedDB session persistence**, **WAV export**, and a **VST-style plugin SDK** with zero dependencies . **Standalone single-file build** (`wavr-pro.html`) opens in any browser with no server . Best for developers wanting a hackable, local-first browser DAW with an extensible plugin architecture .

### Additional Strong Open-Source Options

- **Community Web Audio DAWs** and **Web Audio Module (WAM) plugins** for building custom synthesis and effects chains.
- **Tone.js** and **Web Audio API wrappers** as foundational libraries for browser-based synthesis and sequencing.
- **SuperCollider** and **Csound** for algorithmic composition and real-time synthesis outside the browser DAW paradigm.

**Frameworks for building custom systems**: Combine **openDAW** for a modern browser DAW foundation with 30+ plugins, **WAVR PRO** for a local-first, hackable React component you can embed, and **Tone.js** for custom synthesis logic. For academic or standards-based work, **WAM-Studio** provides a validated foundation .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Browser DAWs and audio synthesis tools can produce high sound pressure levels; protect your hearing and use appropriate monitoring levels. Browser-based audio requires low-latency configuration for real-time performance.
- **Tool choice depends on whether you need a free SaaS workflow, a collaborative platform, or full local control.** **BandLab is the most generous free DAW** with no paid tier required for core creation, 250,000+ loops, and 50 collaborators . **Soundtrap offers a solid free tier** (7,760+ loops) but paid plans start at $9.59/mo for more instruments . **Amped Studio uniquely hosts VST3 plugins in the browser** via VST Remote . **AudioSauna is abandoned**—last updated February 2014, not recommended for new projects . **Open-source options have different maturity levels**: openDAW is the most actively developed with a 1.0 roadmap, GridSound is "half open-source" and work-in-progress, WAM-Studio is academically validated but research-oriented, and WAVR PRO is local-first and hackable but newer . Validate whether you need a polished SaaS (BandLab, Soundtrap) or a self-hosted/hackable workstation (openDAW, WAVR PRO) before committing.

---

**Made for musicians, audio developers, and producers building browser-based music infrastructure.**  
Let's make audio synthesis and digital audio workstations more open, local-first, and artist-controlled.
