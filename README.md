# sprout-app

The public website for **Sprout: One Second a Day** (小芽), an iPhone app that
records one to three seconds a day and strings them into a film.

This repository contains **only the website**. The app's source code lives
elsewhere and is not published here.

It exists because App Store Connect requires public URLs for the privacy policy
and the support page, and a reviewer has to be able to load them.

## What's here

| File | Serves | App Store Connect field |
|---|---|---|
| `index.html` | <https://jasonmanxy.github.io/sprout-app/> | Marketing URL |
| `support/index.html` | <https://jasonmanxy.github.io/sprout-app/support/> | Support URL |
| `privacy/index.html` | <https://jasonmanxy.github.io/sprout-app/privacy/> | Privacy Policy URL (English and all other locales) |
| `privacy/zh/index.html` | <https://jasonmanxy.github.io/sprout-app/privacy/zh/> | Privacy Policy URL (zh-Hans, zh-Hant) |

Served by GitHub Pages from the `main` branch, root folder.

## House rules

- **Plain, self-contained HTML.** CSS is inlined in each page. No build step, no
  Jekyll, no framework.
- **No external requests of any kind** — no CDN, no web fonts, no analytics, no
  embedded media. The product's whole claim is that it never phones home; a site
  that loaded third-party scripts to make that claim would be lying. If you edit
  a page, keep it that way.
- Both privacy policies say the same thing. Change one, change the other, and
  bump the "last updated" date on both.
- Every factual claim on these pages was checked against the app's source. Don't
  add a feature to the site that the app doesn't have.

## Contact

<weijiacheng34@163.com>
