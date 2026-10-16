# myet

Personal site of Ervin Tan, CT Whisperer: CT imaging × AI.

The whole site is one self-contained file, `index.html`. Pages (Home, About, Builds, Experience, Coverage, Contact) are rendered in place, with the ripple grid running underneath.

## Builds

| Build | Live tool |
|---|---|
| 01 Knee MAR Viewer | https://smartermar.netlify.app/ |
| 02 Agatston Blind Spot | https://agaston.netlify.app/ |
| 03 Vessel Vector | https://ssfreeze.netlify.app/ |
| 04 Perfusion Literacy | https://brainperf.netlify.app/ |

## Deploy

Static, no build step. On Netlify, point the site at this repo with publish directory `.`; `_redirects` sends direct visits to `about.html` and the other page names to `index.html`.
