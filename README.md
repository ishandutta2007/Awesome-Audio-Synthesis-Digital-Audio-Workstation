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
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Digital Audio Workstation (DAW) and audio synthesis software market is estimated at approximately $4.0B–$4.7B as of 2025–2026, expanding at a CAGR of ~7–9% toward over $6B by 2031. The sector exhibits moderate-to-high fragmentation rather than a single winner-take-all monopoly: while legacy desktop incumbents (such as Apple Logic Pro, Avid Pro Tools, and Ableton Live) dominate pro studios and enterprise giants like Spotify back consumer platforms, agile independent players and specialized browser-based freemium ecosystems (BandLab, Amped Studio, Audiotool) thrive across educational, social creator, and collaborative niches.

## SaaS Products

| Product | Company Size (Valuation / Revenue) | Pricing | Free Tier Limits | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Soundtrap](https://www.soundtrap.com/)** | **~$120B market cap** *(Parent: Spotify, NYSE: SPOT)* | **$9.59/mo** (Sound Starter, billed annually at $115.08/yr) or $11.99 billed monthly; Music Production at $13.59/mo ($16.99/mo monthly) | **Free Forever Tier**: MP3/OGG exports only (no WAV export), 7,760+ loops, 450+ instruments, 20+ vocal presets, no stem splitter/auto-tune. Paid plans include a **30-day free trial** with full feature access requiring credit card. | Browser collaborative DAW with Spotify integration, classroom education support, and cloud vocal tuning. |
| **[BandLab](https://www.bandlab.com/)** | **$425M valuation** *(Series B1 post-money; ~$10M–$48M est. annual revenue)* | **$14.99/mo** or **$99.00/yr** (BandLab Pro Membership); $199.00/yr (BandLab Max) | **Free Forever Tier**: 16 tracks per project max, 20 samples/mo, 5 beats/wk, 436+ instruments, no major streaming service distribution without paid membership. | Social music creation platform with cloud mixdown, built-in stem splitter, SongStarter AI, and 50 collaborators per project. |
| **[Audiotool](https://www.audiotool.com/)** | **~$2.6M total funding** *(Early-stage venture-backed by Unlock Venture Partners)* | **Free / $0/mo** (No paid subscription tiers; 100% free community platform) | **Free Forever Tier (Full Access)**: No track caps, no project length limits, 37 built-in synths/effects, modular cable routing, and real-time multiplayer DAW collaboration with zero paywalls. | Cloud-native modular routing synthesizer and DAW with Web Audio/VST3 bridge and active online musician community. |
| **[Amped Studio](https://ampedstudio.com/)** | **Bootstrapped / Private** *(LettoPro SA, Montreux, Switzerland; ~$1M–$3M est. ARR)* | **$5.99/mo** (billed annually at $69.99/yr) or $6.99 billed monthly (Premium); $9.99/mo ($119.99/yr) for Pro | **Free Forever Tier**: Max 16 tracks, MP3-only export (no WAV/project export), 0GB cloud storage, 5 virtual instruments & 10 FX, no external VST3 support, ad-supported. Paid plans offer a **3-day free trial** with full access. | Online DAW featuring remote VST3 plugin hosting via desktop bridge, AI stem splitter, and sample sequencer. |
| **[AudioSauna](https://chromewebstore.google.com/detail/audiosauna/lkgfemnodkdnenmfkblebnkjpckkjcae)** | **Micro-entity / Inactive** *(Naive Solutions, Helsinki, Finland)* | **Free / $0/mo** (Discontinued legacy web app) | **Free Forever Tier**: Browser session only, 2 synths (analog + 4-op FM Yamaha DX-21 style), 8-track stereo sampler with ping-pong looping, local file saving. *(Note: unmaintained since February 2014).* | Classic web audio synthesizer and sampler with Chrome Web Store deployment; historical precursor to modern web DAWs. |

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
