# Astro in Space (SSR)

This is an Astro blog generated from the [**official Blog theme**](https://astro.build/themes/details/blog/) that can be pushed in [**Space**](https://deta.space/developers). It is configured with the [`@astrojs/node`](https://docs.astro.build/en/guides/integrations-guide/node/) adapter for SSR. The `Spacefile` is configured to be deployed on [**Space**](https://deta.space/developers).

![blog](https://user-images.githubusercontent.com/22895284/224337874-1520e7d4-2666-4574-8d78-858e24f5e5fe.png)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── Spacefile
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `space push`           | Push Astro to Space                              |
| `space release`        | Release Astro into Space                         |

## 👀 Want to learn more?

- Read the **[Astro docs](https://docs.astro.build/)**
- Read the **[Space docs](https://deta.space/docs/en/introduction/start)**
- Join the **[Astro Discord](https://astro.build/chat)**
- Join the **[Deta Discord](https://go.deta.dev/discord)**

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
