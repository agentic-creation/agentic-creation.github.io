# Agentic Creation

This repository publishes the Agentic Creation organization homepage at
<https://agentic-creation.github.io/>.

The website is built from the canonical
[`GeminiLight/awesome-agentic-artifact-creation`](https://github.com/GeminiLight/awesome-agentic-artifact-creation)
repository. The deployment workflow checks out its `main` branch, rebuilds the
catalog, and deploys the generated site to GitHub Pages.

Every deployment validates the catalog, generated README, and source tests before
publishing. The workflow records the source commit in its run summary. It builds
with `--site-url https://agentic-creation.github.io/` so canonical URLs, social
metadata, and the sitemap point to this organization's website.

Synchronization runs:

- whenever this deployment repository changes;
- every six hours; and
- on demand from the Actions tab.

To publish a newly merged source change immediately:

```sh
gh workflow run pages.yml --repo agentic-creation/agentic-creation.github.io
```

Keep catalog and website source changes in the canonical Awesome repository so
the two repositories cannot drift.
