# Moss & Rain Grove

A procedural, cozy animated canvas scene built with HTML5 Canvas 2D and the Web Audio API.

## Features
- **3-Pass Multi-Pass Shading**: Contact crevice shadow, textured base body with cluster dithering, and directional edge bevel highlight.
- **Universal Spatial & Collision Contract**: Obstacles declare physical footprints, actors anchored at ground-contact feet (0.5, 1.0), dynamic Y-depth sorting (`zIndex = entity.y`), and closed-loop sliding navigation.
- **Procedural Rain Audio**: Stereo wide-spectrum rain hiss and stochastic Poisson droplet splatters synthesized via the Web Audio API.
- **Interactive Controls**: Rain intensity, atmospheric lighting (Overcast Day vs. Lantern Twilight), pace presets (1.0x, 0.5x, 0.35x), and click-to-splash.

## Deployment on GitHub Pages
1. Push this repository to GitHub.
2. In your repository on GitHub, open **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` branch and `/ (root)` folder.
4. Click **Save**. Your site will be live at `https://<username>.github.io/<repo-name>/`.
