# PharmaChain Backend (Demo)

Simple Express server used for demo. Data is stored in `data.json` in the same folder.

Run (PowerShell):

```powershell
cd server
npm install
npm start
```

API endpoints:
- GET /api/batches
- GET /api/batches/:id
- GET /api/iot-readings?batchId=BTCH-2024-001
- POST /api/iot-readings  (JSON body: batchId, temperature, pressure, gpsLat, gpsLon)
- GET /api/alerts
- GET /api/transactions?batchId=...
- POST /api/transactions (JSON body: batchId, from, to, location)
