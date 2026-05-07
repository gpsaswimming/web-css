# web-css

Shared stylesheet CDN for Greater Peninsula Swimming Association, served at `css.gpsaswimming.org`.

## Available Stylesheets

| File | Purpose |
|------|---------|
| `gpsa-tools-common.css` | Shared styles for all GPSA web tools — headers, buttons, toasts, modals, brand colors |
| `gpsa-main.css` | Main site styles — imports roster, contacts, and officials stylesheets |
| `gpsa-roster.css` | Roster table styles for SwimTopia HTML exports |
| `gpsa-roster-contact.css` | Contact table styles for SwimTopia HTML exports |
| `gpsa-roster-officials.css` | Officials list styles for SwimTopia HTML exports |
| `gpsa-swimtopia-iframe.css` | Styles for SwimTopia iframe embeds |
| `invitationals-main.css` | Invitationals site styles — imports meet, table, store, and records stylesheets |
| `invitationals-meets.css` | Meet listing styles for invitationals site |
| `invitationals-tables.css` | Results table styles for invitationals site |
| `invitationals-store.css` | Store/merchandise styles for invitationals site |
| `invitationals-records.css` | Records table styles for invitationals site |
| `zz_legacy.css` | Legacy styles — do not reference in new work |

## Usage

Reference any stylesheet using its absolute URL:

```html
<link rel="stylesheet" href="https://css.gpsaswimming.org/gpsa-tools-common.css">
```

## Adding or Updating Styles

Push changes to `main` — GitHub Actions deploys automatically to Cloudflare Pages.

All GPSA repos reference these files by absolute URL. Changes here affect every site immediately, so test thoroughly before pushing.
