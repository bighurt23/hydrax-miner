
# HydraX Miner

High-performance GPU + CPU crypto miner for NVIDIA. Free, with a transparent 1% dev fee.

**Status:** Open beta · NVIDIA only (AMD in progress) · Windows x64

Part of the HydraX mining stack — free calculators, this miner, and the Operator fleet dashboard at **[hydrax.gg](https://hydrax.gg)**.

## What it mines
- **GPU:** Ethereum Classic (Etchash) · Ravencoin (KawPow)
- **CPU:** Monero (RandomX) — runs alongside a GPU coin, so you can dual-mine on one rig

## Requirements
- NVIDIA GPU — RTX 30 / 40 / 50 series (~6 GB+ VRAM for the DAG)
- A recent NVIDIA driver
- 64-bit Windows

## Quick start
1. Download the latest release → **[Releases »](https://github.com/bighurt23/hydrax-miner/releases/latest)**
2. Unzip anywhere.
3. Open `HydraX.conf`, set your wallet address(es), pick a mode.
4. Double-click `mine-rvn.bat`, `mine-etc.bat`, or `mine-xmr.bat` — or `watchdog.bat` for auto-restart.

Run `miner.exe --help` for all options.

## Dev fee
1% — for ~36 seconds each hour the miner mines to the developer, then switches back to you. Shown as `[DEV FEE]` in the console. That's how it stays free — no hidden second fee.

## Notes
- It's a beta. The `.exe` is unsigned, so Windows SmartScreen may warn → *More info → Run anyway*. Code signing is on the roadmap.
- Antivirus sometimes false-flags miners; add an exclusion if needed.
- HydraX only connects to the pools in your config (plus the dev-fee pool). Your coins go to the wallet you set. No telemetry.

## Feedback
Open beta — we want to know how it runs on **your** card: GPU model + driver, algorithm, hashrate, and anything that broke.
📧 **admin@hydrax.gg** · or open an [Issue](https://github.com/bighurt23/hydrax-miner/issues).

---
*Built by the team at [hydrax.gg](https://hydrax.gg). NVIDIA now; AMD (OpenCL) in progress.*
