# 0xmodo — Developer homepage

A personal homepage for 0xmodo, a computer science master’s graduate working
as a developer at a software company. Interests include frontend engineering,
software architecture, and database technology.

**[Visit the homepage](https://0xmodo.github.io/)**

## Projects

- **[Paintlet](https://github.com/0xmodo/paintlet)**: a JavaScript and Canvas 2D
  drawing board with pixel editing, undo/redo, image transforms, and PNG export.
  [Try the drawing board](https://paintlet.vercel.app).
- **[Lamplight](https://github.com/0xmodo/lamplight)**: an animated nighttime
  workspace drawn with JavaScript and Konva.
  [Enter the room](https://0xmodo.github.io/lamplight/).

The homepage includes a personal introduction, two completed projects, technical
interests, GitHub contact links, and planned learning implementations inspired by
Cloudflare Durable Objects and Supabase Realtime. Plans are explicitly marked as
not yet built. No employer, university, or work history beyond the supplied
profile is claimed. It uses semantic
HTML and responsive CSS, with no JavaScript requirement or build step.

## Local preview

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`. No application credentials or dependencies are needed.
Lamplight is published from a separate repository; its demo link requires that
project's Pages deployment. For a local homepage-only preview, it will not exist
under this server's `/lamplight/` path.

## Structure

- `index.html`: developer profile, project details, and navigation.
- `assets/css/site.css`: responsive editorial layout, system diagram, and typography.
- `assets/favicon.svg`: the site monogram.
- `assets/fonts/`: locally served Ubuntu fonts and their license.
- `assets/previews/`: screenshots of the featured projects.
- `.nojekyll`: serves the repository directly as static GitHub Pages content.

## Publishing and verification

GitHub Pages publishes the root of the `main` branch. There is no build pipeline
or automated test suite. Before publishing, check desktop and mobile layouts,
keyboard navigation, image loading, and project links. The homepage should remain
readable with JavaScript disabled.

[Lamplight](https://github.com/0xmodo/lamplight) is an independent animation
project with its own repository and commit history. This homepage links to it
as a featured work.

Code is MIT licensed. See [LICENSE](LICENSE) and [NOTICE](NOTICE) for attribution.
