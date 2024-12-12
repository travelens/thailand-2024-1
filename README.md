# Thailand 2024

Girl's trip to Thailand, visiting Chieng Rai, Chieng Mai and Bangkok. We have been planning this ever since the COVID-19 pandemic lockdown so it has taken almost 2 years to fruition!

## 🚀 Project Structure

Inside this project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── content.config.ts
│   ├── components/
│   │   └── Card.astro
│   ├── gallery/
│   │   └── gallery1/
|   │       └── image.jpeg
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   |   └── index.astro
│   ├── post/
│   │   └── article.md
│   └── trip/
│       └── my-trip.md
│       └── trip.jpeg
└── package.json
```

In addition, each trip will be stored as a separate repository in the
`travelens` organization. This project integrates all the individual
repositories into a single seamless website.

## 🧞 Commands

`pnpm` is used as a package manager
All commands are run from the root of the project, from a terminal:

| Command             | Action                                           |
| :------------------ | :----------------------------------------------- |
| `pnpm install`      | Installs dependencies                            |
| `pnpm dev`          | Starts local dev server at `localhost:3000`      |
| `pnpm build`        | Build your production site to `./dist/`          |
| `pnpm preview`      | Preview your build locally, before deploying     |
| `pnpm astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro --help` | Get help using the Astro CLI                     |
