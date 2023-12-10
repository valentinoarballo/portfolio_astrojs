# Personal Portfolio Website In Astro

You can see the website deployed [in here](https://dashing-platypus-c0244a.netlify.app/)

## 🚀 Website Performance

This website is built with [Astro](https://astro.build/), a new framework that lets you build faster websites with less JavaScript. Astro generates static HTML at build time, which means that only the HTML file is sent to the browser, without any JS. This makes the website lighter, faster, and more SEO-friendly. 


This website is also hosted on [Netlify](https://www.netlify.com/), a web service that allows me to deploy this site for free and offers a composable web architecture that adapts to my needs. Netlify uses the [Cloudflare](https://www.cloudflare.com/) CDN (Content Delivery Network) to deliver the website faster thanks to a network of servers located in different geographic points that store and transfer content near the end users, improving the performance and availability of the website. 


To measure the performance of this website, I used [PageSpeed Insights](https://pagespeed.web.dev/), a tool that analyzes the performance of a web page on mobile and desktop devices, and offers suggestions to improve it. It shows a score from 0 to 100 based on different metrics such as the load time, the time to interactive, the time to largest contentful paint, etc.

![portfolio performance](https://github.com/valentinoarballo/portfolio_astrojs/blob/main/public/assets/images/portfolio-performance.png)

## 🏗️ Project Structure

Inside of this Astro project, you'll see the following folders and files:

```
/
├── public/
│   ├── assets
│   │   ├── fonts
│   │   └── images
│   └── favicon.svg
│
├── src/
│   ├── components/
│   │    ├── Header.astro
│   │    ├── Footer.astro
│   │    └── ...
│   │
│   ├── layouts/
│   │   └── Layout.astro
│   │
│   └── pages/
│       └── index.astro
│
├── package.json
├── tsconfig.json
├── tailwind.conf.js
└── ...
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/assets` directory.

Your personal data would be go on `src/data` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [Astro documentation](https://docs.astro.build) or jump into Astro [Discord server](https://astro.build/chat).
