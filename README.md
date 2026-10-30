# Plan curte – pomi fructiferi

Pagină web (un singur fișier, `index.html`) cu planul curții la scară, în care poți muta cu degetul sau cu mouse-ul pomii, arbuștii, leagănul și trambulina.

- **＋ Adaugă**: pomi (cais, piersic, cireș, măr, păr, nuc etc., cu soiurile și prețurile de la Pepiniera Sarusi), smochin (preț estimat, alt magazin), zmeur, mur, afin, coacăz, agriș, leagăn, trambulină.
- Atinge un element ca să-i schimbi soiul și coroana, să-l rotești, duplici sau ștergi. Sunt afișate distanțele față de gardul vecinului, casă și garaj, plus avertismente (de exemplu sub 2 m de gardul vecinului).
- **💾 Variante**: salvează mai multe variante în browser (localStorage). Planul curent se salvează automat.
- **🖼 Imagine**: generează un PNG cu planul și lista de prețuri. Pe telefon „Salvează / trimite” → „Salvează imaginea”.
- **🔗 Link**: un link care conține tot planul, ca să-l deschizi pe alt telefon.

## Publicare pe GitHub Pages

1. Pe github.com: **New repository** (de ex. `plan-curte`), **Public**, fără README.
2. Varianta simplă: în repository → **Add file → Upload files** → încarci `index.html` (și `README.md`) → **Commit changes**.
   Sau din terminal, în acest folder:
   ```
   git remote add origin https://github.com/UTILIZATOR/plan-curte.git
   git push -u origin main
   ```
3. În repository: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. După 1–2 minute pagina e la `https://UTILIZATOR.github.io/plan-curte/`.

Pentru o modificare: editezi `index.html` și îl încarci din nou (sau `git commit` + `git push`).
