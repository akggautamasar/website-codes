# Website Codes

Reusable archive of authored interactive website effects and landing-page source.

## Effects

- **Kage** — Full HTML + DOM/CSS + Three.js
- **Sketchbook** — Full HTML + DOM/CSS + JavaScript
- **Sylva Living Green** — Full HTML + DOM/CSS + local Three.js
- **Complete Shelf** — Full HTML + DOM/CSS + Three.js r165

## Repository layout

Each effect is isolated under `effects/<effect>/`. The original complete source bundle is retained as `SOURCE-BUNDLE.txt`. Where the supplied bundle exposed extractable source files, those are also stored at their authored paths.

## Reuse

Copy the relevant effect directory into a React/Next.js project and preserve the internal public paths. Kage, for example, uses:

`/landing-pages/kage.html`

The authored renderer should be preserved rather than replaced with a visual approximation.

## Provenance

Source revision identifiers and asset hashes supplied with the source material are retained in the corresponding source bundles.

## Asset note

Some binary scene assets were not present in the supplied source material. Their paths/hashes should be added when the original binaries are available. No substitute assets are claimed to be byte-exact.

## License

No redistribution license is asserted by this repository. Verify that you have permission to redistribute any third-party source or assets before publishing or deploying them.
