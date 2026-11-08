YOUNG_S8 — XBOX ONE / GAMEPAD VIEWER — V4

Black, red, and white. Original 750 × 630 layout and input sprites preserved.

CHANGES IN V4
The subtle curved detail lines are restored at both grip tips.
The white shell is clipped along the same curve as the dark grip panels.
The panels extend beyond the inner cutout and use the original controller
silhouette as their final edge, eliminating the pale wedges and outlines.
The white transparent emblem and text-free shell from V2 are retained.
All preview labels, status messages, and documentation are now in English.

OBS INSTALLATION
1. Keep your existing Xbox One Gamepad Viewer Browser source and player URL.
2. Set the source to 750 pixels wide and 630 pixels high.
3. Open young_s8-obs.css, copy the whole file, and paste it into Custom CSS
   in the OBS Browser source. Refresh the source and press a controller button.
All graphics are embedded. No image hosting is needed for this method.
poco98-obs.css is an identical compatibility alias.
The original pack used https://overlay.gamepadviewer.com/loader/index.html?p=1&s=1

EXTERNAL CSS
Host edit.css and all nine .svgz files together on HTTPS, then point
Edit CSS URL to edit.css. Alternatively host young_s8-obs.css by itself.
The .svgz files contain plain SVG, as in the original pack. Serve them as
image/svg+xml without a gzip Content-Encoding header. This pack is not hosted.

LOCAL PREVIEW
Open preview.html. Choose Idle, Active inputs, Demo, Disconnected, or
Live controller. Z/X/C/V map to A/B/X/Y; arrow keys to the D-pad; Q/E to
LB/RB; R/T to LT/RT. The controller graphics also support clicks and touch.
Live input requires a browser with the Gamepad API on localhost or HTTPS.
If Python is installed, run from this folder:
  python -m http.server 8765 --bind 127.0.0.1
Then open http://127.0.0.1:8765/preview.html and press a controller button.
The local preview uses standard browser mapping. Gamepad Viewer retains its
own detection, player selection, and remapping. Physical hardware/OBS testing
was not performed during this revision.

FILES
young_s8-obs.css: self-contained OBS skin.
edit.css + *.svgz: external-asset version.
assets/*.svg: editable source graphics.
assets/young_s8-emblem.svg / .png: white emblem with real transparency.
Preview*.svg / .png: idle, active, and disconnected transparent previews.
Presentation.svg / .png: complete visual comparison.
Grip-edge-comparison.svg / .png: enlarged before/after edge detail.
Grip-detail.svg / .png: close-up of the restored curved grip lines.
CHANGES.md, VALIDATION.md, changes.json: revision notes and verification.
LICENSE.txt: original Dracula Theme MIT license, unchanged.

The channel emblem comes from https://www.twitch.tv/young_s8/about .
The original base license does not change the emblem owner's rights.
