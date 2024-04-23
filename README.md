## 🧞 SWTCO webpage with Astro

All commands should be run from the root of the project, from a terminal:

To run the project locally:

1. `git pull` to get the latest changes
2. `npm install` to have the latest version of the packages needed
3. `npm start` and visit [http://localhost:4321/](http://localhost:4321/) to run the project locally and see it in your browser

More commands:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🚀 Project Structure

The `assets` folder contains SWTCO specific files.

The Astro project files are structured like this:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where you'll find any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory. Move SWTCO specific files there as we start using them.

## 👀 Astro issues?

Check the [documentation](https://docs.astro.build)
