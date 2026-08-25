# Work Hours & Pay Tracker...

Upload these files to the root of your GitHub repository:

- index.html
- manifest.webmanifest
- sw.js
- .nojekyll

Then go to **Settings → Pages → Deploy from a branch**, select **main** and **/(root)**, and save.

The app stores worked days and settings in the browser using local storage, so data stays on the same device/browser. It does not automatically sync between devices.

The tax calculation is an estimate rather than a full UK PAYE payroll calculation.
