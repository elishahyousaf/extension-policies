# Extension Privacy Policies

Privacy policy pages for the Chrome extensions published by **BYDP (E.A Services)**. One plain-English page per extension, as static HTML — no tracking, no scripts, no server.

## Why this repo exists

The Chrome Web Store requires each listing’s privacy policy link to lead **directly to a policy page**. These pages live here so every listing can point at its own page. GitHub Pages for this account redirects to a broken custom domain, so the live links below use the jsDelivr CDN instead of GitHub Pages.

## Policies

| Extension | Policy file | Live link |
|---|---|---|
| TabMind — AI Tab Triage & Workspaces | `tabmind-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/tabmind-privacy.html |
| TrustLens — Extension Trust Auditor | `trustlens-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/trustlens-privacy.html |
| InboxPilot — AI Gmail Triage, On-Device | `inboxpilot-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/inboxpilot-privacy.html |
| ReadEase — Reading Companion for Dyslexia & ADHD | `readease-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/readease-privacy.html |
| CartHawk — Honest Price Tracker | `carthawk-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/carthawk-privacy.html |
| Smart Persona Switcher (PersonaFlow) | `persona-switcher-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/persona-switcher-privacy.html |
| ApplyPilot | `applypilot-privacy.html` | https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/applypilot-privacy.html |

`index.html` links the policies from one page. (Note: it currently links six of the seven pages — ApplyPilot is in the repo but not yet linked there.)

## What the policies have in common

Each policy states, in plain English, what its extension does with your data. The shared principle across all of them:

- **Your data stays on your device.** Processing happens locally in the browser; nothing is sent to a server.
- **No accounts, no sign-in, no email collection.**
- **No analytics, telemetry, crash reporters, or advertising.**
- **No data selling.**
- **Uninstalling an extension deletes everything** — there is nothing on a server to delete, because nothing was ever sent.

See each policy page for the details of that extension — what it reads (for example tab titles and URLs, or Gmail content for triage), which permissions it uses and why, and what it never does.

## Adding a policy for a new extension

1. Copy the closest existing `*-privacy.html` file and rename it `<extension>-privacy.html`.
2. Update the title, the "Last updated" date, the data it reads, the permissions list, and the contact section. Keep it plain English and keep every claim true for that extension.
3. Add a link to it in `index.html` and a row in the table above.
4. Use the jsDelivr URL (`https://cdn.jsdelivr.net/gh/elishahyousaf/extension-policies@main/<file>`) as the privacy policy URL in the Chrome Web Store listing — not a GitHub Pages URL.

## License

MIT — see [LICENSE](LICENSE).
