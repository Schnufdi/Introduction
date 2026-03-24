# SIGNAL — Business Intelligence Engine

## Setup

```bash
npm install
ANTHROPIC_API_KEY=your_key_here npm start
```

Then open http://localhost:3000

## Deploy to Railway / Render / Fly.io

Set the `ANTHROPIC_API_KEY` environment variable in your platform's dashboard, push the folder, done.

## Files

- `index.html` — the full client app
- `server.js`  — Express proxy to Anthropic API
- `package.json`
