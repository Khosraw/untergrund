# Untergrund

A 1-bit music visualizer for hard techno and schranz, at
[khosraw.com/untergrund](https://khosraw.com/untergrund).

The music writes into Conway's Game of Life. Each track is analysed ahead of time (beat, kick,
sections and the instruments it is made of), and that analysis drives the automaton:

- **Kicks** stamp plain shapes that Life breaks apart.
- **New sounds and hits** seed cells in the part of the screen their frequencies own.
- **Instruments that stand out** (a lead, a vocal, a riff that comes in mid-drop) each get a
  lane that comes alive while they play.
- **Sections** set the look: builds tighten and speed up, drops land with a flash, breaks open up.
- **Pace** sets the speed. The automaton has momentum and speeds up with the music.

Black and white only.

## Keys

`space` play/pause · `← →` seek · `N` `P` next/previous · `F` fullscreen · `S` strobe ·
`H` HUD · `D` feature view · `T` tap along to fix sync · `M` lock a mode · `Esc` track list

The tracks belong to their artists. This repo holds only the static build.
