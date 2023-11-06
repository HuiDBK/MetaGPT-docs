# Prerequisites

- [Node.js](https://nodejs.org/en) version 18 or higher.
- Text Editor with [Markdown](https://en.wikipedia.org/wiki/Markdown) syntax support.
  - [VSCode](https://code.visualstudio.com/) is recommended, along with the [official Vue extension](https://marketplace.visualstudio.com/items?itemName=Vue.volar).

# Up and Running

follow steps below to start the dev server

1. `corepack enable pnpm` to use pnpm

2. `pnpm i` to install dependency

3. `npm run docs:dev`

The dev server should be running at http://localhost:5173. Visit the URL in your browser to see your new site in action!

# file structure

```text
 ├─ src
 | ├─ blog        # blog file  /blog/xxx
 | ├─ guide       #  /guide/xxx
 | ├─ rfcs        #  /rfcs/xxx
 | ├─ public      #  you can put resource here
 | ├─ utils       # some utils
 | ├─ index.md    # home page;
```