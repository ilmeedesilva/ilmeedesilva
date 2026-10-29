# Hi, I'm Ilmee 👋

Fullstack software engineer based in Colombo, Sri Lanka, working mostly on the backend with Python and FastAPI. For the past three years I've built cloud integrations and AI document-automation pipelines for Australian enterprise clients, including an LLM-powered extraction pipeline that turned a month-long manual tax review into a few days.

I like building tools that take real work off people's plates, and making them reliable enough to trust.

🌐 [Portfolio](https://ilmeedesilva.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/ilmeedesilva)
<!-- Once your post is live, add: · ✍️ [Blog](https://dev.to/YOUR-HANDLE) -->

## 🚀 Featured project: [patchpilot](https://github.com/ilmeedesilva/patchpilot)

An AI agent that upgrades a Python dependency, **fixes the code that breaks**, and opens a pull request explaining what changed and why. Install it with `pipx install patchpilot`.

![patchpilot demo](https://raw.githubusercontent.com/ilmeedesilva/patchpilot/main/docs/demo.gif)

- A hand-written tool-use agent loop on the Claude API
- The project's code runs in a locked-down **Docker sandbox** (only the repo is mounted, non-root, capped resources)
- Works in a temporary **git worktree**, so your checkout is never touched
- **Re-runs the tests itself** before committing, instead of trusting the model
- Opens the PR through the GitHub CLI; failing upgrades open as drafts

➡️ See the [pull request it opened](https://github.com/ilmeedesilva/patchpilot-demo/pull/1) on a demo app, upgrading pydantic v1 to v2.

## 🛠️ Other projects

| Project | What it is | Built with |
|---|---|---|
| [MESA](https://github.com/ilmeedesilva/MESA) | A cross-service static analysis tool that detects architectural anti-patterns in microservices | Python, TypeScript, PostgreSQL, Docker |
| [Diabetic Retinopathy Stage Detection](https://github.com/ilmeedesilva/Diabetic-Retinopathy-Stage-Detection) | Computer vision model that classifies diabetic retinopathy stages from retinal images | Python, Jupyter |
| [ReceiptSnap](https://github.com/ilmeedesilva/ReceiptSnapApp) | iOS app for receipt and expense management | Swift |
| [ClinicFlow](https://github.com/ilmeedesilva/ClinicFlow) | iOS app for clinic management | Swift |
| [Tuk-tuk tracking API](https://github.com/ilmeedesilva/tuk-tuk-tracking-web-api) | Web API for tracking tuk-tuks | JavaScript |

## 🧰 Tech I work with

**Languages:** Python · TypeScript · JavaScript · Swift · Java
**Backend & infra:** REST APIs · PostgreSQL · Docker · GitHub Actions
**AI:** LLM agents and tool use (Claude API) · computer vision · machine learning
