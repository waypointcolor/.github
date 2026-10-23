## Waypoint color: a material's color for every light and every viewer

Every CIELAB value comes with fine print: it holds for one light and one standard viewer. Change either, and the value
moves by a different amount for each sample. **Wpt** (pronounced "Waypoint") describes the material instead, and
**WLab** (Waypoint Lab) reshapes Wpt so that distances read like familiar ΔE color differences. With them you can ask
whether a match will hold under store lighting, whether an ink holds its color, or whether two viewers, or a camera
and a person, agree.

**Start here**

- [WLab and Wpt: Color Without the Fine Print](https://waypointcolor.github.io/wpt-onramp/WLab-Color-Without-the-Fine-Print.pdf),
  an onramp to material color equivalency for readers who know CIELAB and ΔE, with every equation in its Technical annex
- [The web page](https://waypointcolor.github.io/wpt-onramp/): the short version, a metamerism demo and a constant-hue
  experiment you can judge by eye
- [The robustness report](https://waypointcolor.github.io/wpt-onramp/WLab-robustness-report.html): paste spectra,
  pick lights, read ΔE<sub>WLab</sub>; it runs in your browser and sends nothing anywhere

**Repositories**

- [wpt-onramp](https://github.com/waypointcolor/wpt-onramp): the guide and its companion package, with GNU Octave,
  Python and spreadsheet tools that reproduce every number in it
- [wlab](https://github.com/waypointcolor/wlab): Wpt, WLab and material adjustment transforms (MATs) in TypeScript,
  with no dependencies

**The avatar** is a waypoint pin whose hue ring is the 40 Wpt training colors, idealized: the Munsell colors of Value 5
and Chroma 6 that carry the Wpt normalization, at their WLab lightness (51.58) and mean WLab chroma (24.07), in equal
steps of WLab hue. The gray at the center is the neutral of the same lightness.

Maxim W. Derhak (PhD)
