# Rafa Abdul

- [https://RafaAbdul.com](https://RafaAbdul.com)

[![Eleventy Build](https://github.com/sasidhar/rafaabdul/actions/workflows/eleventy_build.yml/badge.svg)](https://github.com/sasidhar/rafaabdul/actions/workflows/eleventy_build.yml)


## Getting Started

Navigate to the root folder of the site and run:

```
npm install
```

To run the development environment:

```
npm run dev
```

To build for production:

```
npm run build
```
For additional eleventy commands, visit the [Eleventy command line usage page](https://www.11ty.dev/docs/usage/).

## Editing Styles
Edit and amend as needed. The main Sass files are under the `/assets` folder.
### Sass Folder Structure
```
src
  /assets
    /styles
      /scss
        /base
        /components
        /utility
        main.scss
```
The development environment watches for changes to the Sass files and pushes changes to `main.css` in the `/includes` folder. Eleventy then pushes the styles inline in the `<head>` of the base page template.

