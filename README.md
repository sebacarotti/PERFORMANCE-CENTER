# Performance Center - PWA shell

Questa cartella contiene il contenitore installabile per Performance Center.

File:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

Prima della pubblicazione:
1. Apri index.html.
2. Sostituisci PASTE_YOUR_APPS_SCRIPT_WEB_APP_URL_HERE con il link pubblico della Web App Google Apps Script.
3. Carica tutti i file nella root del repository GitHub.
4. Attiva GitHub Pages sul branch main, cartella /root.

La dashboard Google Apps Script deve consentire l'apertura in iframe.
Nel Code.gs attuale è già presente XFrameOptionsMode.ALLOWALL.
