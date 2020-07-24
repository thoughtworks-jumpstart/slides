# slides

## Getting started

Clone the repository and install all dependencies

```sh
npm install
```

## Create a new deck

Within the `src` folder, select or create a new folder for a topic (e.g. `git`, `javascript`, `react`) and create a Markdown file for your deck (e.g. `react.md`).

Next, create a link to your deck in `index.md` so that it's easily accessible from the main page. Be sure to follow the format `deck/{topic}/{title}.html` (e.g. `[React]("deck/react/react.html")`).

## Preview your deck

To view your deck locally, run `npm run build` and then use a local development server like `serve` to
