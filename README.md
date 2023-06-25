# Koamuse Finale Templates

These are my versions of Finale templates that are good starting points.

- Jazz Band Portrait
- Lead Sheet (Legacy) - Uses the Broadway Legacy font
- Lead Sheet - Uses the new Broadway font included in Finale v27

## Workflows

### Jazz Band Portrait

tbd

### Lead Sheet (Legacy)

1. Enter the melody, chord symbols, and everything else into the concert part
2. Copy the concert part to the other 4 staves
3. If there is an initial tempo specified, update that expression: Offset from Alignment Point: 0 / 0.5
4. Document > Manage Parts...: Generate Parts

Then, you can move the parts around and such.

_CAVEAT_ When you first get in there, the copyright have my information. Best to update that in your template!

### Lead Sheet

This one is not as up to date as Lead Sheet (Legacy) but I imagine most of the things to do are the same.

## My Formatting

I've formatted all of this on the Lead Sheet (Legacy) but I'm not sure if it is done on the other templates. I've especially liked how the Page Edge positioning works.

Finale's default is to do positioning based on the page margins. This means if you adjust them to move the music down, everything else moves too. But your page numbers should always be in the same place yeah? Same with Copyright and such? So, make it so!

### Score Margins

_Only non-defaults shown_
First Staff System margin / top: 1.2
Left and Right Page / top: 0.75
Left Page / right: 0.75
Right Page / left: 0.75

### Part Margins

First Staff System margin / top: 1.2
Left and Right Page / top: 0.75
Left Page / right: 0.5 (single page)
Left Page / right: 0.625 (multi-page)
Right Page / left: 0.625

### Text (H/V)

_Use from Page Edge for absolute positioning_
Title: 0 / -0.35
Title (page 2 onwards): 0 / -0.35
Score/Part Name: 0.5 / -0.5
Composer: -0.5 / -0.5
Arranger: -0.5 / -0.8 (+0.3)
Initial Tempo: 0.5 / -0.75
Page Number (page 2 onwards): 0.5 / -0.5
Page Number (right page positioning): -0.5 / -0.5
Footer: 0 / 0.375

### Document Options

- Beams
  - Beam four eight notes together in common time: **off**
- Music Spacing
  - Avoid Collision Of
    - Articulations: **on** (trying it)
    - Chords: **on** (trying it)
- Repeats
  - Repeat Endings…
    - Height of Bracket: **0.7** --> 0.70139
    - Horizontal: **0.03** --> 0.03125

For Repeat values, entering the value specified, results in the value after the -->
i.e. enter 0.7 and you get 0.70139.

### Expressions

- Tempo Marks > Edit Categories… > Score List > Edit…
  - Under Score, Top Staff is checked and that's good
  - Under Part, click _Check All Staves_

This way tempo indications, like at the top of the tune, display on every part.
