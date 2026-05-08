# Missing keys (dropped during 3x6 → 3x5 conversion)

These bindings used to live on the outermost pinky column on each side. They've been removed from the keymap and need to be reassigned somewhere else (combos, layers, mod-taps, etc.).

Old position numbering refers to the 3x6 layout (positions 0-40).

## BASE layer

| Old pos | Side / row | Binding |
|---------|------------|---------|
| 0 | L pinky, row 0 (top) | `&kp ESC` |
| 11 | R pinky, row 0 (top) | `&kp BSPC` |
| 12 | L pinky, row 1 (home) | `&kp TAB` |
| 23 | R pinky, row 1 (home) | `&kp APOS` |
| 24 | L pinky, row 2 (bottom) | `&mo 5`  *(SCROLL layer toggle)* |
| 35 | R pinky, row 2 (bottom) | `&mo 5`  *(SCROLL layer toggle)* |

⚠️ The SCROLL layer (layer 5) is now **unreachable** until `&mo 5` (or `&to 5` / a combo) is placed somewhere.

## NAV layer

| Old pos | Binding |
|---------|---------|
| 0 | `&trans` |
| 11 | `&kp F1` |
| 12 | `&trans` |
| 23 | `&kp F10` |
| 24 | `&trans` |
| 35 | `&kp F20` |

## SYMNUM layer

| Old pos | Binding |
|---------|---------|
| 0 | `&bt BT_CLR` |
| 11 | `&kp DEL` |
| 12 | `&studio_unlock` |
| 23 | `&kp GRAVE` |
| 24 | `&trans` |
| 35 | `&kp TILDE` |

## FUN layer

| Old pos | Binding |
|---------|---------|
| 0 | `&trans` |
| 11 | `&bt BT_CLR` |
| 12 | `&trans` |
| 23 | `&kp LALT` |
| 24 | `&trans` |
| 35 | `&to 0` |

## AUTO-MOUSE / SCROLL layers

All dropped positions on these layers were `&trans` — nothing to relocate.

## Notable bindings worth rehoming

`ESC`, `BSPC`, `TAB`, `APOS`, `&mo 5` (×2), `studio_unlock`, `&bt BT_CLR`, `&to 0`, `GRAVE`, `TILDE`, `DEL`.

The rest (`F1`/`F10`/`F20`, `LALT`, `&trans`) are easy to discard or duplicate elsewhere.
