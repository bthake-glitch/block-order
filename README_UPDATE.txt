BT Block Order v3.3 Yellow/Black Icon Fix

Fix:
- Uses NEW icon filenames: icon-yellow-192.png and icon-yellow-512.png.
- Manifest points to the new icon filenames so Chrome cannot keep using the old cached icon.
- Old icon filenames are also overwritten for compatibility.

Upload/replace ALL these files:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- icon-yellow-192.png
- icon-yellow-512.png

Important:
If the Home Screen icon still shows the old one after uploading:
1. Remove the old BT Block Order shortcut/app icon from your phone Home Screen.
2. Open https://bthake-glitch.github.io/block-order/ in Chrome.
3. Refresh.
4. Add to Home Screen again.
Android often does not update an already-installed PWA icon until it is re-added.
