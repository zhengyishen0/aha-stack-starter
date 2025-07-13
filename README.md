# AHA Stack Starter Kit: 

## To-Dos:
- [ ] fix the alpine components and the htmx todo list
- [ ] install all the alpine plugins
- [ ] convert ahtropic website to alpine components
- [ ] convert all the marketing template using alpine basic elements
- [ ] css class and global css


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🎨 Pine Marketing Components

This project includes marketing-focused Astro components converted from Pine UI templates, optimized for the AHA stack (Astro + HTMX + Alpine.js):

### Available Components:
- **HeroSideBySide**: Side-by-side hero layout with text and image
- **HeroCentered**: Centered hero section with optional image below  
- **HeaderWithNav**: Complete header with navigation and hero content
- **HeaderDark**: Dark-themed header with gradient background and newsletter signup

### Usage:
```astro
---
import { HeroSideBySide, HeaderWithNav } from '@/components/pine-marketing';
---

<HeaderWithNav
  logo="Your Brand"
  navItems={[
    { text: "Home", href: "/", active: true },
    { text: "Features", href: "/features" }
  ]}
  heroTitle="Start Crafting Your Next Great Idea"
  heroDescription="Simplifying the creation of landing pages..."
  primaryButtonText="Get Started"
  primaryButtonHref="#start"
/>
```

For detailed documentation and examples, see `/src/components/pine-marketing/README.md`.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
