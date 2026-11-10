# DIJANA HAIR

Kompletan statički sajt za frizerski salon DIJANA HAIR u Kneževu. HTML, CSS i JavaScript, bez instalacije paketa, build koraka, API ključeva ili servera za aplikaciju. Spreman za GitHub Pages i drugi statički hosting.

## Lokalni pregled

Otvori `index.html` dvoklikom. Fotografije i Montserrat su lokalni fajlovi, pa sajt možeš pregledati i bez interneta. Spoljni linkovi i Viber traže odgovarajuću aplikaciju ili internet.

Za pregled preko lokalnog servera, ako imaš Python:

```sh
python -m http.server 4173
```

Zatim otvori `http://localhost:4173`.

## GitHub Pages

1. Raspakuj ZIP. Sadržaj foldera `dijana-hair` treba biti u korijenu repozitorijuma: `index.html`, `styles.css`, `script.js`, `assets/` i ostali fajlovi. Ne stavljaj dodatni folder iznad `index.html`.
2. Napravi prazan repozitorijum na GitHubu, npr. `dijana-hair`.
3. Otvori terminal u folderu sajta i izvrši komande ispod, uz zamjenu `TVOJE-KORISNICKO-IME` svojim GitHub imenom.

```sh
git init
git add .
git commit -m "Add DIJANA HAIR website"
git branch -M main
git remote add origin https://github.com/TVOJE-KORISNICKO-IME/dijana-hair.git
git push -u origin main
```

4. Na GitHubu otvori **Settings → Pages → Build and deployment**.
5. Za **Source** izaberi **Deploy from a branch**, granu **main** i folder **/(root)**, pa **Save**.
6. Nakon objave, GitHub će prikazati adresu sajta, uobičajeno `https://TVOJE-KORISNICKO-IME.github.io/dijana-hair/`.

Alternativno, sadržaj foldera možeš dodati kroz GitHub opciju **Add file → Upload files**. Sačuvaj strukturu foldera `assets`.

Uputstvo za Pages provjereno prema [zvaničnoj GitHub dokumentaciji](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Izmjene

- Tekstovi, cijene, radno vrijeme, adresa i linkovi: `index.html`.
- Boje, fontovi, razmaci i mobilni prikaz: `styles.css`.
- Mobilni meni i galerija: `script.js`.
- Fotografije: `assets/`. WebP verzije su optimizovane za učitavanje.
- Font: `assets/fonts/`, zajedno s OFL licencom. Nema poziva Google Fonts servisu pri posjeti.

Sve putanje su relativne, pa sajt radi i u GitHub project repozitorijumu.

## Kontakt i sadržaj

- Broj: **+387 65 529 928**.
- Viber dugmad: `viber://chat?number=%2B38765529928`.
- Poziv: `tel:+38765529928`.
- Instagram: `https://www.instagram.com/dijanahair/`.
- Adresa: Dujka Komljenovića bb, Kneževo.
- Ponedjeljak–petak: 10:00–18:00. Subota: 10:00–16:00. Nedjelja: neradna.

Viber link pokušava otvoriti aplikaciju; ne šalje poruku automatski. Otvaranje konkretnog razgovora zavisi od uređaja, instalacije i verzije Vibera i nije testirano na fizičkom telefonu. Kao alternativa svuda je dostupan telefonski broj i poziv. Ako salon koristi Viber Business, sva Viber odredišta možeš zamijeniti zvaničnim chat linkom iz poslovnog profila ([Viber uputstvo](https://help.viber.com/hc/en-us/articles/36712478644381-Get-your-Viber-chat-link-and-QR-code-for-Business-accounts)).

Instagram profil nije bilo moguće učitati kroz dostupni pristup tokom izrade. Nisu preuzimane objave niti izmišljane informacije s profila.

Pet cijena je prepisano iz dostavljenog cjenovnika od 15. 9. 2025. Originalni PDF je sačuvan bez izmjena. U njemu je navedena doplata nedjeljom; sajt prati noviju izričitu informaciju vlasnika da je nedjelja neradna. Ako se objavljuje novi PDF, zamijeni `assets/cjenovnik-original.pdf`.

Dvije fotografije frizura obrađene su pomoću ugrađenog Imagegen alata; obrada uključuje svjetlo, jasnoću i usklađivanje pozadine, pa rezultat nije dokumentarno identičan izvornom snimku. Izvorne fotografije na računaru nisu mijenjane. Opis i korišteni promptovi nalaze se u `ASSETS.md`.

## Prije i poslije objave

- Pregledaj cijene i probaj Viber dugme na svom telefonu.
- Sajt trenutno nije objavljen na internetu; paket je pripremljen za tvoj push.
- Kada dobiješ javnu adresu, za pouzdanije dijeljenje na društvenim mrežama promijeni `og:image` u apsolutnu javnu adresu fotografije i dodaj `og:url` i canonical adresu. Oni nisu izmišljeni unaprijed jer domen još nije poznat.
- Nema analitike, kolačića, kontakt forme ni obrade rezervacija na serveru. Dogovor termina se obavlja direktno u Viberu ili telefonom.
