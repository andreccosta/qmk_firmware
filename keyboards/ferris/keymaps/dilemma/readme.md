# Ferris sweep

Dilemma inspired layout

## Flashing

```sh
qmk compile -kb ferris/sweep -km dilemma
qmk flash -kb ferris/sweep -km dilemma -bl avrdude-split-left
qmk flash -kb ferris/sweep -km dilemma -bl avrdude-split-right
```
