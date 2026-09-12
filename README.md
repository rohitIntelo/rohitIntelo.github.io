# sites

Dumpyard for LLM-agent-generated static sites by Rohit. Served via GitHub Pages
at <https://rohitintelo.github.io/>.

## Layout

- `/index.html` — apex page. Spartan. Keep it that way.
- `/research/<report-name>/index.html` — reports.
- `/learning/<guide-name>/index.html` — guides.
- `/plans/<plan-name>/index.html` — project plans.
- `/llms.txt` — instructions for LLMs uploading to this repo. Read it before adding anything.

## Rules

- Every page is self-contained HTML with inline CSS/JS. No build step, no frameworks, no external dependencies unless unavoidable.
- Slugs are lowercase kebab-case.
- Adding a page? Follow `/llms.txt`.
