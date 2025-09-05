# Insta Kitchen — Flat Vite + React

This version is **flat at repo root** and uses a **relative import** (`./src/main.jsx`) to avoid the Rollup error you saw on Vercel.

## Deploy on Vercel (Git)
1) Push these files to your GitHub repo **at the root** (no extra folder).
2) In Vercel → New Project → Import Repo.
3) Confirm:
   - Framework: Vite
   - Build: `vite build`
   - Output: `dist`
4) Deploy.

## Local Dev
npm install
npm run dev
