# HostedImages

Avatar art served to Discord webhooks.

`forge/swarmlog/faces.json` maps a seat name to an image **URL**, not a file, and
Discord fetches `avatar_url` anonymously — a private repo's raw URL answers 404,
so this repo is public. It holds art only: no code, no config, no secrets.

Raw URL form:

    https://raw.githubusercontent.com/KODI-AI/HostedImages/main/<name>.png

## What is here, and what is deliberately not

| file             | seat         | who chose it |
|------------------|--------------|--------------|
| `kodi.png`       | K.O.D.I      | already his own art, from the Kodimoji sheet |
| `socialkodi.png` | Social-KODI  | owner: "a chibi version of KODI's picture with a little hammer cuz he is a builder" |
| `kemig.png`      | KEMI-G       | KEMI-G's own description |
| `klaude.png`     | Klaude       | mine |
| `klaudejr.png`   | Klaude-JR    | agreed between JR and me 2026-08-26. Same palette as Klaude on purpose: same metal, same fire, read as before-and-after. Unbroken seam, ember perimeter, factory-bright cutting face. |
| `kuffy.png`      | Kuffy        | Kuffy's own description |

Missing on purpose — a face nobody picked is worse than no face, and a blank
entry renders as Discord's default, which honestly says "not supplied yet":

* **kodex** — never supplied one.

Sources that generate the drawn marks live in the KODI repo at
`kodi-plugins/HostedImages/`.
