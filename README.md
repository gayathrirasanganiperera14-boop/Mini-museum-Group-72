# Mini Museum Exhibit – Marker-Based AR (A-Frame + AR.js)

**Group:** 72  |  **Members:** G.G.R.Perera, W.G.S.Sithmina, W.V.Sathsara, N.M.R.S.G.B.H.B.Karunarathne, M.G.D.A.Nanayakkara

## Live demo (HTTPS)
https://gayathrirasanganiperera14-boop.github.io/Mini-museum-Group-72/

## What it does
Point your camera at the Hiro marker to see a mini museum exhibit: a spinning 3D model on a plinth,
a bouncing ball (tap to change colour), a cone (tap to grow/shrink) and a text label.
A banner at the top turns green when the marker is found and red when lost.

## Requirements checklist
- [x] Hiro marker scene: plane, cylinder, sphere, cone, glTF model + `<a-text>` label
- [x] Animations: rotation (model), position (ball), scale (plinth)
- [x] glTF model: see credit below
- [x] Interaction: `color-changer` (workshop) + `tap-grow` (own custom component)
- [x] Status banner: `marker-status` component
- [x] Hosted over HTTPS and tested on a phone

## Model credit & licence

- **Title:** King's Crown
- **Author:** [MishaCho](https://sketchfab.com/MishaCho)
- **Source:** [King's Crown on Sketchfab](https://sketchfab.com/3d-models/kings-crown-aaed331d49fe41bba494cb0cd2ee80a0)
- **Licence:** [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)
- **Use in this project:** The model is scaled and animated in the AR scene.

## Tools
A-Frame 1.3.0, AR.js 3.4.5

## How to run
Open `index.html` with VS Code Live Server (localhost), or visit the live link on a phone and allow the camera.
