# Kompletne Upute za Objavljivanje i Postavljanje Sustava Naplate

## Vodiči i Predlošci za AI Promptove – Kompletan Vodič za Pokretanje Vašeg E-Book Biznisa

Ovaj vodič će vas korak po korak provesti kroz sve što trebate učiniti kako biste objavili vašu prodajnu stranicu online i postavili sustav naplate. Čak i ako niste tehnički stručnjak, moći ćete slijediti ove upute.

---

## Dio 1: Objavljivanje Stranice Online

Trebate objaviti vašu HTML stranicu na internetu kako bi je korisnici mogli vidjeti. Evo nekoliko opcija, od besplatnih do jeftinijih.

### Opcija 1: Netlify (Preporučeno – Besplatno i jednostavno)

**Što je Netlify?** Netlify je besplatna platforma koja omogućuje objavljivanje web stranica u nekoliko minuta bez potrebe za tehničkim znanjem.

**Koraci:**

1. **Kreiraj Netlify račun:**
   - Posjetite https://www.netlify.com
   - Klikni na "Sign up" (Registracija)
   - Odaberi "Sign up with GitHub" ili koristi e-mail
   - Ako koristiš GitHub, trebat ćeš GitHub račun (besplatan, kreiraj na https://github.com)

2. **Preusmjeri datoteke:**
   - Klikni na "New site from Git" ili "Drag and drop"
   - Ako koristiš "Drag and drop": Prosto povuci sve datoteke (prodajna-stranica.html, hvala-osnovni.html, hvala-pro.html, hvala-vip.html) u Netlify prozor
   - Čekaj da se datoteke učitaju (obično 30 sekundi)

3. **Dobij besplatnu domenu:**
   - Netlify će ti dati besplatnu domenu poput "nesto-random.netlify.app"
   - Ako želiš vlastitu domenu (npr. ai-promptovi.com), vidi dolje

4. **Tvoja stranica je sada online!**
   - Posjetite vašu novu domenu i provjerite da sve radi

**Prednosti:** Besplatno, brzo, jednostavno
**Nedostaci:** Besplatna domena nije profesionalna

---

### Opcija 2: Vercel (Besplatno i vrlo brzo)

**Što je Vercel?** Sličan Netlify-u, ali optimiziran za brže učitavanje.

**Koraci:**

1. **Kreiraj Vercel račun:**
   - Posjetite https://vercel.com
   - Klikni na "Sign Up"
   - Koristi GitHub, GitLab ili e-mail

2. **Preusmjeri projekt:**
   - Klikni na "New Project"
   - Odaberi "Import Git Repository" ili "Deploy from Git"
   - Ako koristiš Git: Kreiraj GitHub repozitorij s vašim datotekama
   - Ako ne koristiš Git: Koristi "Other" opciju i preusmjeri datoteke

3. **Deploy:**
   - Klikni "Deploy"
   - Čekaj nekoliko sekundi
   - Dobij besplatnu domenu

**Prednosti:** Besplatno, vrlo brzo, profesionalno
**Nedostaci:** Trebam GitHub znanje za Git opciju

---

### Opcija 3: GitHub Pages (Besplatno, ali malo složenije)

**Što je GitHub Pages?** GitHub je besplatna platforma za dijeljenje koda, a Pages omogućuje objavljivanje web stranica.

**Koraci:**

1. **Kreiraj GitHub račun:** https://github.com (besplatno)

2. **Kreiraj novi repozitorij:**
   - Klikni na "+" u gornjem desnom kotu
   - Odaberi "New repository"
   - Naziv: "ai-promptovi" ili "moj-ebook"
   - Klikni "Create repository"

3. **Preusmjeri datoteke:**
   - U novom repozitoriju, klikni "Add file" > "Upload files"
   - Povuci sve HTML datoteke (prodajna-stranica.html, hvala-*.html)
   - Klikni "Commit changes"

4. **Aktiviraj GitHub Pages:**
   - Idi u "Settings" > "Pages"
   - Pod "Source", odaberi "main" branch
   - Klikni "Save"
   - Čekaj nekoliko minuta

5. **Pronađi svoju domenu:**
   - Vraćaj se u "Pages"
   - Vidjet ćeš link poput "https://korisnicko-ime.github.io/ai-promptovi"

**Prednosti:** Besplatno, jednostavno
**Nedostaci:** Domena nije profesionalna

---

### Opcija 4: Vlastita Domena (Preporučeno za profesionalnost)

Ako želiš profesionalnu domenu poput "ai-promptovi.com", trebat ćeš:

1. **Registrirati domenu:**
   - Posjetite https://www.namecheap.com ili https://www.godaddy.com
   - Pretraži domenu koju želiš (npr. "ai-promptovi.com")
   - Odaberi domenu i dodaj u košaricu
   - Cijena: obično 8-15€ godišnje
   - Završi kupnju

2. **Povezati domenu s Netlify:**
   - U Netlify, idi na "Domain settings"
   - Klikni "Add custom domain"
   - Unesi svoju domenu (npr. ai-promptovi.com)
   - Netlify će ti dati DNS upute
   - U Namecheap/GoDaddy, idi u DNS postavke i dodaj Netlify DNS
   - Čekaj 24-48 sati da se DNS ažurira

3. **Tvoja stranica je sada dostupna na vlastitoj domeni!**

**Cijena:** 8-15€ godišnje za domenu + besplatno hostiranje na Netlify

---

## Dio 2: Postavljanje Stripe Računa i Payment Linkova

Stripe je najpopularniji sustav za primanje plaćanja online. Evo kako ga postaviti.

### Korak 1: Kreiraj Stripe Račun

1. **Posjetite Stripe:**
   - Idi na https://stripe.com
   - Klikni "Sign up" (Registracija)

2. **Unesi osnovne informacije:**
   - Ime i prezime
   - E-mail
   - Lozinka
   - Zemlja: Hrvatska (ili gdje si)

3. **Provjera identiteta:**
   - Stripe će te pitati za dodatne informacije
   - Unesi podatke o svojoj tvrtki ili kao pojedinac
   - Unesi bankovni račun gdje će novac biti uplaćen
   - Provjera obično traje 24-48 sati

4. **Aktiviraj račun:**
   - Čekaj e-mail od Stripe-a s potvrdom
   - Klikni na link u e-mailu

### Korak 2: Kreiraj Payment Linkove za Svaki Paket

Payment linkovi omogućuju korisnicima da plate direktno bez kompliciranih integracija.

1. **U Stripe Dashboard-u, idi na "Payment links"**

2. **Kreiraj prvi payment link (Osnovni paket):**
   - Klikni "+ New"
   - Odaberi "Product" ili kreiraj novi
   - Naziv proizvoda: "Osnovni Paket - AI Promptovi"
   - Cijena: 19.99 EUR
   - Opis: "6 poglavlja s osnovama prompt inženjeringa + 50+ promptova"
   - Klikni "Create product"

3. **Postavi detalje plaćanja:**
   - Odaberi "EUR" kao valutu
   - Postavi količinu: 1 (fiksna)
   - Klikni "Create link"

4. **Kopiraj link:**
   - Stripe će ti dati URL poput: https://buy.stripe.com/test_1234567890
   - Kopiraj ovaj link

5. **Ponovi za PRO i VIP pakete:**
   - PRO Paket: 49.99 EUR
   - VIP/ULTIMATE Paket: 99.99 EUR

### Korak 3: Dodaj Payment Linkove u HTML Stranicu

1. **Otvori prodajna-stranica.html u tekst editoru**

2. **Pronađi ove linije:**
   ```
   <a href="STRIPE_PAYMENT_LINK_OSNOVNI" class="payment-button stripe-button" target="_blank">
   <a href="STRIPE_PAYMENT_LINK_PRO" class="payment-button stripe-button" target="_blank">
   <a href="STRIPE_PAYMENT_LINK_VIP" class="payment-button stripe-button" target="_blank">
   ```

3. **Zamijeni placeholder-e sa stvarnim linkovima:**
   - Zamijenite "STRIPE_PAYMENT_LINK_OSNOVNI" sa stvarnim Stripe linkom za Osnovni paket
   - Zamijenite "STRIPE_PAYMENT_LINK_PRO" sa stvarnim Stripe linkom za PRO paket
   - Zamijenite "STRIPE_PAYMENT_LINK_VIP" sa stvarnim Stripe linkom za VIP paket

4. **Spremi datoteku**

5. **Preusmjeri ažuriranu datoteku na Netlify/Vercel**

---

## Dio 3: Postavljanje PayPal Računa i Payment Linkova

PayPal je alternativa Stripe-u. Mnogi korisnici preferiraju PayPal.

### Korak 1: Kreiraj PayPal Business Račun

1. **Posjetite PayPal:**
   - Idi na https://www.paypal.com
   - Klikni "Sign Up"
   - Odaberi "Business Account"

2. **Unesi podatke:**
   - Ime i prezime
   - E-mail
   - Lozinka
   - Vrsta poslovanja: "Prodaja digitalnih proizvoda"
   - Zemlja: Hrvatska

3. **Verifikacija:**
   - PayPal će tražiti dodatne informacije
   - Unesi bankovni račun
   - Čekaj potvrdu (obično 24-48 sati)

### Korak 2: Kreiraj Payment Linkove

1. **U PayPal Dashboard-u, idi na "Tools" > "PayPal Buttons"**

2. **Kreiraj prvi button (Osnovni paket):**
   - Klikni "Create Button"
   - Odaberi "Buy Now"
   - Naziv stavke: "Osnovni Paket - AI Promptovi"
   - Cijena: 19.99
   - Valuta: EUR
   - Klikni "Create Button"

3. **Kopiraj kod:**
   - PayPal će ti dati HTML kod
   - Kopiraj cijeli kod

4. **Alternativa: Koristi Payment Links (jednostavnije)**
   - Idi na "Invoicing" > "Create Invoice"
   - Kreiraj fakturu s proizvodom
   - Generiraj payment link
   - Kopiraj link

5. **Ponovi za PRO i VIP pakete**

### Korak 3: Dodaj PayPal Linkove u HTML

1. **Otvori prodajna-stranica.html**

2. **Pronađi ove linije:**
   ```
   <a href="PAYPAL_PAYMENT_LINK_OSNOVNI" class="payment-button paypal-button" target="_blank">
   <a href="PAYPAL_PAYMENT_LINK_PRO" class="payment-button paypal-button" target="_blank">
   <a href="PAYPAL_PAYMENT_LINK_VIP" class="payment-button paypal-button" target="_blank">
   ```

3. **Zamijeni placeholder-e sa PayPal linkovima**

4. **Spremi i preusmjeri datoteku**

---

## Dio 4: Kako Ćeš Primati Novac?

### Stripe – Kako Primiti Novac

1. **Bankovni Račun:**
   - Novac se automatski uplaćuje na tvoj bankovni račun
   - Trebat ćeš IBAN broj (pronađi ga u svojoj bankovnoj aplikaciji)
   - Stripe će tražiti IBAN tijekom registracije

2. **Isplate:**
   - Isplate se obično vrše svaki dan (ako imaš dovoljno novca)
   - Minimalna isplata: obično 0,50€
   - Stripe zadržava 2,9% + 0,30€ po transakciji

3. **Primjer:**
   - Korisnik kupi PRO paket za 49,99€
   - Stripe zadržava: 2,9% od 49,99€ + 0,30€ = 1,75€
   - Tebi ostaje: 49,99€ - 1,75€ = 48,24€

### PayPal – Kako Primiti Novac

1. **PayPal Račun:**
   - Novac dolazi na tvoj PayPal račun
   - Možeš ga zadržati u PayPal-u ili ga povući na bankovni račun

2. **Isplate:**
   - Isplate se obično vrše svaki dan
   - PayPal zadržava 2,9% + 0,30€ po transakciji (za digitalnu prodaju može biti drugačije)

3. **Povlačenje novca:**
   - U PayPal-u, idi na "Wallet" > "Transfer Money"
   - Odaberi "Transfer to Your Bank"
   - Unesi iznos i bankovni račun
   - Čekaj 1-3 radna dana

---

## Dio 5: Automatsko Preuzimanje Nakon Plaćanja

Trebat ćeš da korisnici automatski dobiju e-book nakon što plate. Evo nekoliko opcija:

### Opcija 1: Gumroad (Preporučeno – Jednostavno)

**Što je Gumroad?** Gumroad je platforma specijalizirana za prodaju digitalnih proizvoda. Automatski šalje datoteke nakon plaćanja.

**Koraci:**

1. **Kreiraj Gumroad račun:**
   - Posjetite https://gumroad.com
   - Klikni "Sign up"
   - Unesi podatke

2. **Kreiraj proizvod:**
   - Klikni "+ New Product"
   - Naziv: "Osnovni Paket - AI Promptovi"
   - Cijena: 19.99 EUR
   - Opis: Napiši opis paketa
   - Dodaj datoteku: Preusmjeri pro-paket-komplet.md ili PDF

3. **Gumroad će automatski:**
   - Primiti plaćanje
   - Poslati e-mail korisniku
   - Priložiti datoteku u e-mail

4. **Kopiraj link:**
   - Gumroad će ti dati link poput: https://gumroad.com/korisnicko-ime/l/ai-promptovi
   - Koristi ovaj link na svojoj stranici

**Prednosti:** Automatsko slanje datoteka, jednostavno, besplatno (Gumroad zadržava 10%)
**Nedostaci:** Gumroad zadržava veći postotak nego Stripe

---

### Opcija 2: Stripe + Zapier (Naprednije)

**Što je Zapier?** Zapier je servis koji automatizira radnje između različitih aplikacija.

**Kako radi:**
1. Korisnik plati preko Stripe-a
2. Zapier detektira plaćanje
3. Zapier automatski šalje e-mail s download linkom

**Koraci:**

1. **Kreiraj Zapier račun:** https://zapier.com (besplatno)

2. **Kreiraj "Zap":**
   - Klikni "+ Create"
   - Odaberi "Stripe" kao trigger
   - Odaberi "Payment Successful"
   - Poveži svoj Stripe račun

3. **Dodaj akciju:**
   - Odaberi "Email" kao akciju
   - Kreiraj e-mail koji će biti poslan
   - Uključi download link za datoteku

4. **Aktiviraj Zap**

**Prednosti:** Automatsko slanje, fleksibilno
**Nedostaci:** Zapier ima ograničenja u besplatnoj verziji

---

### Opcija 3: Gumroad + Stripe (Kombinacija)

Koristi Gumroad za automatsko slanje datoteka, ali Stripe za primanje plaćanja:

1. **Kreiraj proizvod na Gumroad-u** (kao gore)
2. **Dobij Gumroad link**
3. **Koristi Gumroad link na svojoj stranici umjesto Stripe linka**

**Prednosti:** Automatsko slanje, jednostavno, Gumroad se brine o svemu
**Nedostaci:** Gumroad zadržava 10% (više nego Stripe)

---

## Dio 6: Praćenje Prodaje i Zaradu

### Stripe Dashboard

1. **Idi na https://dashboard.stripe.com**

2. **Provjeri zaradu:**
   - Klikni na "Transactions"
   - Vidiš sve plaćanja
   - Vidjet ćeš iznos koji je primljen i koliko je Stripe zadržao

3. **Izvještaji:**
   - Klikni na "Reports"
   - Vidiš detaljne izvještaje o prodaji
   - Možeš vidjeti koliko je prodano svakog proizvoda

### PayPal Dashboard

1. **Idi na https://www.paypal.com**

2. **Provjeri zaradu:**
   - Klikni na "Activity"
   - Vidiš sve transakcije

3. **Izvještaji:**
   - Klikni na "Reports"
   - Detaljni pregled prodaje

### Gumroad Dashboard

1. **Idi na https://gumroad.com**

2. **Provjeri zaradu:**
   - Klikni na proizvod
   - Vidiš broj prodaja i zaradu
   - Vidiš listu kupaca

---

## Dio 7: Savjeti za Marketing i Prve Prodaje

### 1. Optimiziraj Stranicu za Pretraživače (SEO)

**Što je SEO?** SEO čini da tvoja stranica bude vidljiva na Google-u.

**Koraci:**

1. **Dodaj meta podatke:**
   - U HTML-u, već ima: `<meta name="description" content="...">`
   - Ovo je ono što Google prikazuje

2. **Koristi ključne riječi:**
   - Ključne riječi: "AI promptovi", "prompt inženjering", "AI vodiči", "e-book AI"
   - Uključi ih u naslov, opis i tekst

3. **Kreiraj blog:**
   - Napiši nekoliko blog postova o AI promptovima
   - Link na svoju prodajnu stranicu
   - Google će te bolje rangirati

### 2. Društvene Mreže

**Gdje promovirati:**

1. **LinkedIn:**
   - Idealan za profesionalne proizvode
   - Napiši post: "Upravo sam objavio e-book o AI promptovima!"
   - Dijeli savjete iz e-booka
   - Linkiraj na stranicu

2. **Twitter/X:**
   - Dijeli kratke savjete o AI promptovima
   - Koristi hashtag-e: #AIPrompts #PromptEngineering #AI
   - Linkiraj na stranicu

3. **Facebook:**
   - Kreiraj stranicu za svoj proizvod
   - Dijeli sadržaj
   - Koristi Facebook Ads za plaćanu promociju (počni s 5-10€)

### 3. E-mail Marketing

**Kako početi:**

1. **Kreiraj besplatnu e-mail listu:**
   - Koristi Mailchimp (besplatno za do 500 kontakata)
   - Ili Brevo (besplatno)

2. **Dodaj sign-up formu na stranicu:**
   - Ponudi besplatni bonus (npr. 5 best promptova)
   - Korisnici će se prijaviti s e-mailom

3. **Pošalji e-mail:**
   - Pošalji e-mail s linkom na stranicu
   - Pošalji follow-up e-mailove s savjetima

### 4. Plaćena Promocija

**Gdje oglašavati:**

1. **Google Ads:**
   - Prikazuj oglase kada netko pretraži "AI promptovi"
   - Počni s budžetom od 10€ dnevno
   - Google će te voditi kroz proces

2. **Facebook/Instagram Ads:**
   - Kreiraj oglas s opisom e-booka
   - Ciljaj ljude zainteresirane za AI
   - Počni s 5-10€ dnevno

3. **Reddit:**
   - Pronađi subreddite o AI-ju
   - Dijeli svoj e-book (ako je relevantno)
   - Budi oprezan – Reddit ne voli direktnu promociju

### 5. Partnerstva i Suradnje

1. **Pronađi influencere:**
   - Pronađi YouTubere ili bloggere koji pišu o AI-ju
   - Ponudi im besplatnu kopiju e-booka
   - Ako im se sviđa, mogu ga preporučiti

2. **Gostuj na podcastima:**
   - Pronađi podcaste o AI-ju
   - Ponudi se kao gost
   - Promovira tvoj e-book tijekom epizode

3. **Suradnje s drugim prodavačima:**
   - Pronađi ljude koji prodaju komplementarne proizvode
   - Ponudi im affiliate program (npr. 20% provizije)
   - Oni će promovirati tvoj e-book

### 6. Prvih 10 Prodaja – Strategija

1. **Ponudi besplatno ili s popustom:**
   - Ponudi prvi 10 kupaca 50% popust
   - Traži od njih da ostave recenziju
   - Recenzije pomažu za prodaju

2. **Traži povratne informacije:**
   - Kontaktiraj prve kupce
   - Pitaj ih što im se sviđa i što se može poboljšati
   - Koristi povratne informacije za marketing

3. **Napravi case study:**
   - Ako netko koristi e-book i postigne rezultate, traži dozvolu da ga predstaviš
   - Case study je moćan marketing alat

---

## Dio 8: Česta Pitanja

### P: Trebam li vlastitu domenu?
**O:** Ne trebam za početak. Besplatne domene (Netlify, Vercel) su okej. Kasnije, ako želiš biti profesionalniji, kupi vlastitu domenu (8-15€ godišnje).

### P: Koliko novca trebam za početak?
**O:** Tehnički, možeš početi s 0€. Sve je besplatno osim domene (opciono). Ako želiš plaćanu promociju, počni s 5-10€ dnevno.

### P: Koliko vremena trebam za postavljanje?
**O:** 2-4 sata za sve. Objavljivanje stranice: 15 minuta. Stripe/PayPal: 1 sat. Dodavanje linkova: 30 minuta.

### P: Što ako nešto ne radi?
**O:** Kontaktiraj support:
- Netlify Support: https://support.netlify.com
- Stripe Support: https://support.stripe.com
- PayPal Support: https://www.paypal.com/us/smarthelp

### P: Trebam li poreziti dohodak?
**O:** DA. Dohodak od prodaje je oporeziv. Trebat ćeš:
- Registrirati se kao samostalni djelatnik ili otvoriti obrt
- Voditi evidenciju prodaje
- Platiti porez na dohodak
- Savjetuj se s računovođom

### P: Kako mogu povećati prodaju?
**O:** Vidi "Savjeti za marketing" gore. Najjednostavnije: LinkedIn, Twitter, e-mail marketing.

### P: Mogu li prodavati u drugim valutama?
**O:** DA. Stripe i PayPal podržavaju više valuta. Korisnici će vidjeti cijenu u svojoj valuti.

---

## Dio 9: Sljedeći Koraci

1. **Kreiraj Netlify ili Vercel račun** (15 minuta)
2. **Preusmjeri stranicu** (5 minuta)
3. **Kreiraj Stripe račun** (30 minuta)
4. **Kreiraj payment linkove** (15 minuta)
5. **Dodaj linkove u HTML** (10 minuta)
6. **Testiraj plaćanja** (5 minuta)
7. **Kreiraj PayPal račun** (30 minuta, opciono)
8. **Počni s marketingom** (svakodnevno)

**Ukupno vrijeme za postavljanje: 2-3 sata**

---

## Dio 10: Dodatni Resursi

- **Stripe dokumentacija:** https://stripe.com/docs
- **PayPal dokumentacija:** https://developer.paypal.com
- **Netlify dokumentacija:** https://docs.netlify.com
- **Vercel dokumentacija:** https://vercel.com/docs
- **SEO vodič:** https://developers.google.com/search/docs
- **Google Ads:** https://ads.google.com
- **Facebook Ads:** https://www.facebook.com/ads

---

## Zaključak

Sada imaš sve što trebam za pokretanje svoga e-book biznisa. Proces je jednostavan:

1. Objaviti stranicu
2. Postaviti plaćanja
3. Početi s marketingom
4. Primati novac

Sretno s prodajom! Ako trebam pomoć, kontaktiraj support servise gore navedenih platformi.

**Autor:** Manus AI | **Verzija:** 1.0 | **Datum:** Lipanj 2026
