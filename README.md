# 📊 Müügianalüüsi raport - UrbanStyle

Selle projekti raames teostasin põhjaliku müügianalüüsi, kasutades SQL päringuid (CTE-d, agregeerimine, filtreerimine), et selgitada välja UrbanStyle'i äritulemused ja kasvuvõimalused.

## 1. Ülevaade põhinäitajatest (KPI-d)

* **Aasta kogukäive:** 2 190 113,51 €
* **Tellimuste koguarv:** 7 658 tehingut
* **Keskmine tellimuse väärtus (AOV):** 285,99 €


## 2. Müügitrendid ja sesoonsus (CTE analüüs)

Analüüs näitas selget sesoonsust ja pühade mõju müügitulemustele:

* **🥇 Parim kuu:** Detsember (käive **260 334,11 €**). Märkimisväärne **61,46% kasv** võrreldes novembriga.
* **📈 Suurim kasvuhüpe:** Juunikuus kasvas käive **30,47%** (220 496,63 €), mis viitab edukale suvehooaja algusele.
* **📉 Madalseis:** Jaanuar oli aasta madalaim punkt (**124 091,22 €**), mis on ootuspärane pühadejärgne langus.


## 3. Kategooriate analüüs (GROUP BY & HAVING)

| Kategooria | Müükide arv | Kogukäive (€) | Keskmine hind (€) |
| :--- | :---: | :---: | :---: |
| **Jalanõud**      | 1 521 | 584 498,35 | 384,29 |
| **Meeste riided** | 1 751 | 572 289,41 | 326,84 |
| **Naiste riided** | 1 529 | 501 821,92 | 328,20 |
| **Aksessuaarid**  | 1 292 | 298 010,80 | 230,66 |
| **Laste riided**  | 1 565 | 233 493,03 | 149,20 |

### Olulisemad tähelepanekud:
* **Top kategooria:** Jalanõud on peamine tuluallikas ja kõrgeima keskmise tehinguväärtusega.
* **Kliendimagnet:** Meeste riided genereerivad kõige rohkem tehinguid (1751), olles peamine mahtude tooja.


## 💡 Strateegilised soovitused juhatusele

1.  **Fookus jalanõudele:** Kuna jalanõude keskmine hind on üle 2,5 korra kõrgem kui lasteriietel, on see kõige tulusam segment täiendavateks investeeringuteks.
2.  **Sesoonsuse ära kasutamine:** Detsembri tugev tulemus kinnitab kampaaniate efektiivsust. Sarnast mudelit tuleks rakendada juunis, et võimendada suvist tõusutrendi.
