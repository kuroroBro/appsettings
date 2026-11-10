# appsettings

Public remote switches for apps, served by GitHub Pages (Settings → Pages → Deploy from branch `main`, root).

## tennisvibe/appsetting.json

| Key | Default | Meaning |
|-----|---------|---------|
| `paywallEnabled` | `true` | `false` turns the paywall off: all Pro features are open to everyone. |

URL: https://kurorobro.github.io/appsettings/tennisvibe/appsetting.json

The app reads it at launch and when it becomes active, and keeps the last value if it can't be fetched.
Pages can take ~10 minutes to refresh after a push. Anyone can read these files; they are not a security control.

## vibecap/appsetting.json

| Key | Default | Meaning |
|-----|---------|---------|
| `paywallEnabled` | `true` | `false` turns the paywall off: all VibeCap Pro features are open to everyone and the Settings Pro section is hidden. |

URL: https://kurorobro.github.io/appsettings/vibecap/appsetting.json

Same behavior as TennisVibe. Keep it `true` while the app is in App Review, so the reviewer can see the subscription.
