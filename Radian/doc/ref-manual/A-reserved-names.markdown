---
layout: default
title: Reference manual - Appendix: reserved names
---

# Appendix: Reserved names

<hr>
## Directives

The following directive names are reserved and implemented within
Radian: `<area>`, `<background>`, `<bars>`, `<lines>`, `<metadata>`,
`<palette>`, `<plot>`, `<plot-col>`, `<plot-data>`, `<plot-grid>`,
`<plot-options>`, `<plot-row>`, `<points>`.

<hr>
## Attributes

The following attributes names are reserved for use by Radian
directives: `axis-x`, `axis-x-label`, `axis-x2`, `axis-y`,
`axis-y-label`, `axis-y2`, `banded`, `clip-x`, `clip-y`, `cols`,
`error-for`, `fill`, `fill-opacity`, `format`, `id`, `interp`,
`label`, `legend-switches`, `marker`, `marker-size`, `name`, `range`,
`range-x`, `range-y`, `rows`, `select-x`, `select-y`, `separator`,
`src`, `stroke`, `stroke-opacity`, `stroke-switch`, `stroke-width`,
`tabs`, `title`, `type`, `units`, `x`, `x2`, `y`, `y2`, `zoom-2d`,
`zoom-x`, `zoom-y`.

Any other attribute name applied to a plotting
directive brings a name into scope for data access expression
evaluation.
