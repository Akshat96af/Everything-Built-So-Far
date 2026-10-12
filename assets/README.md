# README assets

The showcase uses repository-local images, so its appearance is versioned with the README and does not depend on an image host or badge generator being available.

- `previews/` contains the original project images downloaded from the previous README, plus a screenshot of the Solitaired landing page.
- `ui/` contains the new static SVG header, footer, and action buttons, plus the downloaded technology icons.
- `projects.json` records project content and the colour used for each action button. When changing a project, update the main README and this record together.

## Image sources

Flare's local `flare-preview.png` is downloaded from its repository's `docs/images/launcher-dark.png`. TubeDeck has no screenshot in its README, so its entry uses a text card.

| Asset | Source |
| :-- | :-- |
| `macos-preview.jpg` | https://i.ibb.co/h1y4pYNx/macos.jpg |
| `latent-hub-preview.png` | https://i.ibb.co/3y0jthPy/Screenshot-25.png |
| `soulos-preview.png` | https://i.ibb.co/LDxjHhd7/soulos.png |
| `lossify-preview.png` | https://raw.githubusercontent.com/Akshat96af/lossify/main/assets/home%20page.png |
| `presence-preview.png` | https://i.ibb.co/CKqKn0qG/Screenshot-28.png |
| `omnibypass-preview.png` | https://i.ibb.co/hxHVf38p/Screenshot-29.png |
| `solitaired-preview.png` | Screenshot of https://akshat96af.github.io/Solitaired/ |
| `synclab-preview.png` | https://i.ibb.co/S4z2GdyP/Synclab.png |
| `ps5-ui-preview.png` | https://i.ibb.co/5xrm5gQB/Screenshot-30.png |
| `portfolio-preview.png` | https://i.ibb.co/VY8ZYWd6/Screenshot-36.png |
| `built-with.svg` | https://skillicons.dev/icons?i=html,css,js,ts,react,nodejs,git,github,vscode,figma&theme=dark |

The old animated title graphics, badges, divider GIF, and waving banners were replaced by static SVG artwork and real text headings. The retired GTA VI preview is not used.

## Theme choices

The hero and footer use a purple, pink, and cyan palette with layered interface artwork. Buttons use dark surfaces, a tinted border, and an accent rail matched to each project. Flare uses the cyan accent in its launcher; TubeDeck uses coral.

Button accents follow the actual previews: warm stone for MacOS, rose for Latent Hub, lake blue for SoulOS, coral for Lossify, mint for Presence, cyan for Omnibypass, gold for Solitaired, silver for SyncLab, slate blue for PS5 UI, and violet for the portfolio. Projects without previews keep an accent consistent with their previous identity.

## Local assets or external hosting?

**Local assets suit this showcase best.** GitHub still serves them online; keeping them in the repository provides stable relative paths, version history, and a self-contained checkout. The cost is a larger repository, and screenshots must be refreshed manually.

External hosting is useful for very large media, frequently changing content, or genuinely live badges. It keeps Git history smaller, but introduces third-party availability, changed images, deleted files, and separate maintenance. These previews are a small, fixed collection, so the reliability of local assets is the better tradeoff.

Keep descriptive lowercase filenames. If screenshots become substantially larger or change often, export optimised copies before adding new versions. Never overwrite a preview with unrelated generated artwork.
