# Frontier Notes

A light-themed editorial blog about AI. Published at https://raghav-one.github.io/blog/.

## Publishing a new post

Keep one folder per post, with an `index.html` inside. Use the first article as a structure reference: title and description metadata, date, editorial introduction, visual mechanisms, concise prose, and linked primary sources. Add the post to the journal in the root `index.html`, newest first. Shared styles live in `style.css`.

Preview: `python3 -m http.server 8088` from this folder. Open http://localhost:8088/.

Deployment: GitHub Pages from the `main` branch, repository root. Commit and push, wait for the Pages build, then verify the public article at desktop and mobile sizes. LinkedIn publishing is a separate explicit action through MCP; this repository does not auto-post.
