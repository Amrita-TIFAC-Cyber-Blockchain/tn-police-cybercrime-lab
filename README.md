# TN Police Academy — Cybercrime Investigation Lab

A bilingual (English/Tamil), static browser-based training simulator for freshly recruited Sub-Inspectors. It contains eight fictional, decision-based modules covering AI-enabled impersonation, cryptocurrency fraud, evidence handling and investigation planning.

## Important use limitation

**Training use only.** All names, events, wallets, transactions and records are fictional. This project does not detect deepfakes, identify wallet owners, provide legal advice, or establish that a crime occurred. Its feedback is educational—not forensic proof. Follow current law, departmental SOPs, authorisation requirements and supervisory direction in real cases.

## Modules

1. Deepfake Detective
2. The Cloned Voice
3. Deepfake Video Meeting
4. Fake Crypto Investment
5. Follow the Crypto Trail
6. Digital Evidence Triage
7. Build the Timeline
8. Final Case Challenge

The interface includes English and Tamil labels, scenario prompts, decision feedback, progress tracking and an instructor guide. The default 120-minute plan is a suggested facilitation structure; module timings can be adapted.

## Run locally

No build step, package manager, API key or backend is required.

- Open `index.html` in a modern browser, or
- Serve the folder using any static web server.

## Deploy to GitHub Pages

1. Create a GitHub repository, for example `tn-police-cybercrime-lab`.
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source.
4. Commit the included workflow at `.github/workflows/deploy.yml` to the default branch.
5. Open the **Actions** tab and wait for the Pages workflow to complete.
6. Find the published URL under **Settings → Pages**.

The workflow deploys the repository as a static site. No secrets are needed.

## Repository structure

```text
.
├── index.html
├── assets/
│   ├── css/style.css
│   └── js/app.js
├── .github/workflows/deploy.yml
└── README.md
```

## Evidence-handling teaching points

- Preserve original files and document provenance, source, collection time and handling.
- Avoid unnecessary alteration; use approved acquisition and storage procedures.
- Maintain access controls and documented chain of custody.
- Record timestamps, time zones and clock discrepancies.
- Corroborate claims across independent sources.
- Treat blockchain addresses as transaction identifiers, not automatic proof of a person's identity.
- Seek records through lawful, authorised processes and follow applicable procedures.

## Privacy and security

- No analytics, external API calls, external fonts, or third-party scripts.
- No personal data or actual case material should be entered.
- The progress state is held in the current page session; no trainee data is uploaded.
- Do not add API keys or confidential information to a public repository.

## Customisation

Edit `assets/js/app.js` to revise module text, choices, feedback, translations and durations. Keep scenarios fictional and have training content reviewed by qualified instructors before delivery.

## Accessibility

The interface uses semantic controls, keyboard-dismissable modal behaviour, visible focusable buttons and responsive layouts. Review with the academy's supported devices and accessibility requirements before deployment.
