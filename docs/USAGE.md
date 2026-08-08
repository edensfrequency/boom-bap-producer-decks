![banner-image.png](../assets/banner-image.png)

<hr>

# Usage

Two independent decks, a mixer, and a bank of sample pads per deck. The
banner shows the installed version number under "PRODUCER DECKS".

## Deck A / Deck B

Each deck is independent — its own loaded sample, its own platter.

- **Load...** or **drag an audio file** onto a deck to load a sample.
- **Click-drag the platter** to scratch: dragging clockwise plays
  forward, counter-clockwise reverses, and the pitch follows how fast
  you drag. Release to resume normal playback from wherever the scratch
  left off.
- **Play / Pause** — normal playback at the current pitch.
- **Cue** — stops and jumps back to the start.
- **Pitch** fader — 0.5x-2.0x playback speed when not scratching. This
  is a simple resample-based change, so it affects pitch too — it's not
  true independent time-stretching yet.
- **Volume** fader — this deck's output level.
- **BPM / Key** — automatically detected when you load a sample (shows
  `--` for either if nothing could be estimated). **Sync** sets this
  deck's Pitch so its detected BPM matches your host's current tempo.

## Deck mixer strip (High / Mid / Low / Filter / Reverb)

Five knobs under each deck's Pitch/Volume faders:

- **High / Mid / Low** — 3-band EQ, -24dB to +6dB each, double-click a
  knob to reset it to flat (0dB, straight up). This is a DJ-style "kill"
  EQ with fixed crossover points, not a parametric one.
- **Filter** — one knob, centre is bypass. Turn it clockwise for a
  low-pass sweep (cuts highs, closing in toward 200Hz), or
  counter-clockwise for a high-pass sweep (cuts lows, opening up toward
  3kHz).
- **Reverb** — a send: turning it up layers reverb on top of the dry
  signal without ever losing the dry signal underneath.

## Scratch-Strip FX

The centre column between the two decks, above the crossfader: a
dropdown to pick one effect (**Echo**, **Delay**, **Phaser**, **Reverb**,
**Flanger**, or **Filter**) and a **Mix** knob for how much of it blends
in. This applies to the whole mix (both decks, after the crossfader),
not to a single deck. Mix at 0 is fully dry/bypassed.

## Crossfader

Center strip between the two decks. Full left = only Deck A audible,
full right = only Deck B, center = both at equal power.

## Pads

Each deck has its own bank of 16 one-shot trigger pads. Click the
**Pads** button in a deck's header to switch that deck's platter view
over to its pad grid (click **Platter** to switch back — the rest of
that deck's controls, EQ, and FX stay active either way).

- **Drag an audio file onto any pad** to load a sample onto just that
  pad.
- **Click a loaded pad** to trigger it — it plays once, start to finish.
- Clicking an already-playing pad **retriggers it from the start**
  (cutting off whatever was still playing), rather than needing a
  separate stop step.
- This is "plain trigger" mode: no per-pad volume, pitch, or envelope
  yet, and pads aren't MIDI-mapped in this build — click-to-trigger only.

## What's not here yet

Hot Cues / Slicer / Sampler pad-modes, saving your settings between
sessions (presets), true independent time-stretch, and stem separation
are all on the roadmap but not in this build.
