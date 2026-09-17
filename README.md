# OsteoMaster — site GitHub Pages

Site static FructoseLabs, fără instalări, build, baze de date sau chei secrete. Aplicație: `com.osteomaster.app`. Contact: fructoselabs@gmail.com.

## Ce încarci

Dezarhivează pachetul. Încarcă **fișierele din interior**, direct în rădăcina repository-ului:

- index.html
- privacy-policy.html
- styles.css
- icon.png
- .nojekyll
- README.md (aceste instrucțiuni)

Nu încărca arhiva ZIP ca atare și nu încărca întregul proiect Android. Nu încărca `release-private/`, parole, fișiere `.jks`, APK/AAB sau rapoarte de build. Nu este nevoie de fișier CNAME dacă nu ai domeniu propriu.

## Publicare din interfața GitHub

1. Creează un repository **Public**, de exemplu `osteomaster`. GitHub Pages este disponibil pentru repository-uri publice pe GitHub Free. Dacă ai deja un repository pentru acest site, îl poți folosi; păstrează alte fișiere existente care nu aparțin acestui pachet.
2. Încarcă fișierele: **Add file → Upload files**, apoi **Commit changes**. Dacă repository-ul este gol, folosește legătura **uploading an existing file**. `index.html` trebuie să fie la rădăcină, nu într-un subfolder.
3. Deschide **Settings → Pages**.
4. La **Build and deployment → Source**, selectează **Deploy from a branch**.
5. Selectează ramura **main**, folderul **/(root)** și apasă **Save**. Dacă ramura ta are alt nume, alege ramura în care ai încărcat fișierele.
6. Așteaptă publicarea (poate dura până la 10 minute). În aceeași pagină, folosește **Visit site**. Verifică eventualele erori în fila Actions.
7. Deschide legătura **Politica de confidențialitate** de pe site. Copiază adresa paginii publice din browser în câmpul Privacy policy din Play Console. Verifică accesul și într-o fereastră privată, fără autentificare.

## Cum vor arăta adresele

Dacă repository-ul se numește `osteomaster`, adresele vor avea forma:

```text
https://UTILIZATORUL-TAU.github.io/osteomaster/
https://UTILIZATORUL-TAU.github.io/osteomaster/privacy-policy.html
```

`UTILIZATORUL-TAU` se înlocuiește cu numele real al contului/organizației GitHub. Nu presupune că numele de dezvoltator FructoseLabs este și numele contului GitHub.

Pentru un repository special numit exact `UTILIZATORUL-TAU.github.io`, segmentul `/osteomaster/` lipsește. Folosește întotdeauna adresa confirmată prin **Visit site**, nu un URL presupus. Nu folosi linkul `github.com/.../blob/...` și nu folosi adresa unui fișier local.

## Întreținere

Păstrează politica publică în acord cu funcțiile și SDK-urile aplicației. Dacă apar conturi, reclame, analytics sau alte fluxuri de date, actualizează atât politica web, cât și cea din aplicație și declarația Data safety. Pagina principală spune că aplicația este în pregătire: actualizează acest text după publicarea efectivă în Google Play.

Nu s-a publicat automat nimic în GitHub. Arhiva conține numai fișiere publicabile ale site-ului; fonturile și iconița sunt locale, fără resurse externe obligatorii.

## Documentație oficială

- [Crearea unui site GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configurarea publicării dintr-o ramură](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
