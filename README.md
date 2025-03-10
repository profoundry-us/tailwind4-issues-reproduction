# Tailwind 4 - HAML Parsing Issues

This is a very small project to reproduce some HAML parsing issues in the new Tailwind 4 Insiders package.

## Setup

1. Run `yarn install`
2. Run `yarn run build:css`
3. Verify that there are some classes used in the `home.html.haml` file that do not
   appear in the `build/application.css` file.

## Missing Classes

- `mt-24` - Used near the bottom of the page
