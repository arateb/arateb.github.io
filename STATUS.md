# Status

*Last classified*: 2026-07-16.

This directory hosts the personal GitHub Pages site `arateb.github.io`, served at `ashrafrateb.com` through the `CNAME`. It is not actively developed. Updates are made by hand only.

- Hand-written static HTML: one `index.html` with inline CSS, no build step, no generator. What is committed is what is served.
- No methodology development.
- No Julia package surface. No `Project.toml`, no `src/`.
- Not included in any "commit and push the packages" automation.
- Workspace audits should treat this as a static archive and skip it.

The repository is public, and a push to `main` publishes: GitHub Pages redeploys from the branch with no staging step in between.

If a real research project later needs a hosted page, build it under `/data/projs/<name>/site/` and deploy from there. Do not co-mingle project pages with the personal site.
