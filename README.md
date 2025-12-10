# Mason's Fork of Bespoke Synth

This branch contains my personal modifications to BespokeSynth. This is for my own use only, so I do not guarantee that my changes won't break things, or that my changes would even be useful to anyone else.

The original project is here: https://github.com/BespokeSynth/BespokeSynth

## Features Added/Changed:
- NoteCanvas shows microtonal note names for certain scales (depending on PPO), 
instead of always showing 12-TET midi note names mapped incorrectly. Currently supports these tunings (defaults to 12 if a tuning isn't supported):
  - 12-EDO
  - 16-EDO
  - 17-EDO
  - 19-EDO
  - 31-EDO

## Features I plan on adding/changing/experimenting with:
- Microtonal Features:
  - Microtonal chord generator
  - Change scale select to show certain Microtonal scales/key signatures depening on PPO (maybe).
  - Make color-coded intervals work with microtonal tunings.
  - Option to show note numbers instead of names (for high EDO).
  - Some way to surpass the 128 note midi limit. Might have to break midi stuff for this.
- Sequencers:
  - Some kind of sequencer using Magic Squares.
- Easier way to create Synth modules without so much boilerplate
- More 'algorithmic' synths like KarplusStrong. Ideas:
  - Waveguide synths
    - Single Reed / Clarinet-like
    - Bowed/sustained strings instead of plucks
  - Maybe some other physical modeling stuff.
- Changes to NoteCanvas:
  - Highlight entire pitch row on hover.
  - Show note name of the current cell the mouse is hovering on.
  - Keybinds for moving things up/down an octave should respect PPO instead of being hardcoded to 12 steps.
  - Remove annoying help dialog, since it blocks view of things sometimes.
