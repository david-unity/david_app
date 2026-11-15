# david_app

Public pages for **QR Plus** (iOS), served by GitHub Pages at
`https://david-unity.github.io/david_app/`:

| Page | URL | Used by |
|---|---|---|
| Support | `/david_app/support/` | App Store Connect → Support URL |
| Privacy Policy | `/david_app/privacy/` | App Store Connect → Privacy Policy URL, app Settings + Premium screen |
| Terms of Use | `/david_app/terms/` | App description (Terms of Use link), app Settings + Premium screen |

The app links to these exact URLs, so do not rename the folders. Keep the content in sync
with the app: permissions, third-party SDKs, Premium features and subscription terms.

## Pomodoro

Pages for **Pomodoro** (iOS/macOS) live in `pomodoro/`, same layout as QR Plus:

| Page | URL | Used by |
|---|---|---|
| Support | `/david_app/pomodoro/support/` | App Store Connect → Support URL |
| Privacy Policy | `/david_app/pomodoro/privacy/` | App Store Connect → Privacy Policy URL, app paywall + Settings |
| Terms of Use | `/david_app/pomodoro/terms/` | App paywall + Settings |

The app links to these exact URLs (`AppConstants.swift` in the Pomodoro repo), so do not rename the folders.

## Block

Pages for **Block App** (iPhone) live in `block/`, same layout as Pomodoro:

| Page | URL | Used by |
|---|---|---|
| Support | `/david_app/block/support/` | App Store Connect → Support URL |
| Privacy Policy | `/david_app/block/privacy/` | App Store Connect → Privacy Policy URL, app paywall + Settings |
| Terms of Use | `/david_app/block/terms/` | App description (Terms of Use link), app paywall + Settings |

The Terms page supplements Apple's Standard EULA (App Store Connect keeps the standard license agreement).
The app links to these exact URLs (`AppInfo.swift` in the Block repo), so do not rename the folders.
