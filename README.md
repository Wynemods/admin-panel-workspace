# Moto Rides Admin Panel

This folder is the **workspace root** for the admin UI. Application source lives in the `frontend/` submodule.

## Clone (fresh)

```bash
git clone --recurse-submodules https://github.com/Wynemods/ADMIN-PANEL-WORKSPACE.git
cd Admin-Panel-WORKSPACE   # or your folder name
cd frontend
npm install
cp .env.example .env
npm start
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Submodule

| Path | Remote |
|------|--------|
| `frontend/` | https://github.com/Wynemods/ADMIN-PANEL.git |

Day-to-day app work happens inside `frontend/` (commits push to `ADMIN-PANEL`). Update the parent repo when you want to pin a new submodule commit for the team.

## Local API

Point `REACT_APP_API_URL` at your backend (e.g. `http://localhost:3000` for dev, `https://api.motorides.app` for production).
