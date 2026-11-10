SOLDOTNA PART 91 SUBPART A — INTERACTIVE PWA PROTOTYPE (V2)

CONTENTS
index.html          Main responsive PWA
app.js              Ten-scene logic, seven additional airport discoveries
styles.css          Mobile/iPad responsive styles
manifest.webmanifest, sw.js  Installability and offline caching
assets/             Cropped artwork that avoids the defective AI-rendered propeller
source/part91-2026-11-05.pdf  User-supplied Part 91 regulatory reference

QUICK START (MAC OR PC)
1. Extract this ZIP.
2. In Terminal, go to the extracted soldotna_pwa_v2 folder.
3. Run: python3 -m http.server 8000
4. Open http://localhost:8000 in your browser.

PHONE / IPAD
A PWA must be hosted securely (HTTPS) for service-worker offline access
and home-screen installation on a phone/tablet. Upload this folder's
CONTENTS to a static HTTPS hosting service. On iPhone/iPad, open the
hosted URL in Safari and use Share > Add to Home Screen. On supported
Android browsers, use Install app / Add to Home Screen.

A separate single-file browser preview (Soldotna_Microlearning_Preview.html)
is included outside the ZIP. It works from a local file and does not need
hosting, but is not itself an installable PWA.

SCOPE AND SAFETY
This is a visual instructional prototype. The flight and the example
aircraft weight limit are fictional. Subpart A is covered through ten
core scenes and seven optional Airport Discoveries. Relevant exact
regulatory excerpts and the source PDF are available inside the app.
Not flight planning guidance, legal advice, or a substitute for current
regulations, aircraft-specific limitations, maintenance documentation,
or instructor judgment.

ARTWORK NOTE
Earlier generated C172 artwork depicted the propeller inconsistently.
This app avoids those propeller areas by cropping source illustrations.
An approved, accurate C172 character/aircraft master illustration is
still needed before a production release.
