# SAFUHANDS · SAFU之手

A single-page black-and-gold 3D experience, with Chinese as the default language and an English switch. The scene features the supplied textured gauntlets, a golden portal, architectural columns, a stepped platform, bloom and interactive effects.

## Run locally

Requires Node.js 20 or later. No installation or build step is required.

```sh
npm start
```

Open http://localhost:3000. Set `PORT` to choose another port. Any static host can alternatively serve the contents of `dist/` directly.

```sh
npm run check
```

## Files

- `dist/index.html`, `dist/style.css` — layout and styling.
- `dist/ui.js` — Chinese/English copy, language selection and wallet copying.
- `dist/scene.js` — Three.js scene, lighting, model loading and interaction.
- `dist/assets/gauntlets-optimized.glb` — optimized supplied model, approximately 1.31 MB, using Meshopt compression and WebP textures.
- `dist/assets/` — locally hosted fonts, original fist artwork, logo and favicon.
- `dist/vendor/` and `dist/three.module.js` — locally hosted rendering dependencies.
- `server.mjs` — dependency-free Node.js static server.

## Project status

This is a pre-launch community concept, not a deployed token or smart contract. The displayed planned buy and sell fees are 3% and 5%. The designated fee recipient is `0x420ef1f25563593af5fe3f9b9d3bc56a8bd8c104`, an address published in the [official Binance SAFU FAQ](https://www.binance.com/en/support/faq/detail/028799e730294ae4a9b382d60d350116). The site includes the source and a BNB Chain explorer link; it does not execute transfers.

The project is independent and is not affiliated with or endorsed by Binance or SAFU.

## Third-party code

Three.js is distributed under the MIT license; see `THIRD_PARTY_NOTICES.md`. The bundled Meshopt decoder includes its own MIT license notice. Supplied artwork and models are not covered by those third-party software licenses.
