# Masažuotojas Giedrius – svetainė

https://masazuotojasgiedrius.lt/

Statinis one-pager: `index.html` + `css/styles.css`, be jokio build žingsnio.
Peržiūrai lokaliai užtenka atidaryti `index.html` naršyklėje.

## Dar liko (`TODO` faile `index.html`)

- tikslus adresas ir darbo laikas (kol kas „Kaunas, Eiguliai“ ir „Susitarus telefonu“),
- kur Giedrius mokėsi, kiek metų dirba; vėliau – portretas skiltyje „Apie“.

## Publikavimas

Kiekvienas `main` šakos atnaujinimas automatiškai publikuojamas per GitHub Actions
(`.github/workflows/pages.yml`) į GitHub Pages. Į svetainę kopijuojami tik
`index.html`, `CNAME`, `robots.txt`, `sitemap.xml`, `css/`, `fonts/`, `img/`.
Aplankas `images/` (originalūs failai) į repozitoriją nekeliamas.

### Domenas

- `CNAME` faile – `masazuotojasgiedrius.lt`; *Settings → Pages*: tas pats domenas, **Enforce HTTPS** įjungta.
- DNS (domenai.lt): `@` → **A** `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`;
  `www` → **CNAME** `karina-klinkeviciute.github.io`.

### SEO

- Pakeitus turinį, atnaujinti `<lastmod>` faile `sitemap.xml`.
- Domenas pridėtas į Google Search Console, ten pateiktas `https://masazuotojasgiedrius.lt/sitemap.xml`.
