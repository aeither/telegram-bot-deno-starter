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

# Deploy

Use Deno deploy to connect to Github repo.

Setup with webhook to listen Telegram

```
deno task commands
```
