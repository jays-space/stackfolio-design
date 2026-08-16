# StackFolio design

Published design artifacts for StackFolio, built on the Impande system.

## Layout

    design/
      index.html          this ledger
      <name>/index.html   one self-contained page per design
      src/                the .dc.html sources these were built from

Each `index.html` is a single file with fonts, styles and runtime inlined. It opens in any
browser, offline, with nothing to install. That is why they are around 1.4 MB each.

## Publishing

GitHub Pages, serving from the branch root. The design ledger is at `/design/`.

## Changing a design

The bundles are generated output. Edit the matching file in `src/`, rebuild, and commit the
source and the bundle together — the diff on the source is the reviewable part.

Sources render in the design environment, not standalone; the bundles are the portable copy.
