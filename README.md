# Auto škola Reni Pro — sajt

Statički sajt spreman za hostovanje (GitHub Pages, Netlify, bilo koji web server).

## Stranice
- `index.html` — početna
- `o-nama.html` — O nama
- `cenovnik.html` — Cenovnik
- `tim.html` — Naš tim
- `galerija.html` — Galerija
- `kontakt.html` — Kontakt
- `kondicioni.html` — Kondicioni časovi

## Objava na GitHub Pages
1. Napravi novi repozitorijum i otpremi **sav sadržaj ove `export` fascikle** (uključujući `uploads/`, `support.js`, `image-slot.js`).
2. Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` grana, `/ (root)` folder.
3. Sačuvaj — sajt će biti na `https://<korisnik>.github.io/<repo>/`.

## Napomene
- `index.html` mora ostati naziv početne strane.
- Ne razdvajaj fajlove — `support.js`, `image-slot.js` i `uploads/` moraju biti u istoj fascikli kao HTML stranice.
- Sve stranice su međusobno povezane relativnim linkovima. Hero video kreće automatski (muted, u petlji).
- Za bržе učitavanje preporučujemo kompresiju videa u `uploads/` pre uploada.
