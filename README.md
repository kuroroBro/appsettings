# appsettings

Public remote switches for apps, served by GitHub Pages (Settings → Pages → Deploy from branch `main`, root).

## tennisvibe/appsetting.json

| Key | Default | Meaning |
|-----|---------|---------|
| `paywallEnabled` | `true` | `false` turns the paywall off: all Pro features are open to everyone. |

URL: https://kurorobro.github.io/appsettings/tennisvibe/appsetting.json

The app reads it at launch and when it becomes active, and keeps the last value if it can't be fetched.
Pages can take ~10 minutes to refresh after a push. Anyone can read these files; they are not a security control.
