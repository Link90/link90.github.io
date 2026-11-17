# link90.github.io

Static files that let an Android app open its own links (Android App Links):

- `.well-known/assetlinks.json`: the app's package name and the public fingerprint of its
  signing certificate. Both are public by design: every copy of an app carries them.
- `finfree/callback/`: a return page with no scripts, shown only if the app doesn't open by
  itself.
- `robots.txt` keeps the return page out of search engines. `.nojekyll` lets GitHub Pages
  serve `.well-known/`.

Nothing else lives here: no data, no secrets, no scripts.
