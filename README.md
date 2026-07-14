# NDC Election App — Local Working Directory

Static, self-contained HTML mockups. No build step, no dependencies — just open the files in a browser.

## Files
- `index.html` — Voter-facing app (verification → facial recognition → OTP → ballot → review → submit → results)
- `admin.html` — Admin portal (live dashboard, positions & candidates, voter data import/roster, elections control, user admin/roles)

## Run locally
Just open either file directly in a browser, or serve the folder:

```
npx serve .
```

then visit http://localhost:3000/index.html or /admin.html

## Deploy to GitHub Pages
1. Push this folder's contents to your repo (e.g. `git add . && git commit -m "Add election app" && git push`)
2. In GitHub: Settings → Pages → Source: "Deploy from a branch" → main → /(root)
3. Visit `https://<username>.github.io/<repo>/index.html` and `/admin.html`

## Notes
These are design mockups with simulated data and interactions (no real backend, camera, or SMS). Demo login: membership ID `NDC-208441`, any date of birth, any 6-digit OTP.
