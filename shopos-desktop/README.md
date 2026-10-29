# ShopOS Desktop (Windows offline POS prototype)

Electron desktop app with local SQLite database. No browser, internet or cloud account required after installation. USB barcode scanners operating as keyboard input are supported. Includes products, stock, checkout, receipts, sales history, and database backup.

## Build on Windows
Install Node.js LTS, then open PowerShell in this folder:

```powershell
npm install
npm start
npm run dist
```

The Windows installer should appear in `dist`. This build has not been tested on the shopkeeper's machine. Native module compatibility may require rebuild; verify before use. The database lives in Electron's userData directory; use the Backup button regularly. Do not use as the shop's official POS until hardware, power-loss, data recovery, taxes, and receipt formatting are tested.
