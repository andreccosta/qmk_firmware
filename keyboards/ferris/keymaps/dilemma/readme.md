# Ferris sweep

Dillema inspired layout

## Flashing

```
qmk compile -kb ferris/sweep -km dilemma
qmk flash -kb ferris/sweep -km dilemma -bl avrdude-split-left
qmk flash -kb ferris/sweep -km dilemma -bl avrdude-split-right
```
