# cocapn-press

A shared library of press materials and messaging frameworks for the Cocapn ecosystem. Every project announcement in the Fleet uses the same three-sentence structure from this repo. Fork it to deploy consistent communications for your own project.

**Live Preview:** https://the-fleet.casey-digennaro.workers.dev/press

## Why This Exists

You build working code, then waste time explaining it. This repo exists so you can spend that time building instead. We built this for ourselves, then polished it enough for you to use.

## Quick Start

1.  **Fork this repository** to your own GitHub account.
2.  **Deploy** it instantly as a Cloudflare Worker. It requires zero configuration.
3.  **Customize** the templates in `/frameworks` and `/messaging` for your project.

Everything is MIT licensed and built to be copied.

## How It Works

This is a static asset server running on a single Cloudflare Worker. All content is plain text or Markdown files served directly—no build step, no dependencies, and no database.

## What’s Inside

*   **Launch Frameworks:** Three core templates for project announcements, updates, and deprecations.
*   **Audience-Specific Copy:** Pre-written sections for developers, operators, and end-users.
*   **Fork-First Workflow:** Use any asset immediately; all modifications live in your own fork.
*   **Zero Dependencies:** Runs natively on Cloudflare Workers. No external packages.
*   **Plain Text Infrastructure:** All content is Markdown or JSON.

## One Limitation

The library includes exactly three announcement templates. If your project requires a significantly different communication cadence or more than three core message types, you will need to expand the framework yourself.

## Contributing

Improvements to messaging, templates, or documentation are welcome. For changes to core positioning, please open an issue first to discuss.

## License

MIT

<div style="text-align:center;padding:16px;color:#64748b;font-size:.8rem"><a href="https://the-fleet.casey-digennaro.workers.dev" style="color:#64748b">The Fleet</a> &middot; <a href="https://cocapn.ai" style="color:#64748b">Cocapn</a></div>