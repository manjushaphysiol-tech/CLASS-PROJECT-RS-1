# Mechanics of Breathing: 3D Navigation Map

An interactive 3D model of the thorax that simulates inspiration and expiration, built from the lecture deck "Mechanics of Breathing" by Dr. Manjusha Shinde, AIIMS Kalyani.

- Nine stations: airways, diaphragm, rib cage, accessory muscles, pleural sac, alveoli, transmural pressures, Boyle's law, elastic recoil and compliance
- Quiet and forced breathing, with live pressure readouts and cycle traces
- Step-by-step sequence of events and a three-question self-check

## Files

The whole site is one file, `index.html`. It loads three.js (r128) from cdnjs and IBM Plex fonts from Google Fonts, so viewers need an internet connection. There is no build step.

## Host on GitHub Pages

1. Create a new public repository on GitHub, for example `breathing-mechanics-3d`.
2. Open the repository, choose **Add file > Upload files**, upload `index.html` and `README.md`, and commit.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then save.
5. Wait a minute or two. The site appears at `https://<your-username>.github.io/<repository-name>/`.

## Run locally

Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari). WebGL must be enabled.

## Notes on the numbers

Quiet-breathing values (760/759/761 mm Hg intrapulmonary, 756/754 mm Hg intrapleural, 500 mL tidal volume) come from the lecture deck. Forced-breathing values are illustrative, apart from the −18 mm Hg intrapleural maximum. Cycle timing and the airflow trace are assumptions made for the simulation.

## Copyright

© 2026 Dr. Manjusha Shinde, AIIMS Kalyani. All rights reserved.
