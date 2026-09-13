# Admin-User

Simple admin & user login/dashboard app — Node.js, Express, MongoDB.

## Run Locally

```bash
git clone https://github.com/Jahanad-pr/Admin-user.git
cd Admin-user
npm install
npm run nur
```

Make sure MongoDB is running and your connection string is set (check `app.js`).
Visit `http://localhost:3000`.

## Deploy

Needs a Node host (not static hosting) — e.g. **Render** or **Railway**:
1. Connect the repo
2. Build: `npm install`
3. Start: `node app.js`
4. Add your MongoDB URI as an environment variable
