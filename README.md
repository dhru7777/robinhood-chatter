# Robinhood Chatter & Sentiment

Before/After prototype with live Polygon prices and a Cortex-style chatter UI.

## Run locally

```bash
cp .env.example .env   # add POLY_API_KEY
npm start
```

Open http://localhost:3000

## Deploy (Render)

1. Open the Blueprint: https://dashboard.render.com/blueprints/new?repo=https://github.com/dhru7777/robinhood-chatter
2. Apply `render.yaml`
3. When prompted, set **POLY_API_KEY** (Polygon API key)
4. Deploy the `robinhood-chatter` web service

Local: `npm start` → http://localhost:3000  
Config: `render.yaml` (Node web service, health check `/api/health`)
