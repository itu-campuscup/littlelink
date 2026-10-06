# CampusCup LittleLink

CampusCup’s link hub, built on [LittleLink](https://littlelink.io) and styled for the CampusCup brand.

## Links and redirects

The landing page links to Show IT, event images, the CampusCup website, Instagram, YouTube, GitHub, and email. Internal shortcuts are grouped separately.

Short paths redirect to CampusCup destinations:

- `/gh` — GitHub
- `/ig` — Instagram
- `/yt` — YouTube
- `/li` — LinkedIn
- `/littlelink` — this repository
- `/show-it` — Show IT stats
- `/judge-it` and `/judge` — internal Judge IT links

## Design

The landing and privacy pages share the CampusCup style: Montserrat body text, Pirata One headings, and a light, high-contrast palette. The layout includes responsive link cards, visible keyboard focus, and reduced-motion support. Fonts are included in `fonts/`.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8765>. No build step or JavaScript dependencies are required.

## License

This project is based on LittleLink and retains its MIT license. See [LICENSE.md](LICENSE.md).
