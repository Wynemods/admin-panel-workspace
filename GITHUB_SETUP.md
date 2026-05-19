# Push this workspace to GitHub (one-time)

Create **two empty public repos** under [Wynemods](https://github.com/Wynemods) (no README, no .gitignore):

| Local folder | GitHub repo name | Remote already configured |
|--------------|------------------|---------------------------|
| `Admin Panel/` | `admin-panel-workspace` | `origin` → `https://github.com/Wynemods/admin-panel-workspace.git` |
| `Google frontend/` | `motorides-google-frontend-workspace` | `origin` → `https://github.com/Wynemods/motorides-google-frontend-workspace.git` |

Then from each folder:

```powershell
cd "c:\Users\User\OneDrive\Desktop\MOTO RIDES PROJECT\Admin Panel"
git push -u origin main

cd "c:\Users\User\OneDrive\Desktop\MOTO RIDES PROJECT\Google frontend"
git push -u origin main
```

## App code (unchanged remotes)

| Submodule | Pushes to |
|-----------|-----------|
| `Admin Panel/frontend/` | https://github.com/Wynemods/ADMIN-PANEL.git |
| `Google frontend/Frontend/` | https://github.com/Wynemods/Moto-rides-deletion-page.git |

Work inside the submodule for feature changes; commit the parent when you want to pin a submodule SHA for the team.
