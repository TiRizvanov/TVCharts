# React Chart Example

This example app shows how to use the `lightweight-charts` library with a backend API.

The library version included here uses the new `addSeries` API instead of the
deprecated `addCandlestickSeries` helper.

## Setup

```bash
npm install
cp .env.example .env
npm run dev
```

Create a `.env` file to configure the backend:

```ini
VITE_API_URL=https://chart-widget-backend-production.up.railway.app/api
```

The example uses this API URL by default if `VITE_API_URL` is not set.

The chart loads historical data from the backend deployed at `https://chart-widget-backend-production.up.railway.app` for chart `1766151d-f972-42ac-bbb6-d31579f80dc2`.
