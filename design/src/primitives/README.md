# primitives/

The Impande primitives and their spec sheets. Self-contained — every import here
resolves inside this folder.

Box, Stack and Grid are the layout primitives; they share one sheet (`Layout Sheet.dc.html`)
because the thing being documented is the spacing scale, not three components.

The sheets do not render StackFolio's Header or Footer. That is deliberate: they are system
documentation, and pulling in product chrome would mean keeping copies of it here that drift
from `screens/`.
