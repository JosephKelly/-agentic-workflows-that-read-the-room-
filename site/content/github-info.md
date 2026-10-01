# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Recent updates

- **Async merge API is generally available** – Merge individual or stacked pull requests, add them to a merge queue, or merge directly (optionally bypassing rules if you have permission). Submit a merge request with `PUT`, then poll with `GET` using the returned request ID. GitHub now recommends it over the synchronous REST endpoint or GraphQL mutations for programmatic merges. Source: [GitHub Changelog](https://github.blog/changelog/2026-10-01-github-async-merge-api-generally-available).
- **GitHub Copilot app for Beginners series** – Walkthroughs on running several agents at once and using the diff, terminal, and browser. Sources: [GitHub Blog: Run several agents at once](https://github.blog/ai-and-ml/github-copilot/github-copilot-app-for-beginners-run-several-agents-at-once/), [GitHub Blog: Using the diff, terminal, and browser](https://github.blog/ai-and-ml/github-copilot/github-copilot-app-for-beginners-using-the-diff-terminal-and-browser/).
- **Refreshed repository pull requests page is generally available** – Find pull requests faster with content-assisted filters, advanced search (`AND`/`OR` and nested queries), a collapsible sidebar with common filters like "Authored by me", compact mode, and bulk actions such as closing and labeling. Source: [GitHub Changelog](https://github.blog/changelog/2026-09-21-refreshed-repository-pull-requests-page-generally-available).
- **Node 20 is no longer available in GitHub Actions** – Runners now use Node 24 for JavaScript actions and the temporary opt-out is gone. Action maintainers should set `runs.using` to `node24` and publish a new release; workflow authors should move to the latest action versions. Source: [GitHub Changelog](https://github.blog/changelog/2026-09-23-node-20-is-no-longer-available-in-github-actions).
- **Copilot code review: improved review experience** – The overview comment groups findings into Open, Resolved since last review, and Previously missed, with severity and links to inline comments. Copilot also auto-resolves its own fixed suggestions and writes commit messages when you accept suggestions in a batch. Source: [GitHub Changelog](https://github.blog/changelog/2026-09-18-copilot-code-review-an-improved-review-experience).
