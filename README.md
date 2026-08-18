# Agentic Creation

This repository publishes the Agentic Creation organization homepage at
<https://agentic-creation.github.io/>.

The website is built from the canonical
[`GeminiLight/awesome-agentic-artifact-creation`](https://github.com/GeminiLight/awesome-agentic-artifact-creation)
repository. The deployment workflow checks out its `main` branch, rebuilds the
catalog, and deploys the generated site to GitHub Pages.

Synchronization runs:

- whenever this deployment repository changes;
- every six hours; and
- on demand from the Actions tab.

Keep catalog and website source changes in the canonical Awesome repository so
the two repositories cannot drift.
