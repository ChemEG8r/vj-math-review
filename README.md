# Math Review

VJ's math review practice app — all geometry, in the style of
[Area Arena](https://area-arena.pages.dev), weighted toward the newest
material. Every round is a fresh 12-question test:

- **Shaded regions ×4** — whole shape minus a cut-out (rect − triangle
  notch, triangle − circle, circle − trapezoid with the diameter trap,
  square − parallelogram, V-notch banner, ring, rect − circle hole), each
  drawn as a worksheet-style figure with dimension arrows
- **Circumference word problems ×4** — C from radius/diameter, fencing
  cost, Ferris-wheel distance, revolutions to cover a distance,
  halfway-around-the-pond, and working backwards from C to d
- **Compound areas ×3** — stadium, house, L-shape, cone, parallelogram,
  trapezoid, rocket (from the previous test)
- **Rule checks ×1** — quick multiple choice on the formulas and traps

Missed questions get a full step-by-step breakdown (figures re-render with
each part highlighted). π = 3.14 throughout. Scores sync across devices via
Cloudflare Workers KV (`functions/api/scores.js`, binding `SCORES`).

Live: https://vj-math-review.pages.dev
