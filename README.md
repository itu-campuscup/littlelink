<div align="center">
  <a href="https://campuscup.dk"><img src="https://github.com/itu-campuscup/.github/blob/50aaa28abe375ead7588372c5afa0daae36014cf/campus.png?raw=true" alt="CampusCup" width="180"></a>
  <h1>CampusCup LittleLink</h1>
  <p>One home for CampusCup’s links, event tools, and community channels.</p>
  <p>
    <a href="https://campuscup.dk">Website</a> ·
    <a href="https://github.com/itu-campuscup/littlelink">Repository</a> ·
    <a href="https://littlelink.io">Powered by LittleLink</a>
  </p>
  <p>
    <img alt="License" src="https://img.shields.io/github/license/itu-campuscup/littlelink">
    <img alt="Last commit" src="https://img.shields.io/github/last-commit/itu-campuscup/littlelink">
  </p>
</div>

## What’s here

The landing page brings together Show IT, event photos, the CampusCup website, social channels, and email. Internal Judge IT links are kept in their own section.

### Short links

| Path | Destination |
| --- | --- |
| `/show-it` | Show IT stats |
| `/judge-it` | Judge IT repository |
| `/judge` | Judge IT app |
| `/gh` · `/ig` · `/yt` · `/li` | CampusCup social profiles |
| `/littlelink` | This repository |

## Design

The page pairs Pirata One headings with Montserrat body text, using CampusCup’s light palette. Responsive link cards, keyboard focus, and reduced-motion support are built in. Both font files live in `fonts/`.

## Run locally

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open <http://127.0.0.1:8765>. There’s no build step or JavaScript dependency.

## License

Based on [LittleLink](https://littlelink.io) and distributed under the MIT License. See [LICENSE.md](LICENSE.md).
