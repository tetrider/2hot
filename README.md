# 2HOT

Makes crouch, walk, sprint, lean, and ADS work as hold, toggle, or hold+toggle — the way STALKER 2 handles it. Beyond that, adds a reliable prone system, and a collection of quality-of-life fixes.

A set of engine workarounds — my attempt to make Anomaly feel more comfortable to play. Based on and inspired by Hold or Toggle by duddy.

## Stance systems

- **Progressive (default)** — tap crouch for crouch, hold crouch for prone. Most natural feel. Prone key works as backup.
- **Fluid Stance** — crouch and walk keys switch between modes cleanly: pressing crouch while walking switches to crouch rather than standing up. No accidental prone from crouch+walk — use the prone key.
- **Vanilla Prone** — adds only a dedicated prone key. Crouch and walk behave exactly like vanilla STALKER.

## Rapid Fire *(experimental)*

Holding fire or ADS skips the weapon raise animation so you can shoot or aim almost instantly. If you press before the weapon is ready, the game no longer ignores it — the action executes as soon as the weapon allows. Extends Fluid Aim by Skieppy with additional behaviors and Hold or Toggle compatibility.

- **Rapid Fire** — hold fire to skip the raise animation and shoot almost instantly. Works with single, burst, and auto fire modes. If you press fire too early, the intent is queued and executes as soon as the weapon is ready. Configurable delay before the raise animation is cancelled.
- **ADS** — same behavior: holding ADS skips the raise animation. In Toggle or Hold+Toggle mode, tapping ADS early opens a short window so the aim activates as soon as the weapon is ready.
- **Reload cancel** — optionally interrupt magazine or pump-action reloads by holding fire or ADS mid-reload. Configurable delay for each type.

## QoL Features

- **Alternative Sprint Cancel** — sprint only cancels actions when moving forward. Preserves your stance when stationary, and keeps LSHIFT free for modifier binds.
- **Opposite Lean Cancel** — in Toggle/Hold+Toggle mode, pressing the opposite lean key cancels current lean instead of switching sides. In Hold+Toggle mode, a held lean switches direction instead of canceling.
- **Inventory on Release** — tap to open inventory, hold the key for other actions (e.g. Quick Action Wheel).
- **Block Crouch in Inventory** — prevents accidental crouching when holding LCTRL to view full item stats in inventory.
- **PDA Mode** — four options: *Default* (vanilla behavior), *On Release* (tap to toggle PDA), *Hold to Zoom* (hold opens PDA with zoom), *On Release + Zoom* (tap opens with auto-zoom).
- **Restore Hands After PDA** — automatically restores your weapon and detector when closing the PDA with the PDA key or Escape. Requires PDA Mode to be active.
- **Prevent Weapon with Detector** — when switching from a two-handed weapon to a detector, goes to empty hands first to avoid animation issues.
- **QAW: Ignore Modifiers on Hold** — long-pressing the QAW key works even while holding modifier keys, so you can open the wheel while sprinting.
- **QAW: Close with Reload Key** — reload key closes QAW when it's open. Works well with Key Wrapper tap/hold binds or One Key Weapon Control.
- **Stance Vignette** — screen edges darken based on stance: subtle when standing, light vignette when crouching, stronger when prone. Configurable intensity. Requires DXML.
- **FDDA Integration** — if FDDA Redone is installed, lean and ADS are automatically canceled when FDDA animations start, and lean keys are added to FDDA's whitelist.
- **Auto-Walk** — toggle auto-walk using a modifier key combination. Choose activation style (press, double-tap, or hold) and which modifier key to use. Cancels when you manually press forward or back.

## Incompatible mods

Do not use alongside:

- Sprint Cancel, Aim and Lean Toggle
- AutoWalk for Anomaly
- Hold or Toggle (original by duddy)
- Lower Weapon Sprint

## Installation

Add via Mod Organizer 2 (Ctrl+M) near the end.
