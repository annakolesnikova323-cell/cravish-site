# cravish-site

The two public pages the Cravish iPhone app links to, plus their Ukrainian versions. Served by
GitHub Pages straight from the `main` branch — plain HTML and one stylesheet, nothing to build.

| Page | Address |
| --- | --- |
| Privacy policy | https://annakolesnikova323-cell.github.io/cravish-site/privacy |
| Help & feedback | https://annakolesnikova323-cell.github.io/cravish-site/support |
| Ukrainian versions | …/cravish-site/uk/privacy and …/cravish-site/uk/support |

The same two addresses go into `Cravish/App/AppLinks.swift` in the app and into App Store Connect
(Privacy Policy URL, Support URL). **Do not rename or move these files**: the app that people have
installed keeps opening the old addresses.

## Publishing

Repository → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
After that every push to `main` goes live within a minute or two.

## Editing

- Change the English and the Ukrainian page together.
- When the privacy policy changes, update "Last updated" on both versions.
- The pages load nothing from other sites (no fonts, scripts or analytics) — keep it that way,
  a privacy policy should not track its readers.
