# Evan Lee — Portfolio

A single self-contained static site (`index.html` — no build step, no dependencies).

## Adding a project later

Open `index.html`, find the `PROJECTS` array inside the `<script>` tag near the
bottom of the file, and add a new object:

```js
{
  title: "Project Name",
  subtitle: "One-line description",
  description: "1-2 sentences about it.",
  tags: ["Tech", "Stack", "Used"],
  status: "live", // or "soon" for a coming-soon placeholder
  link: "https://your-project-url.com"
}
```

The grid on the page rebuilds itself from this array automatically — no other
HTML or CSS needs to change.

## Running it locally

Just open `index.html` in a browser. No server or build step required.

## Deploying

See the deploy steps in the project chat, or:

1. Push this folder to a GitHub repo.
2. Go to https://vercel.com/new, import that repo, and deploy — Vercel will
   detect it as a static site automatically (no framework, no build command,
   root output directory).
