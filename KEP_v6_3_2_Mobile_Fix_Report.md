# KEP v6.3.2 — Mobile Experience Fix Report

## Problems seen in screenshots

- Student cards were clipping/cutting on mobile.
- Bottom student navigation was overlapping page content.
- Old “Student Mode / Back to Student Home” strip was still visible on some pages.
- Old version labels like `KEP v5.8` and `KEP v4.4` were still visible.
- Some mobile headings and buttons were too large or cramped.

## Fixed

- All grids become one column on mobile.
- Cards now use full mobile width.
- Added bottom padding so content is not hidden behind the bottom app nav.
- Removed old duplicate student mode strip.
- Kept bottom mobile nav, but made it smaller and safer.
- Improved mobile header and menu spacing.
- Updated old visible version labels.
- Added iPhone-safe input font size to prevent zoom.

## No SQL required

This is a mobile CSS/JS polish update only.
