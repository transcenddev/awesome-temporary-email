Thank you for considering a contribution to this curated list.

Purpose
- This repo is a Markdown-only curated reference of temporary / disposable email services. Keep changes minimal, focused, and easy for reviewers to validate.

Service entry template (required)
When adding or updating a service, follow this exact structure in `README.md` under `## Services (curated)`:

1. **Name** - Short descriptor (one line)

   - Features: short · tags · separated · by · middot
   - Link: https://example.com
   - Recommended: **Yes** (optional)

Example:

1. **Mail.tm** - Privacy-focused, API access, inbox persistence.

   - Features: Privacy-focused · API · Inbox persistence
   - Link: https://mail.tm
   - Recommended: **Yes**

Privacy scorecards
- Use the existing token scheme under `## Privacy Scorecards` when editing or adding scores:
  - Logging: `Low|Medium|High`
  - Retention: `Short|Medium|Long`
  - TLS: `Yes|No`
  - API: `Yes|No|Partial` (use `Partial` for unofficial endpoints)

Images / assets
- Place screenshots in `assets/` and reference them with a relative path.
- Recommended format: `PNG` or `WEBP`. Suggested size: 1200×600px (max 1MB).

PR body checklist
- Use the PR template when opening a PR. At minimum include:
  - One-line summary (title)
  - Link to the service
  - 1–2 feature tags (e.g., `API`, `Persistence`, `Privacy`)
  - Optional screenshot path (if added)

Local editing and TOC
- We maintain a workflow that regenerates the README TOC automatically on push/PRs touching `README.md`.
- For local edits, you can use VSCode's "Markdown All in One" extension -> `Create/Update Table of Contents` or run `markdown-toc -i README.md`.

Commit messages
- Prefer Conventional Commits for changelogs and clarity. Examples:
  - `feat: add new service Mail.foo`
  - `chore(docs): update README Table of Contents`

What we do NOT want
- Large reformatting, moving content into new file types, or adding non-markdown code.

If anything in this guide is unclear, open an issue with a short note and I'll clarify.
