# Personal Portfolio - Astro Theme Pure

A simple, fast and powerful blog & document theme built by Astro. 

> [!NOTE]
> Known issues: Header & customize options is still under development (template exposed still).

## Introduction

Hi, This is Rejit aka dream, god knows how long I have wanted a personal website, this is a start. And this time I plan to look it all through,  understanding this codebase and seeking much less AI help possible. I wanna be responsible for what breaks in here. 

### :package: Components ( for me to remember )

Theme includes a lot of components, which can not only be used in the theme, but also in other astro projects.

- Basic components: `Aside`, `Tabs`, `Timeline`, `Steps`, `Spoiler`...
- Advanced components: `GithubCard`, `LinkPreview`, `Quote`, `QRCode`...


## Package ( not sure if i should remove bun and use npm, i remember doing it before and it breaking cuz of it)

See [astro-theme-pure](https://www.npmjs.com/package/astro-pure) on npm.

## Local development

Environment requirements:

- [Nodejs](https://nodejs.org/): 18.0.0+

if you want my look you can clone this repository:

```shell
gh repo clone Dreamgamer5000/personal-portfolio-astro-theme-pure
cd personal-portfolio-astro-theme-pure
```

Useful commands for now:

```shell
# Install dependencies
bun install
# Start the dev server
bun dev
# Build the project
bun run build
# Preview (after the build)
bun preview
# Create a new post
bun pure new
```

## Thanks

Thanks to cworld1 and all other developers behind this.

- [Astro theme pure](https://github.com/cworld1/astro-theme-pure)
- Checkout [original Site →](https://astro-pure.js.org/)


## License

This project is license will be changed (prolly GPL)

## add stuff in 
 - src/pages/photographs/index.astro
 - recipes

## information Changes required in
 - src/pages/projects/index.astro
 - src/pages/about/index.astro
 - src/pages/links/index.astro
 - src/pages/index.astro