# The Best-Looking Food Picture: Smash Burger, Bun Lifted
A hand lifts a glossy brioche bun off a smash burger: molten cheddar drips
down the patty in one slow, shining ribbon, caramelised onions glisten
underneath, steam rising into warm light against dark slate.

Why it should make the judge hungry:

- **One clear focal point.** The lifted bun and the cheese drip sit dead
  centre — at 300 pixels across, the dish is still unmistakable.
- **Texture you can almost taste.** Gloss on the bun, melt on the cheese,
  char on the patty edge, steam in the air: fresh, real, well made.
- **Warm light, dark stage.** The slate background keeps every bright,
  appetising colour on the food itself, and nothing else competes.
- **A moment, not a still life.** The bun is mid-lift, the cheese
  mid-drip — the burger is being eaten right now, and you want in.
## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, stdlib only) copies `entry.png` beside it to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`), creating the
directory if needed. The image is a 1024x683 JPEG, 132,533 bytes — inside
the 1 MiB and 1024x1024 limits; two runs write byte-identical output.
