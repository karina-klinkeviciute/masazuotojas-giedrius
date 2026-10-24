# Masažuotojas Giedrius – svetainė

Statinis one-pager: `index.html` + `css/styles.css`, be jokio build žingsnio.
Peržiūrai lokaliai užtenka atidaryti `index.html` naršyklėje.

## Prieš paleidžiant

`index.html` faile dar liko `TODO`:
- tikslus adresas ir darbo laikas (kol kas „Kaunas, Eiguliai“ ir „Susitarus telefonu“),
- sertifikatai / patirtis skiltyje „Apie Giedrių“,
- nuotrauka dalinimuisi (`img/og.jpg`).

## Publikavimas GitHub Pages

1. Sukurti **viešą** repozitoriją GitHub'e ir įkelti failus.
2. *Settings → Pages → Build and deployment*: Source **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Po minutės svetainė veiks adresu `https://<vartotojas>.github.io/<repo>/`.

### Savas domenas

1. *Settings → Pages → Custom domain*: įrašyti, pvz., `www.giedriausmasazai.lt` (GitHub sukurs `CNAME` failą).
2. Pas domeno registratorių nustatyti DNS:
   - `www` → **CNAME** → `<vartotojas>.github.io`
   - šakninis domenas (`@`) → **A** įrašai: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
3. Kai DNS persiduos (iki kelių valandų), įjungti **Enforce HTTPS**.
