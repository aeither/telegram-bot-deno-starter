# Telegram Bot

Deno Deploy + Grammyjs

# Install

```
brew install deno
```

# Run

with tasks

```
deno task task-name [additional args]
```

or without

```
deno run --allow-net --allow-env bot.ts
```

# Run Webhook locally

```
deno task start:bot
```

```
ngrok http 8000
```

# Deploy

Use Deno deploy to connect to Github repo.

Setup with webhook to listen Telegram.
Update commands and PROJECT_URL in scripts/index.ts.

Make sure to not add / at the and of url.
`const PROJECT_URL = 'https://projectname.deno.dev'`

```
deno task commands
```
