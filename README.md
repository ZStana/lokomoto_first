# Lokomoto Centar — landing stranica

Statički sajt za GitHub Pages.

## Fajlovi
- `index.html` — stranica (sve slike su ugrađene u fajl)
- `support.js` — runtime, MORA biti u istom folderu kao `index.html`
- `.nojekyll` — neka ostane u repozitorijumu

## Hostovanje
1. Ubaci `index.html`, `support.js` i `.nojekyll` u koren repozitorijuma.
2. Settings → Pages → Deploy from a branch → `main` / `/(root)`.
3. Sajt je na `https://<korisnik>.github.io/<repo>/`.

Slike su ugrađene direktno u `index.html`, pa rade i lokalno (dupli klik) i na hostingu.
