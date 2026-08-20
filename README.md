# BB13 - Black Barrio 13

Gang management website for FiveM RP.

## Tech Stack
- **Frontend**: React 18 + Vite
- **Backend**: Node.js + Express
- **Database**: SQLite (sql.js)
- **Auth**: JWT

## Deployment

### Frontend (Vercel)
1. Push to GitHub
2. Go to vercel.com → Import Project
3. Select the `client/` directory as root
4. Set environment variable: `VITE_API_URL=https://your-backend-url.com`
5. Deploy

### Backend (Render/Railway)
1. Create account on render.com or railway.app
2. Create a new Web Service
3. Set root directory to `server/`
4. Build command: `npm install`
5. Start command: `node index.js`
6. Set environment variables:
   - `PORT=5000`
   - `JWT_SECRET=your_secret_key`
   - `CORS_ORIGIN=https://your-vercel-app.vercel.app`
   - `DISCORD_WEBHOOK_URL=your_webhook_url`

## Local Development

```bash
# Backend
cd server
npm install
node index.js

# Frontend (new terminal)
cd client
npm install
npm run dev
```

Frontend runs on port 3000, backend on port 5000.

## Admin Access
- Username: `admin`
- Password: `admin13`
