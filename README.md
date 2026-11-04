# minjunhuang.github.io

Portfolio site for MinJun Huang, UX/UI designer in London.

Static HTML, CSS and JavaScript. No framework, no build step.
Open `index.html` in a browser to preview locally.

## Adding a project

1. Put the images in `assets/<slug>/`
2. Add an entry to `data/projects.js`

Each entry:

```js
{
  slug: "greener",
  title: "Greener",
  year: 2026,
  summary: "One line.",
  tags: ["Mobile app", "UX research"],
  cover: "assets/greener/cover.webp",
  blocks: [
    { type: "section", value: "The problem" },
    { type: "heading", value: "The point of this section." },
    { type: "text",    value: "A short paragraph." },
    { type: "image",   value: "assets/greener/board.webp" },
    { type: "caption", value: "Optional line under an image." }
  ]
}
```

The home list and every case study page are generated from that file.
Nothing is hardcoded into the HTML.

`DESIGN.md` holds the rules the site is built to. Read it before changing anything.
