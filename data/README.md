# Data

## heatsink.txt

Place the CFD dataset file `heatsink.txt` in this directory before running the notebooks.

The file should be whitespace-delimited with **four columns** and no header:

```
G1    G2    TR    PD
```

| Column | Description | Units |
|--------|-------------|-------|
| G1 | Channel length/width ratio | — |
| G2 | Bend spacing ratio | — |
| TR | Thermal resistance | K/W |
| PD | Pressure drop | Pa |

The dataset contains 30 CFD-computed design points from Al-Neama et al.'s serpentine microchannel heat sink study, spanning the design space G1, G2 ∈ [0.4, 1.0].

## Source

Al-Neama, A.F. (2018). *Serpentine minichannel liquid-cooled heat sinks for electronics cooling applications*. University of Leeds.
