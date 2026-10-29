WABASH VALLEY COLLEGE REHABILITATION SERVICES — PTA EMR SIMULATOR
UNOFFICIAL EDUCATIONAL SIMULATOR — PWA INSTALLATION GUIDE

CONTENTS (KEEP THESE FILES TOGETHER)
  index.html             Main simulator, including encounter library and note exports
  manifest.webmanifest   App name, icon, and installation metadata
  sw.js                  Offline cache/service worker
  icon-192.png           App icon
  icon-512.png           App icon
  README.txt             These instructions

IMPORTANT: Downloading this ZIP or opening index.html from Files/Downloads
DOES NOT INSTALL THE PWA. To enable installation and offline caching,
serve the files from an HTTPS website (or localhost for testing).

EASIEST DEPLOYMENT: GITHUB PAGES
1. Download this ZIP, then extract/unzip it.
2. Create a free GitHub account at https://github.com if needed.
3. Create a new repository, e.g. wvc-pta-emr. For standard free GitHub
   Pages hosting, make the repository PUBLIC. Do not upload real patient data.
4. Open the repository, choose Add file > Upload files, and upload ALL SIX
   extracted files to the ROOT of the repository (not inside a nested folder).
5. Commit the files.
6. In repository Settings > Pages, select Deploy from a branch, branch
   main, folder /(root), then Save.
7. Wait a few minutes for the site to deploy. The site URL normally looks
   like https://YOUR-USERNAME.github.io/wvc-pta-emr/
8. Open that HTTPS URL and verify the Encounter Library loads.

INSTALL ON DEVICES (AFTER HOSTING)
  iPhone/iPad: Open site in Safari > Share > Add to Home Screen > Add.
  Android: Open in Chrome > menu > Install app or Add to Home screen.
  Chromebook: Open in Chrome > Install icon in address bar, if offered,
              or menu > Install page as app.
  Windows: Chrome/Edge > Install icon or menu > Apps > Install this site.
  Mac: Safari > File > Add to Dock (supported versions) or Chrome > Install.
  Exact labels vary by browser version. If installation is not offered,
  confirm the page is HTTPS and refresh after deployment.

OFFLINE USE AND UPDATES
  Visit the hosted app while online at least once. The service worker then
  caches app files for subsequent offline use. Browser storage/cache can be
  cleared by the device or user; offline operation is not guaranteed forever.
  To update, upload replacement files to the SAME hosting path, including
  the updated sw.js. Reopen the app online and refresh. The home-screen app
  may need to be reopened to pick up the update.

ENCOUNTER LIBRARY AND BACKUPS
  Encounter Library > New Encounter creates another fictional case.
  Encounters auto-save locally on the CURRENT browser/device. They do NOT
  sync across devices or accounts, and installed PWA storage may differ
  from browser storage on some platforms.
  Use Encounter Library > Backup entire library to save an editable JSON
  backup. Use Restore library to import it. Also export a printable note
  separately for Canvas. PDF/Word notes are NOT editable encounter backups.
  Before switching from an old HTML version, export its chart/library backup
  and import it into the hosted PWA. Deployment does not migrate browser data.

PRINTING / CANVAS
  Review & Export > Print / Save PDF uses your device print dialog.
  Or download Word (.doc), text, or printable HTML and upload to Canvas.
  For PDF: choose Print > Save as PDF (desktop) or the device's PDF sharing
  or save-to-files option. PDF options vary by browser and OS.

PRIVACY AND SCOPE
  FOR FICTIONAL OR FULLY DE-IDENTIFIED CASES ONLY. No HIPAA-compliant
  storage, authentication, encryption, clinical signatures, or cloud sync.
  Do not put actual patient names, dates of birth, or PHI in this simulator.
  This is not an official Wabash Valley College, Epic, or WebPT product.
