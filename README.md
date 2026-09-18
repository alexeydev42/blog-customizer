# Blog Customizer

Blog Customizer is a React and TypeScript interface for changing the appearance of an article through a settings panel.

The starter project already contained the base UI components and styling. My work focused on the settings behavior, form state and applying user-selected options to the article.

<!-- TODO: Add 1 screenshot here: the article with the settings panel open and several changed options visible. -->

## What I implemented

- opening and closing the settings panel;
- form controls for article appearance;
- separate temporary form state and applied page state;
- reset to initial settings;
- applying settings through CSS variables;
- click-outside behavior for closing the panel.

## Technical decisions

The form state is intentionally separated from the state that is currently applied to the article. This lets users change several controls before applying them and also makes reset behavior predictable.

CSS variables are used as the bridge between React state and the article styling, keeping visual configuration out of the component markup.

The project also uses reusable controls from the provided component set and Storybook for working with UI components in isolation.

## Tech stack

- React
- TypeScript
- SCSS
- Webpack
- Storybook
- ESLint
- Stylelint
- Prettier

## Run locally

```bash
git clone https://github.com/alexeydev42/blog-customizer.git
cd blog-customizer
npm install
npm start
```

Storybook:

```bash
npm run storybook
```

Other useful commands:

```bash
npm run build
npm run lint
npm run stylelint
```

## Project context

This project was completed as part of the Yandex Practicum Frontend Developer program. The prepared UI foundation allowed me to focus on React state, form behavior and connecting application state to visual styles.
