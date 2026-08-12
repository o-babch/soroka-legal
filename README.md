# soroka-legal

The public site for the Soroka app: a landing page with support details, and the
privacy policy. Source of truth lives in the app repository; this repo only hosts
the published pages.

| Page | URL | Source in the app repo |
| --- | --- | --- |
| Landing + support | <https://o-babch.github.io/soroka-legal/> | `index.md` here |
| Privacy policy | <https://o-babch.github.io/soroka-legal/privacy/> | `docs/privacy-policy.md` |
| Account deletion | <https://o-babch.github.io/soroka-legal/delete-account/> | `delete-account.md` here |

The landing page exists because both stores need it: App Store Connect requires a
Support URL, and Google's OAuth branding verification requires a homepage that
explains the app and whose name matches the OAuth app name. A privacy policy alone
satisfies neither.

Nothing here may claim anything the app does not already do - the same rule the
store copy follows.
