---
"chroma-js": patch
---

Return a single midpoint color when a scale has one class, set with `classes(1)` or two explicit class breaks. Previously these scales remained continuous and `colors(0)` returned two legend colors. `classes(0)` still restores continuous interpolation.
