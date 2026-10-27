# Local check summary

- Theme: Proof · Prism 0.1.1
- Manifest SHA-256: `06fc9528338f0371e1fd0d3be127be576d4201bc2cf8bebfaf4c4dd1b89028bb`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 11.84:1, title 11.84:1, link 5.58:1, tag 5.58:1, code 10.72:1, mark 10.18:1, chosen 10.06:1.
  - Dark: body 11.88:1, title 11.88:1, link 5.21:1, tag 5.21:1, code 10.43:1, mark 10.67:1, chosen 10.55:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
