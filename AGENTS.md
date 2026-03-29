# Repository Guidelines

## Project Structure & Module Organization
This repository is organized by curriculum track, then lesson group, then exercise. The main sections are `foundations/`, `intermediate-html-css/`, and `advanced-html-css/`. Each exercise lives in its own directory such as `foundations/flex/01-flex-center/` and usually contains `README.md`, `index.html`, and `style.css`. Keep changes scoped to the relevant exercise folder; repo-level files in `.github/` define issue and pull request templates.

## Build, Test, and Development Commands
There is no repo-wide build, package manager, or automated test runner.

- `xdg-open foundations/flex/01-flex-center/index.html`
  Opens an exercise directly in a browser on Linux.
- `python3 -m http.server`
  Serves the repository locally if you prefer browsing exercises through `http://localhost:8000/`.
- Use your editor's Live Preview extension if you want automatic refresh while editing HTML/CSS.

Read the target exercise `README.md` before editing. It defines the desired outcome and self-check requirements.

## Coding Style & Naming Conventions
Follow the existing formatting in each exercise file: 2-space indentation in HTML and CSS, lowercase element names, and simple class-based selectors such as `.container`, `.box`, or `.card`. Keep CSS in the exercise's `style.css` unless the instructions explicitly call for inline or internal styles. Prefer updating existing selectors instead of appending duplicate rules at the end of the file.

## Testing Guidelines
Testing is manual. Open the exercise in a browser and compare the result against the image and checklist in that exercise's `README.md`. Verify layout behavior, spacing, and selector requirements from the self-check section. There is no formal coverage target.

## Commit & Pull Request Guidelines
Recent commits use short, imperative summaries like `Complete first two flexbox exercises` or `added a descendant combinator`. Keep commits focused on one exercise or one documentation change. For pull requests, follow the template in `.github/PULL_REQUEST_TEMPLATE.md`: explain why the change is needed, list what changed, link the related issue, and use the title format `location of change: brief description` such as `01-flex-center: Update self check`.

## Contributor Notes
This repository is for exercises, not learner solution submissions. Do not open pull requests containing completed exercise answers; use PRs only for improving exercise content, instructions, or assets.

## Agent-Specific Instructions
When acting as a teacher for exercise work in this repository, do not provide full solutions or ready-to-paste code unless the user explicitly asks for that. Prefer guided help: break the task into small steps, ask leading questions, point to the relevant files or selectors, and help the user reason their way to the next change.
