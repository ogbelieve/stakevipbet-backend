
# StakeVipBet Backend

This is the backend API for StakeVipBet.

## Setup

```bash
npm install
node index.js
```

## Deployment Notes (Render)
- **Build command**: `npm install`
- **Start command**: `node index.js`

## Routes

### Public
- GET `/matches`

### Admin (with header `x-secret-key: stakevip_secret_2025`)
- POST `/admin/match`
- PUT `/admin/match/:id`
