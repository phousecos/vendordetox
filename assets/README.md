# Assets

Place brand assets here.

## `jlynne-logo.png` (required for the About section)

The landing page's About section loads the J. Lynne & Co. logo from
`assets/jlynne-logo.png`. Until that file exists, the section falls back to a
"JL" monogram automatically (no broken image).

To add the logo, commit a file named exactly `jlynne-logo.png` into this
`assets/` folder. A transparent-background PNG (roughly square, 512×512 or
larger) looks best against the white logo tile. An SVG also works — if you
use `jlynne-logo.svg` instead, update the `src` in `index.html`.

The fastest way to add it without a local checkout: on GitHub, open this
`assets/` folder on the `claude/vendor-detox-landing-page-8c1sjm` branch,
choose **Add file → Upload files**, and drop the PNG in. Vercel will redeploy
and the logo will appear.
