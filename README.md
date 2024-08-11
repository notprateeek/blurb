# [Blurb](https://www.twitterbio.io/)

This project generates bios for you using AI.

## How it works

This project uses [Mixtral](https://mistral.ai/news/mixtral-of-experts/) with streaming to generate a bio. It constructs a prompt based on the form and user input, sends it either to the Mixtral API through [Together.ai](https://www.together.ai/), then streams the response back to the application.

## Running Locally

1. Create an account at [Together.ai](https://www.together.ai/) and add your API key under `TOGETHER_API_KEY`
2. Run the application with `npm run dev` and it will be available at `http://localhost:3000`.

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/notprateeek/blurb&env=TOGETHER_API_KEY&project-name=blurb&repo-name=blurb)
