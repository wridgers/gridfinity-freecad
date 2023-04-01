# gridfinity-freecad

My attempt at parameterised gridfinity bins, with no addon dependencies.

## Instructions

- Copy the base file that most suits your needs
  - `2d` if you need a `2x2` bin or larger
  - `1d` for `1xN`
  - `unit` for `1x1`
- Update the the `Variables` spreadsheet
- Refresh (F5)

This should give you a good base from which to build your custom bin.

## Limitations

- Due to the use of transformations, setting `X=1` or `Y=1` will result in `"Pattern length too small"`. This is why
  the `2d`/`1d`/`unit` variants exist.
- No magnet/screw hole versions.
- All versions have a stacking lip.
- I've not printed non-standard grid sizes, but it does appear to work!

# Acknowledgement

[Zack Freedman](https://www.youtube.com/c/ZackFreedman) for creating Gridfinity!
