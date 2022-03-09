# Guide for using Boilerplate

## Prerequisites

1. [Git](https://git-scm.com/)
2. [Node.js](https://nodejs.org/)
3. [npm](https://www.npmjs.com/)
5. [GitHub](github.com) _[Optional]_

Before you can use this boilerplate, you need to follow the steps below.
<br>Clone the repository to your project folder.

```
git clone https://github.com/imgul/Frontend-Project-Boilerplate.git
```

## Favicon

Prepare icons accorging to [/assets/img/favicon/icons.md](./assets/img/favicon/icons.md) guidelines. Put these icons in `/assets/img/favicon/` folder.

## NPM

1. Install & start npm.
npm guide <https://docs.npmjs.com/getting-started/installing-node>

```
npm init
```

## SASS/SCSS

1. Install & start SASS from npm.
2. Download SASS Boilerplate using.
SASS Commands here: <https://sass-lang.com/documentation/installation>

```
npm install sass
sass --watch src/sass/main.scss:dist/css/main.css
git clone https://github.com/imgul/sass-boilerplate.git sass
```

## Autoprefixer

```
npm i autoprefixer
npm install postcss postcss-cli autoprefixer
npx postcss dist/css/main.css --use autoprefixer -d dist/css/
```

## Tailwind CSS

```
npm install -D tailwindcss
npx tailwindcss init
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

## REACT

## Markdown Guide

1. `Ctrl+Shift+V` Markdown preview in VS Code.
