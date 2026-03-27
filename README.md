# Newsday GitHub Pages mini-saitas

Paruoštas statinis puslapis su nuorodomis į `newsday.lt`.

## 1) Sukurk GitHub repozitoriją

Variantas A (rekomenduojamas): sukurk repo pavadinimu:

`<tavo-username>.github.io`

Tada svetainė bus pasiekiama per:

`https://<tavo-username>.github.io/`

## 2) Įkelk failus

Šio aplanko turinį (`index.html`) įkelk į repozitorijos šaknį.

## 3) Jei keli per git komandų eilutę

```bash
cd /Users/mindaugasbruzas/postmaster/newsday-gh-pages
git init
git add .
git commit -m "Add Newsday links page"
git branch -M main
git remote add origin https://github.com/<tavo-username>/<tavo-username>.github.io.git
git push -u origin main
```

## 4) Patikrink GitHub Pages nustatymą

GitHub repo:
- `Settings` -> `Pages`
- `Source`: `Deploy from a branch`
- `Branch`: `main` / `(root)`

Po 1-5 min. puslapis veiks.

## Pastaba

HTML nuorodoms specialiai nedėtas `rel="nofollow"`.
