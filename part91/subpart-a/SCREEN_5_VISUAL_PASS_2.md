# Screen 5 — Visual Pass 2 (development branch)

## Design change
- Replaces the old cropped illustration on Screen 5 with a close inspection view of Maya, Alex, and the C172-style wing strut.
- Adds a pulsing, keyboard-accessible hotspot directly over the suspected crack on the artwork.
- Offers an alternative “Inspect the strut” control in the lesson pane.
- On click, reveals an enlarged image clearly showing a branching dark line resembling a crack, along with explanatory guidance anchored to § 91.7.
- Keeps Continue disabled until inspection; maintains the original learning progression and all other screens.
- Supports reduced-motion settings and responsive positioning of the hotspot.

## Files changed
- `assets/scene-05.webp` (replaced)
- `assets/scene-05-crack.webp` (new)
- `app.js` (Screen 5 content and artwork interaction)
- `styles.css` (target, zoom, accessibility)
- `index.html` (development version label)
- `sw.js` (new image in cache; version bump)

## Teaching caveat
- The scene and magnification are illustrative AI-generated images, not evidence from an actual aircraft.
- The illustrated line is a **suspected crack**. Assessment of damage and return-to-service status require appropriate evaluation.
- A current annual inspection does not supersede § 91.7 condition and PIC responsibility requirements.

## Acceptance criteria
1. Other nine screens retain previous behavior.
2. Screen 5 shows people and suspected fitting in its wide image.
3. Learner can click the pulsing circle or the text/button alternative.
4. Crack zoom reveals in large scale, clearly visible (not cropped off).
5. Continued flight remains disabled before interaction, enabled afterward.
6. FAA reference panel for §§ 91.7 and 91.3 continues to work.
7. Reduced-motion settings disable the pulse/entrance animation.
8. Does not modify `main` until the change is approved.

## Remaining follow-up
The generated Screen 5 artwork is photorealistic while other scenes use painterly illustrations. Consider commissioning a matched-style illustration after we confirm the close-up interaction teaches as intended. Cockpit seating correction for Screens 3 and 8 is a separate upcoming task.
