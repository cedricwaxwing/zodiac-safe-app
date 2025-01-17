# Zodiac Safe App

The Zodiac Safe app let's you deploy and manage modules and Guards for your Gnosis Safe. You can find the Zodiac Safe app in the [Gnosis Safe UI](https://gnosis-safe.io/app/#/), or you can run it locally by following the instructions below.

## Getting Started

Install dependencies and start a local dev server.

```bash
yarn install
cp .env.sample .env
# fill in details in .env
yarn start
```

Then:

- If HTTPS is used (by default enabled)
  - Open your Safe app locally (by default via https://localhost:3000/) and accept the SSL error.
- Go to {Gnosis Safe web UI](https://gnosis-safe.io/app/#/)
- Create your safe
- Go to Apps -> Manage Apps -> Add Custom App
- Paste your localhost URL, default is https://localhost:3000/
- You should see Safe App Starter as a new app
- Develop your app from there

## Features

- Deploy deploy and enable modules for your Gnosis Safe
- Cost effective module deployment using the Zodiac module proxy factory
- Enable custom modules
- Transaction builder to batch module transactions
