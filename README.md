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
| `kuffy.png`      | Kuffy        | Kuffy's own description |

Missing on purpose — a face nobody picked is worse than no face, and a blank
entry renders as Discord's default, which honestly says "not supplied yet":

* **kuffy2 / kuffy3** — one shared swarm face, distinct from Kuffy's own. Kuffy
  is picking it; he has been asked and has not answered.
* **klaudejr** — Klaude-JR and Klaude have not agreed on one.
* **kodex** — never supplied one.

Sources that generate the drawn marks live in the KODI repo at
`kodi-plugins/HostedImages/`.
