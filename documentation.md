# Documentation

**The contents from /docs will be overwritten when linked with github**.

You can specify some options for each build in the file `/docs/config.json`. It will be generated with some parsed data the first time you run Repository:

```json
{
  "title": "Superdom",
  "subtitle": "Manipulate the DOM like it's 2016",
  "background": "#58a2df",
  "logo": "public/logo.png",
  "documentation": "documentation/readme.md",
  "nav": {
    "https://github.com/franciscop/superdom/issues": "Issues",
    "https://github.com/franciscop/superdom": "Github",
    "/franciscop/umbrella/documentation/": "Documentation",
  }
}
```
