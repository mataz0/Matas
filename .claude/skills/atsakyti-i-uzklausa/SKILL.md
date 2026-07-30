---
name: atsakyti-i-uzklausa
description: Parengia atsakymą į paslaugos.lt (ar kitą viešą) buhalterinės apskaitos užklausą mbuhalterija.lt vardu. Naudok šį skill'ą visada, kai vartotojas įklijuoja skelbimo/užklausos tekstą, kuriame ieškoma buhalterio ar apskaitos paslaugų (MB, UAB, IĮ, NT perpardavimas), arba parašo „atrašyti į užklausą", „atsakyk į užklausą", „paruošk pasiūlymą" ir pan. – net jei žodis „užklausa" nepaminėtas, bet tekstas akivaizdžiai yra skelbimas apie buhalterio paiešką.
---

# Atsakymas į buhalterijos užklausą

Parengiamas trumpas Viber žinutės formato atsakymas į viešą skelbimą, kuriame ieškoma buhalterinės apskaitos paslaugų.

## Eiga

1. Perskaityk užklausą ir išsirink faktus: įmonės forma (UAB/MB/IĮ), darbuotojų skaičius, dokumentų (SF) kiekis per mėnesį, veiklos specifika (pvz., NT perpardavimas), PVM mokėtojo statusas (jei nurodytas), vieta.
2. Peržiūrėk `atsakymai/` katalogą – ankstesni atsakymai rodo įsivažiavusį stilių ir kainų lygį panašiai apimčiai. Laikykis jų nuoseklumo.
3. Parenk atsakymą pagal žemiau aprašytą struktūrą ir stilių.
4. Išsaugok jį faile `atsakymai/YYYY-MM-DD-<trumpas-apibudinimas>.md` (data – šiandienos). Failo viršuje cituojama užklausa, žemiau – atsakymas (žr. formatą).
5. Padaryk commit ir push į nurodytą darbo šaką.
6. Galutinėje žinutėje vartotojui pateik patį atsakymo tekstą (kad būtų galima tiesiog nukopijuoti į Viber) ir trumpai paaiškink kainos ar turinio pasirinkimus, jei jie buvo tavo spėjimas.

## Atsakymo struktūra

Trys trumpos pastraipos, be kreipinio struktūros, be parašo bloko:

1. **Pasiūlymas pagal apimtį** – kas įeina į paslaugą būtent pagal kliento nurodytus skaičius (SF kiekis, darbuotojų DU su Sodra/GPM, automobilio ar kitų sąnaudų apskaita, PVM ir pelno mokesčio deklaracijos, metinė atskaitomybė). Pradžioje paminėti mbuhalterija.lt.
2. **Kaina** – konkreti suma arba siauras rėžis €/mėn. Jei tiksliai apskaičiuoti neįmanoma, pridėti, kad galutinė patikslinama po trumpo pokalbio.
3. **Vienas patikslinantis klausimas** – tik pats svarbiausias, nuo kurio labiausiai priklauso apimtis/kaina (dažniausiai: ar įmonė PVM mokėtoja; NT atveju – ar objektai nauji/seni, ar taikomas 96 str. atvirkštinis PVM).

## Stiliaus taisyklės (iš CLAUDE.md – privalomos)

- Viber formatas: trumpai, be oficialaus laiško struktūros, be „Pagarbiai".
- **Jokių padėkų** („dėkoju už užklausą" ir pan.) – užklausos viešos, ne asmeninės.
- **Jokios savigyros** („puikiai išmanau", „didelė patirtis"). Kompetencija rodoma konkrečiomis įstatymų nuorodomis, kai jos aktualios.
- Kalbama **mbuhalterija.lt vardu**, daugiskaita („siūlome", „tvarkome"), ne „aš buhalterė".
- Tik tai, ko klientui reikia – be mokesčių teorijos dėstymo.

## NT perpardavimo užklausos

Jei užklausoje minimas NT pirkimas–pardavimas, glaustai (viena–dviem eilutėmis, ne paskaita) parodyti išmanymą:

- PVMĮ 32 str. – naujo/seno pastato riba (24 mėn. po užbaigimo), esminis pagerinimas;
- PVM atskaita įsigyjant ir jos tikslinimas;
- PVMĮ 96 str. – atvirkštinis PVM statybos darbams;
- atsargų (perparduodamų objektų) apskaita.

## Kainos orientyrai

Jei `atsakymai/` kataloge yra panašios apimties atsakymų – imk kainą iš jų. Jei ne, orientyras: maža UAB (1 darbuotojas, ~20–25 SF/mėn.) ≈ 100–130 €/mėn.; apimčiai augant (daugiau darbuotojų, daugiau SF, PVM mokėtojas, NT sandoriai) kaina atitinkamai didėja. Savo spėjimą visada įvardink vartotojui, kad galėtų pakoreguoti.

## Failo formatas (`atsakymai/*.md`)

```markdown
# Užklausa

> [cituojamas skelbimo tekstas]
>
> Vieta: [vieta]

# Atsakymas (Viber)

[atsakymo tekstas]
```

## Pavyzdys

**Užklausa:** UAB, 1 darbuotojas, 1 automobilis, 20–25 SF/mėn., Vilnius.

**Atsakymas:**

> Sveiki, mbuhalterija.lt siūlo pilną UAB apskaitos tvarkymą nurodytai apimčiai: 20–25 SF per mėnesį, 1 darbuotojo darbo užmokestis (Sodra, GPM deklaracijos), automobilio sąnaudų apskaita (kuras, remontas, nusidėvėjimas), PVM ir pelno mokesčio deklaracijos, metinė finansinė atskaitomybė.
>
> Orientacinė kaina tokiai apimčiai – 100–130 €/mėn., galutinę patikslintume po trumpo pokalbio.
>
> Ar įmonė yra PVM mokėtoja?
