# Port Review issue — ready to paste

Open a **Port Review** issue in `catppuccin/catppuccin`
(https://github.com/catppuccin/catppuccin/issues/new/choose) and fill the template
with the text below. Replace every `<...>` placeholder first.

---

**Repository**

https://github.com/Lugwiire-Benard/fetchmark

**Screenshots**

Attach the four images from `assets/` in the repository (or link them directly):

- Latte — https://raw.githubusercontent.com/Lugwiire-Benard/fetchmark/main/assets/latte-reader.webp
- Frappé — https://raw.githubusercontent.com/Lugwiire-Benard/fetchmark/main/assets/frappe-reader.webp
- Macchiato — https://raw.githubusercontent.com/Lugwiire-Benard/fetchmark/main/assets/macchiato-reader.webp
- Mocha — https://raw.githubusercontent.com/Lugwiire-Benard/fetchmark/main/assets/mocha-reader.webp

**Additional comments**

FetchMark (https://fetchmarkapp.com) is a read-it-later app: you save an article and
it keeps a full offline copy with reader view, highlights, notes and full-text search.

The theme is native — it ships inside the product rather than as a userstyle — and is
selectable in Settings → Appearance as Latte, Frappé, Macchiato or Mocha. All four
flavours are implemented, each with the official palette values, and the flavour is
applied across the whole interface (surfaces, borders, text hierarchy, primary and
secondary buttons, destructive/success/warning states, reader and footer surfaces)
through semantic tokens. The palette layer is published in
`fetchmark-catppuccin.css` in the repository and is the exact CSS the production app
loads.

Contrast was measured per flavour for the primary button, its label, the footer text
and the social-proof band; all are at or above 4.5:1.

If the port is accepted, I'd like to open the `resources/ports.yml` entry
(snippet in the repository's `ports-entry.yml`).
