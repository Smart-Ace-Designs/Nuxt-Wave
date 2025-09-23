# Nuxt Template: Wave
Nuxt **Wave** is an opinionated Nuxt 4 starter template with built-in support for Nuxt UI, Tailwind CSS, and Prettier. It also includes a simple _Welcome_ component to showcase basic Nuxt UI functionality.

Using `create nuxt@latest` provides everything you need to create a basic Nuxt application. However, it is missing a few useful items that you might find yourself manually adding to every new Nuxt project. The **Wave** template was created to automatically include these items. This provides a great starting point for a new Nuxt project with Nuxt UI and Tailwind.

The template includes:
- An initial Nuxt 4 project structure
- [Nuxt UI 4](https://ui.nuxt.com)
  - Integrates with [Tailwind CSS v4.1](https://tailwindcss.com/)
  - Integrates with [Nuxt Icon](https://nuxt.com/modules/icon)
  - Integrates with [Nuxt Fonts](https://nuxt.com/modules/fonts)
  - Integrates with [Nuxt Color Mode](https://nuxt.com/modules/color-mode)
  - Integrates with [Nuxt Content](https://nuxt.com/modules/content)
- [Prettier](https://prettier.io/)
- Initial <head> elements for language and title set in _nuxt.config.ts_
- A default _main.css_ file
- An opinionated Nuxt UI color theme set in _app.config.ts_
- Default _.vscode_ files to properly handle Tailwind CSS, recommended extensions, and default Prettier formatters
- A simple _Welcome_ component displayed from _app.vue_
- The `dev` script set to `"nuxt dev -o"`

## Deployment Methods
### bun
```sh
bunx giget gh:smart-ace-designs/nuxt-wave project-name
```
### npm
```sh
npx giget gh:smart-ace-designs/nuxt-wave project-name
```

> [!Note]
> You should manually clear the contents of this README file after deployment.

## Project Structure
After deploying the Nuxt **Wave** template you will see the following files and directories in your project root:

```text
/
├── .vscode/
│   ├── extensions.json
│   └── settings.json
├── app/
│   ├── assets/
│   │   └── css
│   │       └── main.css
│   ├── components/
│   │   └── App
│   │       └── Welcome.vue
│   ├── pages/
│   │   └── index.vue
│   ├── app.config.ts
│   └── app.vue
├── public/
│   ├── favicon.ion
│   └── robots.txt
├── .gitignore
├── .prettierrc
├── nuxt.config.ts
├── package.json
├── README.md
└── tsconfig.json
```



