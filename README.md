# Math Review

VJ's cumulative math-review practice app. Every round is a fresh 25-question
test weighted toward the newest material:

- **Shaded regions ×7** — whole shape minus a cut-out (triangle notch, circle
  in a triangle, trapezoid in a circle, parallelogram in a square, V-notch
  banner, ring, circle punched from a rectangle), each drawn as a
  worksheet-style figure with dimension arrows
- **Circumference word problems ×6** — C from radius/diameter, fencing cost,
  Ferris-wheel distance, revolutions to cover a distance, halfway-around-the-
  pond, and working backwards from C to d
- **Compound areas ×3** — stadium, house, L-shape, cone, parallelogram,
  trapezoid, rocket
- **Probability ×3** — fraction answers (bags, spinners, number cubes,
  complements, with/without replacement)
- **Inequalities ×3** — one-step, two-step, and the negative-flip trap
- **Integers & equations ×3** — signed arithmetic and two-step equations

Missed questions get a full step-by-step breakdown (figures re-render with
each part highlighted). π = 3.14 throughout. Scores sync across devices via
Cloudflare Workers KV (`functions/api/scores.js`, binding `SCORES`).

Live: https://vj-math-review.pages.dev
