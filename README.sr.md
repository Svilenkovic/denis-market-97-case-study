<a href="https://denismarket.rs/"><img src="media/cover.jpg" alt="Denis Market 97, naslovna strana na laptopu i telefonu" width="100%"></a>

# Denis Market 97

Jedan sajt od 37 strana za dva posla pod istim imenom: seoski market u Nikolincima i proizvodnju kora za pitu u Beogradu.

**[denismarket.rs](https://denismarket.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/denis-market-97) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Denis Market 97</td></tr>
  <tr><td><b>Delatnost</b></td><td>Market mešovite robe i proizvodnja kora za pitu</td></tr>
  <tr><td><b>Lokacija</b></td><td>Nikolinci i Beograd</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, custom router, flat-file content, JSON-LD</td></tr>
</table>

## O projektu

Denis Market 97 drži market u Nikolincima, selu u opštini Alibunar, otvoren svaki dan od 6 do 23 h. Ista firma u Ledinama, u Beogradu, pravi tanke kore za pitu i gibanicu za pekare, restorane i domaćinstva, a na telefon se za oba posla javlja isti čovek. Sajt je trebalo da komšiju pošalje u radnju, a pekaru u pogon za kore, tako da nijedan ne završi na tuđim stranama.

Zadržao sam jedan brend sa dve odvojene grane: sve o radnji stoji pod /market/, sve o korama pod /kore/, a zajednički su samo kontakt, o nama, lokacije i česta pitanja. Nema ni cena ni korpe, jer se cene na polici menjaju brže od bilo kog sajta, a cena kora zavisi od količine. Razdaljine do okolnih mesta izmerene su po putu, onako kako se stvarno vozi. Od osam strana za okolna mesta koje je klijent tražio napravio sam tri, jer bi ostale bile skoro iste i ne bi imale ništa tačno da kažu.

## Šta sam uradio

- 37 strana u pet grana, a sadržaj stoji u običnim PHP fajlovima, bez baze i bez CMS-a
- Šest recepata sa Recipe oznakama, kao ulaz za ljude koji prave pitu od gotovih kora, a dobavljača još ne traže
- Mapa sajta se ispisuje iz istih podataka kao i strane, pa nova strana ne može da ostane van nje
- Radno vreme za svih sedam dana u strukturisanim podacima, a pogon za kore je vezan za firmu kao njen deo
- Jedna kontakt forma za obe grane, sa izborom teme, bodovanjem neželjene pošte i dnevnikom svih poruka, pa i odbijenih
- Dnevna i noćna tema i fontovi sa sopstvenog servera, a font za tekst unapred učitan u oba latinična podskupa, pa č, ć, š, ž i đ ne prelamaju tekst iznova

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 85 | 100 | 100 | 100 |
| Desktop | 97 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `FAQPage`, `GroceryStore`, `LocalBusiness`, `Person`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Denis Market 97, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Denis Market 97, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Market: sveže svako jutro, otvoreno od 6 do 23 h, sedam dana u nedelji">
<sub>Market: sveže svako jutro, otvoreno od 6 do 23 h, sedam dana u nedelji</sub>

<img src="media/inner-2.webp" alt="Kore iz Ledina: za pekare i ugostitelje po dogovoru, za domaćinstva na upit">
<sub>Kore iz Ledina: za pekare i ugostitelje po dogovoru, za domaćinstva na upit</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
