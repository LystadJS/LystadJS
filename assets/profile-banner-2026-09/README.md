# Profile banner assets

The root README displays the approved aurora banner as 16 adjacent WebP tiles. Ten tiles have independent HTML links: six method buttons and Website, GitHub, LinkedIn, and CV.

## Editing links

Edit the relevant `href` within the `PROFILE BANNER START` / `PROFILE BANNER END` block in the root README. Each anchor has a descriptive `title`, and each linked image has matching `alt` text.

Keep the image markup adjacent, retain `align="top"`, and retain the percentage widths. Adding spaces, line breaks, table cells, or extra image margins inside the banner paragraph can introduce seams. All tile widths in a row sum to 100%.

The image assets form a 1280 x 548 composition. The four right-hand controls have been aligned to the image rows so the button regions remain usable as the profile scales. The source artwork is the approved wide aurora design with its dark grid frame.

`links.json` documents the destination mapping. It is a reference file, not runtime configuration; change the root README to change navigation.

Old banner assets are retained and are not used by this version. No JavaScript, external image host, or scheduled workflow is required.
