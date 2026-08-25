# MOMNTUM Exercise SVG Library

Each exercise animation is a self-contained SVG file.

Current benchmark assets:
- `push-up.svg`
- `band-row.svg`

## Rules
- Keep `viewBox="0 0 320 130"` for consistent framing.
- Reuse MOMNTUM classes such as `.exerciseMotionFigure`, `.exerciseMotionHead`, and `.exerciseMotionFloor`.
- Use SVG `<animate>` keyframes for the movement itself.
- Do not embed fixed theme colours where avoidable; the app injects the SVG inline so parent CSS can supply `currentColor` and `var(--accent)`.
- Add the filename to `EXERCISE_SVG_ASSETS` in `index.html` when a new exercise is approved.
- No generic fallback animations: an exercise without an approved asset intentionally shows no illustration.

## Lower-body batch
- bodyweight-squat.svg
- reverse-lunge.svg
- lateral-lunge.svg
- glute-bridge.svg
- calf-raise.svg
