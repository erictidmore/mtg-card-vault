<p align="center">
  <img src="https://img.shields.io/badge/MTG-CARD_VAULT-334155?style=for-the-badge&labelColor=000000" alt="MTG Card Vault"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/vanilla-html_·_css_·_js-2563eb?style=flat-square&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/scryfall-api-16a34a?style=flat-square&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/tailwind-css-38bdf8?style=flat-square&logo=tailwindcss&logoColor=38bdf8&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/storage-localStorage-d97706?style=flat-square&labelColor=0a0a0a" />
</p>

<p align="center">
  <code>Single-file Magic: The Gathering collection manager.</code><br/>
  <code>Search sets, track inventory, generate manifests and listing sheets.</code>
</p>

<p align="center">
  <img src="dashboard.png" alt="MTG Card Vault" width="800"/>
</p>

---

### `>_ FEATURES`

| Feature | Detail |
|:--------|:-------|
| **Set Search** | Query any MTG set via Scryfall API — paginated results with filter and sort |
| **Collection Manager** | Multiple named collections with add/remove, currency toggle (USD/EUR/TIX) |
| **Price Sync** | One-click market price refresh from Scryfall |
| **Import / Export** | Paste or upload `.txt` card lists, export collection to file |
| **Manifest Generator** | Downloadable PNG image — highlight grid, newspaper-column inventory list |
| **List Generator** | Checklist view with select-all and copy-to-clipboard for selling platforms |
| **Visual Grid** | Fullscreen card image gallery with quantity badges |
| **Responsive** | Mobile-first layout, touch-friendly controls, adaptive modals |

---

### `>_ USAGE`

```
Open index.html in any browser. No server required.
```

1. **Search** — enter a set code (e.g. `LTR`, `MOM`, `MH1`) and click Search
2. **Add cards** — use `+`/`-` buttons on each card for regular and foil quantities
3. **Manage** — create, rename, switch, or delete collections
4. **Import** — paste a card list or upload a `.txt` file (format: `4x Sol Ring`)
5. **Export** — download collection as `.txt` with prices
6. **Manifest** — generate a shareable PNG inventory image
7. **List Generator** — select cards and copy formatted listing text

---

### `>_ DATA`

All collection data is stored in the browser's `localStorage`. No account, no server, no tracking.

| Action | What Happens |
|:-------|:-------------|
| **Save** | Writes to `localStorage` — persists across sessions |
| **Sync Prices** | Fetches latest prices from Scryfall Collection API |
| **Export** | Downloads a `.txt` summary with card names, sets, and prices |
| **Manifest** | Renders collection to a `<canvas>` and exports as PNG |

---

### `>_ STACK`

<p>
  <img src="https://img.shields.io/badge/HTML5-Single_File_SPA-334155?style=flat-square&logo=html5&logoColor=e34f26&labelColor=111111" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-CDN-38bdf8?style=flat-square&logo=tailwindcss&logoColor=38bdf8&labelColor=111111" />
  <img src="https://img.shields.io/badge/Scryfall-Search_·_Collection_API-16a34a?style=flat-square&labelColor=111111" />
  <img src="https://img.shields.io/badge/html2canvas-Image_Export-d97706?style=flat-square&labelColor=111111" />
</p>

---

<p align="center">
  <sub>MIT License</sub>
</p>
