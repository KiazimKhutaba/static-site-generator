## Static Site Template Generator

This template can be used for generation simple static site.

### Tools:

- Parcel
- Nunjucks
- SCSS
- TypeScript


Nunjucks templates resides in **template** dir - root dir for pages.
So all actual site pages should be placed in **src/template folder**.

- **src/templates/data/\*.njk** - contains in Nunjucks variables data for pages
- **src/templates/macro/\*.njk** - various reusing macroses
- **src/templates/partials/\*.njk** - base *layout.njk* and other partials
- **src/scss** - SASS styles
- **src/images** - static images

If needed, entry point file can be changed to another or wildcard 
can be used in **package.json -> scripts** section.

### Run

```bash

$ yarn dev # for development

$ yarn build # to build pages in ./dist folder

```

