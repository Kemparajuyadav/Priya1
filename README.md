# PriyaElectrical — local dev

Simple scaffold to run a React dev server with Vite.

Commands (PowerShell):

```powershell
npm install
npm run dev
```

How to use your original code:
- Replace `src/App.jsx` with your React component file (the code you inspected earlier).
- Update environment variables by copying `.env.example` to `.env` and filling your Firebase config string in `VITE_FIREBASE_CONFIG`.
- In your code, use `import.meta.env.VITE_FIREBASE_CONFIG` and `import.meta.env.VITE_APP_ID` instead of the `__...` placeholders.

Notes:
- You need Node.js and npm installed.
- After `npm run dev` Vite will show a local URL (e.g. http://localhost:5173) — open it in your browser.
