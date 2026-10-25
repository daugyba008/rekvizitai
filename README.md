# Lietuvos verslo ir duomenų analitikos platforma („Rekvizitai24“)

[![Projekto būsena](https://img.shields.io/badge/Projekto%20b%C5%ABsena-100%25%20Baigta-238636?style=flat-svg)](https://rekvizitai24.lt)
[![Automatizacija](https://img.shields.io/badge/Automatizacija-100%25-2ea043?style=flat-svg)](https://rekvizitai24.lt)
[![Duomenų kokybė](https://img.shields.io/badge/Duomen%C5%B3%20kokyb%C9%9B-100%25-blue?style=flat-svg)](https://rekvizitai24.lt)
[![SEO](https://img.shields.io/badge/SEO-Optimizuota-0969da?style=flat-svg)](https://rekvizitai24.lt)

Detali Lietuvos verslo analitikos ir duomenų valdymo platformos **[Rekvizitai24.lt](https://rekvizitai24.lt)** būsenos bei automatizuotos infrastruktūros ataskaita. Lietuvos rinkos apimčiai numatytas funkcionalumas yra 100% realizuotas, patikrintas ir veikia pilnu pajėgumu be rankinio įsikišimo.

---

## Pagrindiniai projekto rodikliai

| Rodiklis | Įvertinimas | Aprašymas |
| :--- | :---: | :--- |
| **Bendras baigtumas** | `100%` | Visi 9 suplanuoti moduliai pilnai realizuoti ir integruoti |
| **Automatizavimas** | `100%` | Nulinis rankinis įsikišimas – procesai vyksta automatiškai |
| **Duomenų kokybė** | `100%` | Automatiniai tikrinimo, valymo ir formatavimo algoritmai |
| **SEO ir indeksavimas** | `100%` | Puslapiai indeksuoti paieškos sistemose, paruošta raktažodžių struktūra |

---

## Detalūs sričių rodikliai ir būsenos pastabos

| Sritis | Baigtumas | Automatizavimas | Būsenos aprašymas ir integracijos |
| :--- | :---: | :---: | :--- |
| Duomenų šaltiniai (56 skriptai) | 100% | 100% | Visi 56 skriptai visiškai integruoti: sąskaitų tiekėjų portalai, registrų archyvai, teisinių dokumentų saugyklos, akcininkų duomenų bazės ir verslo subjektų klasifikatoriai veikia nepertraukiamai. |
| Pirmi pilni įkėlimai | 100% | 100% | Visi istoriniai duomenys įkelti: patentai, visos 14 leidimų rūšių, finansinės ataskaitos, viešųjų pirkimų archyvai bei viešųjų skelbimų tekstai; kasdienis atnaujinimas veikia pilna apimtimi. |
| Duomenų kokybė | 100% | 100% | Įdiegti tikrinimo algoritmai ir x žingsniai su momentiniais įspėjimais; visos sumų valymo ir formatavimo taisyklės pritaikytos. |
| Įmonės puslapis | 100% | 100% | Pilna ~30 sekcijų struktūra realizuota be jokių trūkumų; visi galimi duomenys iš šaltinių atvaizduojami realiu laiku. |
| Sąrašai, reitingai, statistika | 100% | 100% | Visos suvestinės skaičiuojamos automatiškai, prižiūrint administratoriams, bei buhalteriams; veikia visi pirkimų klasifikatorių filtrai bei sąskaitų archyvų atvaizdavimas. |
| Paskyros, planai, mokėjimai | 100% | 100% | Visi narystės planai integruoti su mokėjimų sistemomis; pilnai įdiegta 2FA autorizacija, API raktų saugi maiša bei slaptažodžio keitimo politika. |
| Naujienos  | 100% | 100% | Tvarko realūs autoriai. Moderatoriai tvarko naujienas, redaktorių. |
| SEO optimizacija | 100% | 100% | Visi puslapiai sėkmingai indeksuoti paieškos sistemose; pilnai atlikta raktažodžių bei konkurentų analizė ir taikomas automatinis sitemap atnaujinimas. |
| Kaštai ir priežiūra | 100% | 100% | Automatiniai įspėjimai ir infrastruktūros resursų valdymas; sąskaitų ir duomenų bazių ribų stebėjimas vyksta automatiškai. |
---

## Sisteminiai procesai

Duomenų surinkimo ir apdorojimo grandinė (*ingestion pipeline*) suprojektuota taip, kad užtikrintų autonominį veikimą be papildomų palaikymo kaštų:

1. **Duomenų surinkimas ir valymas:** Nepertraukiamas 56 šaltinių duomenų nuskaitymas, triukšmo šalinimas, verčių formatavimas ir struktūrizavimas.
2. **Sinchronizavimas ir suvestinių skaičiavimas:** Automatinis išvalytų duomenų įrašymas į saugyklas bei verslo analitikos rodiklių perskaičiavimas realiu laiku.
3. **Archyvavimas ir atsarginės kopijos:** Suplanuotas duomenų bazių snapšotų kūrimas ir saugus archyvavimas nustatytais ciklais.
4. **Notifikacijos ir sisteminė stebėsena:** Naujienų platinimas prenumeratoriams bei nepertraukiamas klaidų ir sutrikimų stebėjimas.

---

## Operacinis pasiruošimas ir kontrolė

* **Didelės apimties duomenų valdymas:** Optimizuotos užklausos leidžia apdoroti masinius duomenų įkėlimus nepatiriant sistemos lėtėjimo.
* **Prieigos teisių ir narystės valdymas:** Vartotojų narystės planai, autorizacija bei teisių suteikimas veikia per suderintus integracinius modulius.
* **Savikontrolė ir klaidų šalinimas:** Integruota grandinė automatiškai tikrina duomenų vientisumą ir generuoja įspėjimus.

---

## Technologinė architektūra

* **Frontend:** HTML5, Tailwind CSS, Inter Font, FontAwesome piktogramos, adaptyvus dizainas (šviesios ir tamsios temos palaikymas).
* **SEO ir semantika:** Schema.org (JSON-LD `TechArticle`), Open Graph, Twitter Cards, automatinis `sitemap.xml` generavimas.
* **Backend ir duomenys:** 56 integraciniai skriptai, 14 leidimų rūšių klasifikatoriai, finansinių ataskaitų ir viešųjų pirkimų archyvavimas.

---

## Gamybinė aplinka ir nuorodos

Projekto rezultatus ir veikiančią platformą galite peržiūrėti adresu:

👉 **[https://rekvizitai24.lt](https://rekvizitai24.lt)**

---

© 2026 Lietuvos verslo ir duomenų analitikos platforma. Visos teisės saugomos.
