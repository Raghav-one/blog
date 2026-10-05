# Raghav’s Blog

Raghav’s personal AI blog, with compact, light article formatting. Published at https://raghav-one.github.io/blog/.

## Publishing a new post

Keep one folder per post, with an `index.html` inside. Use the first article as a structure reference: title and description metadata, date, a direct introduction, numbered sections, captioned historical figures, substantial connected prose, and inline primary-source links. Add the post to the post list in the root `index.html`, newest first. Shared styles live in `style.css`.

Preview: `python3 -m http.server 8088` from this folder. Open http://localhost:8088/.

Deployment: GitHub Pages from the `main` branch, repository root. Commit and push, wait for the Pages build, then verify the public article at desktop and mobile sizes. LinkedIn publishing is a separate explicit action through MCP; this repository does not auto-post.

## Editorial and layout direction

Use the article layout of Sebastian Raschka’s https://magazine.sebastianraschka.com/p/classifier-history-and-jev as a formatting reference: compact title and byline, centered reading column, numbered sections, readable body text, inline citations, and captioned figures in the narrative. Keep personal ownership under Raghav’s name. Avoid oversized heroes and blue branding. The first post prioritizes historical chronology, people, milestones, setbacks, and context; technical mechanisms support the history.

Use technology names for headings and explain mechanisms with enough depth to connect the historical milestones. Highlight key technical terms and causal distinctions using selective bold and italic emphasis; do not compress each era into a few summary statements.

Article typography follows the density of https://www.danielscrivner.com/situational-awareness-essays-by-leopold-aschenbrenner/: 16px body text, 24px line height, 20px paragraph spacing, and proportionally smaller technology headings. Preserve the full text and its emphasis.
