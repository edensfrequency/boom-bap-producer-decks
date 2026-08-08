![banner-image.png](../assets/banner-image.png)

<hr>

# Install

Windows only for now (macOS is a later phase).

## Download

Grab the latest build from the
[Releases page](https://github.com/edensfrequency/boom-bap-producer-decks/releases) —
`Boom Bap Producer Decks.vst3.zip` for your DAW, or
`Boom Bap Producer Decks-Standalone.zip` to run it with no DAW at all.

## As a VST3 plugin (inside a DAW)

1. Unzip, then copy the whole `Boom Bap Producer Decks.vst3` folder into
   your system's VST3 folder: `C:\Program Files\Common Files\VST3\`.
2. Rescan plugins in your DAW.
3. If you already had a previous version loaded in an open project,
   remove and re-add the plugin instance (or restart the DAW).

## As a standalone app (no DAW needed)

Unzip and run `Boom Bap Producer Decks.exe` directly, no install step.
On first launch, open its audio settings to pick an output device.

## Building from source instead

See `internal-docs/developer-docs/BUILD.md` if you have the source
repo.

## Troubleshooting

- **Old version still showing**: the plugin binary can be locked by a
  running DAW that already has it loaded. Close the DAW before replacing
  the file, then reopen.
