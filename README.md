# Blog Customizer

Blog Customizer is a React and TypeScript application with a settings panel for changing the appearance of an article.

The project focuses on form state, applied settings and interaction between UI controls and CSS variables.

## Features

- collapsible settings panel;
- article style customization;
- separate form state and applied state;
- reset to initial settings;
- CSS-variable-based styling;
- click-outside behavior for closing the panel.

## Tech stack

- React
- TypeScript
- SCSS
- Webpack
- Storybook
- ESLint
- Stylelint
- Prettier

## Getting started

Clone the repository and install dependencies:

```bash
git clone https://github.com/alexeydev42/blog-customizer.git
cd blog-customizer
npm install
```

Start the development server:

```bash
npm start
```

Storybook can be started separately:

```bash
npm run storybook
```

## Useful commands

```bash
npm start
npm run build
npm run lint
npm run stylelint
npm run storybook
```

## About the project

This project was completed as part of the Yandex Practicum Frontend Developer program.

The starter project already contained the base UI components and styling setup. My work focused on implementing the settings form behavior, managing form and applied state separately, and connecting user-selected options to the article appearance.
