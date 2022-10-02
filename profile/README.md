## SHARDS framework

Idea behind this framework is to have a JSON data that represent structure of the page - **shell**.

- **Shell** will contain **shards** as an atomic peaces of structure that render data.
- **VueJS** is going to be used as framework to do actual frontend rendering.
- **Bootstrap** is going to be used as a grid and style framework.

## Pilot release

All packages will start with 0.1 versioning to represend not stable, Pre release state of coding.

First release goals:
- bootstrap wrapper to use CSS variables to colour all elements, so new color schemas can be loaded as set of CSS vars
- basic replacement for bootstrap.js via Vue components with similar functionality
- tools to render static pages based on JSON configs.
- Visual editor fo JSON generation to speed up development
- color scheme generation based on bootstrap scss
- minimal set of shards to be used to generate JSON
 
