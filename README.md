# glovia-legal

The published Privacy Policy and Terms of Service for the **Glovia** app, served
via GitHub Pages.

- [privacy.html](privacy.html) — Политика за поверителност / Privacy Policy
- [terms.html](terms.html) — Общи условия / Terms of Service

Each page carries the Bulgarian text first and the English below it, under an
`#en` anchor. Plain HTML, no build step, no dependencies — edit the file, commit,
and Pages redeploys.

The app also ships the full text on-device (`LegalDocumentScreen`), which is what
works offline and what a store reviewer reads first. **These pages and the
on-device text must say the same thing.** When one changes, change the other:
the app's copy lives in `mobile/lib/features/onboarding/legal_text.dart` in the
main repo, and the addresses of these pages in
`mobile/lib/core/config/app_identity.dart`.

Contact: info@astrextech.com
