# find.stellarvector.be

The link hub for Stellar Vector.

Chrome, tokens and shared components come from `github.com/stellarvector/theme`; read its README before adding a component here.

## Running locally

1. Install Hugo (extended version, >= 0.165.0) and Node.js.
2. Run `npm ci` to install dependencies.
3. Run `hugo server`.
4. Go to http://localhost:1313/

The theme is pulled in as a Hugo module. Run `hugo mod get -u github.com/stellarvector/theme` to update it.

## Ownership

| Concern | Source of truth |
|---|---|
| Links data (`data/links/`) | This repository |
| Reveal animations and brand tones | This repository |
| Chrome, tokens, and base behavior | Shared Hugo module |
