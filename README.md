# Cheese Chompers 3D

A browser build of Cheese Chompers 3D with a branded loading screen and StaticQuasar931 page metadata.

## GitHub Pages

The GitHub Actions workflow deploys `index.html` and the local `Build/` files from the `main` branch. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.

Keep all split `.part` files in `Build/` together. The page assembles the game data and WebAssembly files locally before starting Unity. No Google Analytics is included.
