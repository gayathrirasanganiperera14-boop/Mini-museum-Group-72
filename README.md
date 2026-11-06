# Mini Museum

*Group:* 72  |  *Members:* G.G.R.Perera, W.G.S.Sithmina, W.V.Sathsara, N.M.R.S.G.B.H.B.Karunarathne, M.G.D.A.Nanayakkara

## Live demo (HTTPS)
https://gayathrirasanganiperera14-boop.github.io/Mini-museum-Group-72/

## What it does
Point your camera at the Hiro marker to see a mini museum: a spinning 3D model on a plinth,
a bouncing ball, a cone and a text label.
A banner at the top turns green when the marker is found and red when lost.

## Requirements checklist
Hiro marker scene: Framed paintings, cylinder pillars, a dinosaur, a bouncing sphere, and a yellow cone. The `MINI MUSEUM` title is displayed using `<a-text>`.

Animations: The ball bounces up and down using a position animation, and the round display stand pulses using a scale animation.

glTF model: see credit below

Interaction: `color-changer` (workshop) + `tap-grow` (own custom component)

Status banner: `marker-status` component

Hosted over HTTPS and tested on a phone

## Model credit & licence

*Title:* King's Crown

*Author:* [MishaCho](https://sketchfab.com/MishaCho)

*Source:* [King's Crown on Sketchfab](https://sketchfab.com/3d-models/kings-crown-aaed331d49fe41bba494cb0cd2ee80a0)

*Licence:* [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

*Use in this project:* The model is scaled and animated in the AR scene.

## Tools
A-Frame 1.3.0, AR.js 3.4.5

## How to run
Open `index.html` with VS Code Live Server (localhost), or visit the live link on a phone and allow the camera.
