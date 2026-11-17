CAFÉGO - LABORATORY ACTIVITY 10

1. Open this folder in VS Code.
2. Open a terminal in this folder.
3. Run: npm.cmd install
4. Run: npm.cmd run build
5. Run: npm.cmd run preview
6. Open the local URL printed by Vite in Google Chrome.

Important:
- The service worker/PWA should be tested with the production preview, not just npm run dev.
- Open the app while online first so /api/products.json can be cached.
- Then use Chrome DevTools > Network > Offline and reload.
- For the update prompt test, keep the preview tab open, change a visible heading in src/App.jsx, run npm.cmd run build again, then refresh the preview tab.

This project is a learning starter. Read and understand the configuration and write your own lab explanations based on your actual tests.