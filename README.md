# Public website (support + privacy policy)

These files are the app's public web pages. Both stores need the privacy policy link,
and the app links to it from About and privacy.

- `index.html`: help and support (store "Support URL")
- `privacy.html`: privacy policy (store "Privacy policy URL")

They are published from a separate **public** repository so the app code stays private:
`https://github.com/abspatel1/refi-compare-site` → `https://abspatel1.github.io/refi-compare-site/`.
Step-by-step: docs/store-submission.md, part 1.

Rules:
- Edit here first, then copy to the public repo (Claude can push it for you). Never edit only the public copy.
- The privacy page repeats the app's privacy paragraphs word for word. A test fails if they drift apart.
- The maker name (now Abbas Patel) appears in `privacy.html` and the App Store copyright line; change both together. Any `{{PLACEHOLDER}}` left in a page blocks the release check.
- No scripts, cookies, analytics, fonts or anything loaded from other sites.
