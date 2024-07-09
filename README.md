# Frog.fm / bun.sh / Airstack hub – Frame Starter app

> A basic starter scaffold from Frog.fm with Airstack hub preinstalled.

## Installation

## Prerequisites

-   bun.sh

```bash
curl -fsSL https://bun.sh/install | bash
```

> Linux / MacOS

```bash
powershell -c "irm bun.sh/install.ps1 | iex"
```

> Windows

## Install

1. Git clone the repo and copy `env.example` to `.env`

```bash
gh repo clone skullzarmy/frog-airstack-starter
bun install
cp .env.example .env
```

2. Edit `.env` and set `AIRSTACK_API_KEY`
3. `bun run dev`
4. Visit `http://localhost:5173/dev` in the browser to view the local debug tool from Frog.
5. Edit `src/index.tsx` and enjoy!
