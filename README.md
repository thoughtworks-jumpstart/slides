# slides

## Getting started

Clone the repository and install all dependencies

```sh
npm install
```

## Create a new slide deck

Within the `src` folder, select or create a new folder for a topic (e.g. `git`, `javascript`, `react`) and create a Markdown file for your deck (e.g. `react.md`).

## Build your slide deck in watch mode

It is recommended that you run `npm run build:watch` so you can build your slide deck in watch mode to ensure that your slides are always built before you commit them.

## Update the index page

Create a link to your deck in `index.md` so that it's easily accessible from the main page. Be sure to follow the format `topics/{your-topic}/{your-title}.html` (e.g. `[React]("topics/react/react.html")`).

## Preview your deck

To view your deck locally, run `npm run start` - this will run the build and serve your slides on localhost:5000 then navigate to your slide deck.
