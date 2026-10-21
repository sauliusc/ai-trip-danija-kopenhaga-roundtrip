# Perleidimas nuo žingsnio „Maistas ir barai“ — 2026-10-21 20:15:58 UTC

- **Kelionė:** `d85b1e13fecc`
- **Pradžia / pabaiga:** 2026-10-21 20:15:58 → 20:37:33 (21 min.)
- **Agentų rinkinys:** Base
- **Rezultatas:** ❌ Nepavyko
- **Klaida:** Page Designer did not return a complete HTML document: 'atidarote (10:00 žiemą), gražiausia palaukti pasivaikščiojant po Kongens Have parką prie pat pilies.</li>\n    <li>🕐 <strong>Laiko pakeitimas:</strong> naktį tarp šeštadienio ir sekmadienio (spalio 24–25 d.) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal, patikrinkite, ar telefo'

## Eiga

- `20:15:58` Perleidžiama nuo žingsnio: food...
- `20:15:58` Maistas, vietiniai patiekalai ir barai...
- `20:22:39` Orų prognozė...
- `20:22:40` Planas B: įvestis nepasikeitė -- naudojamas ankstesnis rezultatas.
- `20:22:40` Daiktų sąrašas...
- `20:23:38` Biudžeto skaičiavimas...
- `20:25:38` Puslapio atnaujinimas (dizainas išlaikomas)...
- `20:37:33` Nepavyko: Page Designer did not return a complete HTML document: 'atidarote (10:00 žiemą), gražiausia palaukti pasivaikščiojant po Kongens Have parką prie pat pilies.</li>\n    <li>🕐 <strong>Laiko pakeitimas:</strong> naktį tarp šeštadienio ir sekmadienio (spalio 24–25 d.) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal, patikrinkite, ar telefo'

## Agentų kvietimai (4)

### 1. Maistas ir barai — 20:22:35 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 396.8 s
- **Sistemos promptas:** `prompts/food.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Danija (Kopenhaga)",
  "trip_type": "roundtrip",
  "start_date": "2026-10-23",
  "end_date": "2026-10-26",
  "travelers": 4,
  "budget_eur": null,
  "airport": "CPH",
  "return_flight_time": "15:15",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "kultūra",
    "maistas"
  ],
  "language": "lt",
  "notes": "Automobilis nebus nuomojamas — tikslas aplankyti objektus pasiekiamus tik pėsčiomis arba viešuoju transportu. Kelionės planą sudėlioti atsižvelgiant į numatomus orus (lauko/vidaus objektų santykis). Pridėti rekomenduojamo maisto vietas. Nakvynė: Saint - Nice 1-Bdr Apt by the Canals, København, Denmark, 1416. 2026-10-25 vakare Deep Purple koncertas Kopenhagoje (įtraukti į planą). Skrydis KUN→CPH 2026-10-23 išvykimas 09:10, atvykimas 09:40 vietos laiku; skrydis CPH→KUN 2026-10-26 išvykimas 15:15, atvykimas 17:45 vietos laiku."
}
```

**Itinerary:**

```json
{
  "days": [
    {
      "number": 1,
      "title": "Atvykimas ir Christianshavn",
      "stops": [
        {
          "name": "Kopenhagos oro uostas (CPH)",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "09:40",
          "depart": "10:00",
          "maps_query": "Copenhagen Airport (CPH), Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark",
          "notes": "Atvykimo skrydis iš Kauno. Atsiėmę bagažą, metro stotelėje nusipirkite bilietus Rejsebillet programėlėje arba automate (fizinis Rejsekort pamažu nebenaudojamas).",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Apartamentai Sanders Saint-Nice (Christianshavn)",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "10:16",
          "depart": "10:45",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Įsikurkite ir palikite bagažą – butas 3 min pėsčiomis nuo Christianshavn metro stotelės.",
          "arrive_by": "transit",
          "transit": "Metro M2: Lufthavnen → Christianshavn (tiesioginis, ~14 min)"
        },
        {
          "name": "Vor Frelsers Kirke (bokštas)",
          "lat": 55.673,
          "lon": 12.5942,
          "arrive": "10:55",
          "depart": "12:45",
          "maps_query": "Vor Frelsers Kirke, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Vor%20Frelsers%20Kirke%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Garsieji išorės sukasi laiptai su vaizdu į Christianshavn. Bokštas kasdien 09:00–20:00 (gali uždaryti stiprų vėją/lietų – jei taip, apžiūrėkite tik bažnyčią). Bilietas į bokštą ~70 DKK. Dviračių takai (cykelsti) – niekada jais neikite pėsčiomis.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Pietūs – Christianshavns Bådudlejning og Café",
          "lat": 55.6757,
          "lon": 12.592,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Christianshavns Bådudlejning og Café, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Jaukus kavinė tiesiai prie kanalo – geras smørrebrød ir vietinis alus.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nyhavn (diena)",
          "lat": 55.6799,
          "lon": 12.5898,
          "arrive": "14:20",
          "depart": "15:30",
          "maps_query": "Nyhavn, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Spalvingas kanalo krantas su laivais – klasikinė Kopenhagos atvirutė. Nemokama.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Amalienborg (kiemas, sargybos namai)",
          "lat": 55.684,
          "lon": 12.5933,
          "arrive": "15:40",
          "depart": "16:05",
          "maps_query": "Amalienborg, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Amalienborg%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karališkoji rezidencija – sargybos keitimas vyksta apie vidurdienį, bet kiemas gražus bet kuriuo metu. Muziejų aplankysime kitą rytą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Den Lille Havfrue (Mažoji jūrų nimfa)",
          "lat": 55.6929,
          "lon": 12.5993,
          "arrive": "16:25",
          "depart": "16:45",
          "maps_query": "Den Lille Havfrue, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Den%20Lille%20Havfrue%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Nedidelė, bet ikoniška skulptūra – trumpas vizitas užtenka. Popietė mažiau minios nei rytais, kai atvažiuoja turistų autobusai.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nyhavn vakare ir vakarienė (Nyhavns Færgekro)",
          "lat": 55.6797,
          "lon": 12.5905,
          "arrive": "17:10",
          "depart": "19:30",
          "maps_query": "Nyhavns Færgekro, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavns%20F%C3%A6rgekro%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Saulei nusileidus (~17:15) kanalas gražiausias apšviestas. Vakarienė tradicinėje danų restorane – rekomenduojamas smørrebrød ir žuvies patiekalai.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Grįžimas į apartamentus",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "19:50",
          "depart": "20:00",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Nakvynė Christianshavn.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 2,
      "title": "Pilys ir muziejai",
      "stops": [
        {
          "name": "Rosenborg Slot",
          "lat": 55.6857,
          "lon": 12.5777,
          "arrive": "09:35",
          "depart": "11:00",
          "maps_query": "Rosenborg Slot, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Rosenborg%20Slot%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karūnos brangenybės ir karališkoji istorija. Žiemos darbo laikas (spalis–kovas) 10:00–16:00. Bilietas ~140 DKK, nemokamai <18 m.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 18 min pėsčiomis iki pilies (arba pasivaikščiokite po Kongens Have parką prieš atidarymą)"
        },
        {
          "name": "SMK – Statens Museum for Kunst",
          "lat": 55.6896,
          "lon": 12.5799,
          "arrive": "11:12",
          "depart": "12:40",
          "maps_query": "SMK - Statens Museum for Kunst, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=SMK%20-%20Statens%20Museum%20for%20Kunst%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Danijos nacionalinė dailės galerija. Šeštadienį dirba 10:00–18:00. Bilietas ~140 DKK, nemokamai <18 m.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Pietūs – Torvehallerne",
          "lat": 55.6839,
          "lon": 12.5705,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Torvehallerne, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Torvehallerne%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Geriausia maisto turgavietė mieste – rekomenduojama Hallernes Smørrebrød prekystalis tradiciniam smørrebrød. Įėjimas nemokamas, mokama už prekes.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Christiansborg Slot",
          "lat": 55.6761,
          "lon": 12.5789,
          "arrive": "14:30",
          "depart": "16:00",
          "maps_query": "Christiansborg Palace, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christiansborg%20Palace%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Danijos parlamento būstinė, karališkosios reprezentacinės salės ir pilies griuvėsiai. Kasdien 10:00–17:00. Bilietas ~215 DKK internetu / 225 DKK vietoje, nemokamai <18 m.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nationalmuseet",
          "lat": 55.6751,
          "lon": 12.5748,
          "arrive": "16:05",
          "depart": "17:00",
          "maps_query": "Nationalmuseet, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nationalmuseet%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Didžiausias Danijos muziejus, vikingų ir priešistorės kolekcijos. Dirba kasdien 10:00–17:00. Bilietas ~150 DKK – patikrinkite prie kasos, kai kurie šaltiniai teigia, kad nuolatinė ekspozicija nemokama.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Vakarienė – Ved Kanalen",
          "lat": 55.6745,
          "lon": 12.592,
          "arrive": "18:00",
          "depart": "19:30",
          "maps_query": "Ved Kanalen, Overgaden Neden Vandet, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ved%20Kanalen%2C%20Overgaden%20Neden%20Vandet%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Aukštai vertinamas tradicinis danų restoranas tiesiai prie kanalo, netoli nakvynės vietos.",
          "arrive_by": "walk",
          "transit": ""
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 3,
      "title": "Christiania, Tivoli ir Deep Purple koncertas",
      "stops": [
        {
          "name": "Freetown Christiania",
          "lat": 55.6738,
          "lon": 12.5983,
          "arrive": "09:20",
          "depart": "11:00",
          "maps_query": "Freetown Christiania, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Freetown%20Christiania%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Savivaldi alternatyvi bendruomenė, gatvės menas. Lankykite tik dienos metu. Pusher Street – nefotografuokite, laikykitės taisyklių. Nemokama. Šiąnakt (spalio 25-osios naktį) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Ny Carlsberg Glyptotek",
          "lat": 55.6735,
          "lon": 12.5727,
          "arrive": "11:25",
          "depart": "12:50",
          "maps_query": "Ny Carlsberg Glyptotek, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ny%20Carlsberg%20Glyptotek%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Antikos ir impresionistų kolekcija, žiemos sodas po stiklo kupolu. Sekmadienį dirba 10:00–17:00. Bilietas ~125 DKK.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv, persėdimas į M3 → Rådhuspladsen (~18 min iš viso), toliau 5 min pėsčiomis"
        },
        {
          "name": "Pietūs – Tivoli Food Hall",
          "lat": 55.673,
          "lon": 12.5678,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Tivoli Food Hall, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tivoli%20Food%20Hall%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Pietūs Tivoli sodų maisto salėje – įskaičiuota į bendrą Tivoli bilietą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Tivoli Gardens (Helovino tema)",
          "lat": 55.6736,
          "lon": 12.5681,
          "arrive": "14:00",
          "depart": "16:00",
          "maps_query": "Tivoli Gardens, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tivoli%20Gardens%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Istorinis pramogų parkas, per visą kelionę vyksta Helovino sezonas su 20 000 moliūgų dekoracijų. Vartai 11:00–23:00. Bilietas ~200 DKK suaugusiam.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Vakarienė – Field's",
          "lat": 55.6269,
          "lon": 12.5751,
          "arrive": "16:25",
          "depart": "17:45",
          "maps_query": "Field's, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Field%27s%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Didelis prekybos centras su maisto kiemeliu prie pat arenos – patogu prieš koncertą.",
          "arrive_by": "transit",
          "transit": "Traukinys/S-tog: København H → Ørestad (~7 min), toliau 5 min pėsčiomis"
        },
        {
          "name": "Royal Arena – Deep Purple koncertas",
          "lat": 55.6256,
          "lon": 12.5732,
          "arrive": "17:50",
          "depart": "22:00",
          "maps_query": "Royal Arena, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Royal%20Arena%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Durys atsidaro ~18:00, koncerto pradžia orientaciniai ~19:00–20:00 (patikslinti artimiau datai livenation.dk). Dėl vasaros laiko pabaigos šią naktį patikrinkite vėlyvo metro tvarkaraštį grįžtant.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Grįžimas į apartamentus",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "22:20",
          "depart": "22:30",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Po koncerto grįžtama tiesioginiu metro. Patikrinkite paskutinio traukinio laiką.",
          "arrive_by": "transit",
          "transit": "Metro M1: Ørestad → Christianshavn (~20 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 4,
      "title": "Amalienborg, Nyhavn ir skrydis namo",
      "stops": [
        {
          "name": "Amalienborg Museum",
          "lat": 55.684,
          "lon": 12.5933,
          "arrive": "09:50",
          "depart": "11:00",
          "maps_query": "Amalienborg Museum, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Amalienborg%20Museum%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karališkųjų apartamentų interjerai. Prieš lapkričio 1 d. pirmadieniais dirba 10:00–15:00. Bilietas ~125 DKK internetu / 135 DKK vietoje, nemokamai <18 m.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 8 min pėsčiomis"
        },
        {
          "name": "Nyhavn (paskutinis apsilankymas)",
          "lat": 55.6799,
          "lon": 12.5898,
          "arrive": "11:10",
          "depart": "11:50",
          "maps_query": "Nyhavn, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Trumpas laikas suvenyrams ir paskutinėms nuotraukoms prie kanalo.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Apartamentai – bagažas ir išsiregistravimas",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "12:00",
          "depart": "12:20",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Atsiimkite bagažą ir išsiregistruokite.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)"
        },
        {
          "name": "Kopenhagos oro uostas (CPH) – pietūs ir skrydis",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "12:40",
          "depart": "15:15",
          "maps_query": "Copenhagen Airport (CPH), Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark",
          "notes": "Grįžtamasis skrydis CPH→KUN išvyksta 15:15. Pietus patogu užkąsti pačiame oro uoste – daug kavinių ir restoranų abipus saugumo patikros. Rekomenduojama iš anksto atlikti registraciją internetu, liks pakankamai laiko bagažo pridavimui ir saugumo patikrai.",
          "arrive_by": "transit",
          "transit": "Metro M2: Christianshavn → Lufthavnen (tiesioginis, ~14 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kaunas"
    }
  ]
}
```

Accommodation:
## Nakvynė — Kopenhaga (2026-10-23 → 2026-10-26, 3 naktys, viena stotelė)

Kelionėje automobilis nenuomojamas, todėl prioritetas – greta stotelės/metro ir centro. Svečiai jau nurodė konkretų, rezervuotą butą, tad jį pateikiu kaip pagrindinį variantą ir pridedu 2 atsargines alternatyvas tuo atveju, jei rezervacija nepatvirtinta arba reikėtų keisti.

### 1. Sanders Saint-Nice 1-Bdr Apt by the Canals (jau pasirinkta/nurodyta keliautojo)
- **Kaina**: ~$158/naktis (Expedia duomenys, apytiksliai €135–145/naktis priklausomai nuo kurso — tiksli kaina priklauso nuo rezervacijos platformos ir datų, netikrinta tiesiogiai EUR)
- **Kodėl tinka**: Christianshavn rajone, prie kanalų, 1 min. nuo Vor Frelsers Kirke (bokštas suderintas su kultūros prioritetu); **3 min pėsčiomis iki Christianshavn metro stoties (M1/M2)** — puikiai tinka be automobilio; ~15 min pėsčiomis iki Nyhavn/Strøget. Virtuvėlė su indaplove ir orkaite, interneto prieiga, centrinis šildymas.
- **Pastaba**: skelbiamas kaip "1-Bdr" (1 miegamasis) — jei kelionėje 4 keliautojai, verta patvirtinti miegamųjų vietų skaičių prieš galutinį patvirtinimą.
- **Booking nuorodos**: [Tripadvisor](https://www.tripadvisor.com/VacationRentalReview-g189541-d18852743-Sanders_Saint_Nice_1_Bdr_Apt_By_the_Canals-Copenhagen_Zealand.html) · [Expedia](https://www.expedia.com/Copenhagen-Hotels-Cozy-Apartment-In-Christianshavn.h45157366.Hotel-Information) · [Hotels.com](https://hotels.com/ho1446035712/cozy-apartment-in-christianshavn-copenhagen-copenhagen-denmark)

### 2. Central Canal Apartments (Christianshavn) — atsarginis variantas
- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai
- **Kodėl tinka**: tame pačiame Christianshavn rajone prie kanalų, ~15 min pėsčiomis iki Strøget; kelios butų kategorijos, galimai tinka 4 žmonėms.
- **Nuoroda**: [copenhagen-hotel.org](https://www.copenhagen-hotel.org/en/property/central-canal-apartments.html)

### 3. CABINN Apartments — atsarginis variantas
- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai (CABINN tinklas paprastai priklauso biudžetinei/vidutinei kategorijai)
- **Kodėl tinka**: 4 asmenų 2 kambarių butas, **greta metro stoties**, pusryčiai siūlomi gretimame CABINN Metro (05:30–10:00 darbo dienomis, 06:00–10:30 savaitgaliais) — atitinka "pusryčiai įskaičiuoti" prioritetą, kurio pirmasis variantas neturi patvirtinto.
- **Nuoroda**: [CABINN Apartments](https://en.cabinn.com/hotel/cabinn-apartments)

**Neatitikimai/rizikos**: Nei vienam variantui nepavyko rasti patvirtintos kainos EUR valiuta tiesiogiai iš rezervacijos sistemos konkrečioms 2026-10-23–26 datoms — rekomenduoju patikrinti kainą ir laisvas vietas (ypač miegamųjų skaičių pagrindiniame bute) booking.com/Expedia tiesiogiai prieš galutinį patvirtinimą.

```json
{"picks": [{"city": "Kopenhaga", "name": "Sanders Saint-Nice 1-Bdr Apt by the Canals", "checkin": "2026-10-23", "checkout": "2026-10-26", "price_per_night_eur": 140}]}
```

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "eateries": [
    {
      "name": "Christianshavns Bådudlejning og Café",
      "address": "Overgaden Neden Vandet 29, 1414 København K",
      "city": "Kopenhaga",
      "day": 1,
      "near": "Pietų stotelė maršrute, 2 min nuo Vor Frelsers Kirke",
      "kind": "kanalo kavinė valčių nuomos punkte",
      "local_cuisine": true,
      "avg_price_eur": 20,
      "dinner_price_eur": 28,
      "must_try": [
        {
          "name": "Smørrebrodų rinkinys",
          "local_name": "Smørrebrød",
          "price_eur": 18,
          "commons_filename": "Smørrebrød in Copenhagen 01.jpg"
        },
        {
          "name": "Æbleskiver su uogiene ir cukraus pudra",
          "local_name": "Æbleskiver",
          "price_eur": 9,
          "commons_filename": "Aebleskiver.jpg"
        },
        {
          "name": "Lašišos salotos",
          "local_name": "Laksesalat",
          "price_eur": 15,
          "commons_filename": ""
        }
      ],
      "why": "Veikia nuo 1905 m., jauki kavinė tiesiai ant kanalo su valčių nuoma – gera vieta atsipūsti po bokšto lipimo Vor Frelsers Kirke."
    },
    {
      "name": "Nyhavns Færgekro",
      "address": "Nyhavn 5, 1051 København K",
      "city": "Kopenhaga",
      "day": 1,
      "near": "Vakarienės stotelė Nyhavn vakare",
      "kind": "tradicinė danų krogė (taverna)",
      "local_cuisine": true,
      "avg_price_eur": 28,
      "dinner_price_eur": 38,
      "must_try": [
        {
          "name": "Silkių bufetas (10+ rūšių)",
          "local_name": "Sildebuffet",
          "price_eur": 25,
          "commons_filename": "Sild.jpg"
        },
        {
          "name": "Krintanti žvaigždė (žuvies smørrebrodas)",
          "local_name": "Stjerneskud",
          "price_eur": 20,
          "commons_filename": "Stjerneskud (Bruun's Galleri).jpg"
        },
        {
          "name": "Namų gamybos akvavitas",
          "local_name": "Akvavit",
          "price_eur": 6,
          "commons_filename": ""
        }
      ],
      "why": "Vienas geriausių kainos/kokybės santykių Nyhavn kanalo pakrantėje – garsus savo silkių bufetu ir terasa prie vandens saulėlydžio metu."
    },
    {
      "name": "Hallernes Smørrebrød (Torvehallerne)",
      "address": "Frederiksborggade 21, 1360 København K (Torvehallerne, Hal 1)",
      "city": "Kopenhaga",
      "day": 2,
      "near": "Pietų stotelė Torvehallerne turgavietėje",
      "kind": "turgavietės smørrebrodo prekystalis",
      "local_cuisine": true,
      "avg_price_eur": 16,
      "dinner_price_eur": 22,
      "must_try": [
        {
          "name": "Krevetių smørrebrodas",
          "local_name": "Rejestykke",
          "price_eur": 17,
          "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
        },
        {
          "name": "Jautienos tataras",
          "local_name": "Tatar",
          "price_eur": 14,
          "commons_filename": "Steak Tartare in Dresden.jpg"
        },
        {
          "name": "Kepta kiauliena su spirgučiais",
          "local_name": "Flæskesteg",
          "price_eur": 13,
          "commons_filename": "Flaeskesteg med svaer.jpg"
        }
      ],
      "why": "Geriausios reputacijos smørrebrodo prekystalis mieste, tiesiai turgavietėje tarp šviežios žuvies ir sūrių prekystalių."
    },
    {
      "name": "Restaurant Kanalen",
      "address": "Wilders Plads 2, 1403 København K",
      "city": "Kopenhaga",
      "day": 2,
      "near": "Vakarienės stotelė Ved Kanalen, 5 min nuo nakvynės Christianshavn",
      "kind": "aukštesnės klasės danų-prancūziška virtuvė (Michelin Plate)",
      "local_cuisine": true,
      "avg_price_eur": 55,
      "dinner_price_eur": 65,
      "must_try": [
        {
          "name": "Sezoninis degustacinis meniu (3 patiekalai)",
          "local_name": "Menu",
          "price_eur": 47,
          "commons_filename": ""
        },
        {
          "name": "Sūris su traškia duona",
          "local_name": "Ost med sprødt brød",
          "price_eur": 7,
          "commons_filename": ""
        },
        {
          "name": "Šokoladinis panna cotta",
          "local_name": "Chokolade panna cotta",
          "price_eur": 11,
          "commons_filename": ""
        }
      ],
      "why": "Michelin gide pažymėtas restoranas tiesiai ant Christianshavn kanalo kranto – atmosfera atpalaiduojanti, be snobizmo, nepaisant apdovanojimo."
    },
    {
      "name": "Tivoli Food Hall",
      "address": "Bernstorffsgade 3, 1577 København V (Tivoli Gardens)",
      "city": "Kopenhaga",
      "day": 3,
      "near": "Pietų stotelė prieš Tivoli Gardens",
      "kind": "maisto salė su 15-20 prekystalių",
      "local_cuisine": true,
      "avg_price_eur": 16,
      "dinner_price_eur": 20,
      "must_try": [
        {
          "name": "Klasikinis danų dešrainis su traškiais svogūnais",
          "local_name": "Ristet hotdog (Tivoligrillen)",
          "price_eur": 7,
          "commons_filename": ""
        },
        {
          "name": "Krevetių smørrebrodas",
          "local_name": "Rejemad (Hallernes Smørrebrød)",
          "price_eur": 17,
          "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
        },
        {
          "name": "Lašišos smørrebrodas",
          "local_name": "Laksemad",
          "price_eur": 16,
          "commons_filename": ""
        }
      ],
      "why": "Įvairiausių danų greito maisto prekystalių rinkinys viename stogo po – praktiška pietų pertrauka tarp Christiania ir Tivoli."
    },
    {
      "name": "Field's",
      "address": "Arne Jacobsens Allé 12, 2300 København S",
      "city": "Kopenhaga",
      "day": 3,
      "near": "Vakarienės stotelė prieš Royal Arena koncertą",
      "kind": "prekybos centro maisto kiemelis",
      "local_cuisine": false,
      "avg_price_eur": 14,
      "dinner_price_eur": 16,
      "must_try": [
        {
          "name": "Burgeris (Sunset Boulevard, danų tinklas)",
          "local_name": "Original burger",
          "price_eur": 10,
          "commons_filename": ""
        },
        {
          "name": "Bulvytės",
          "local_name": "Pommes frites",
          "price_eur": 5,
          "commons_filename": ""
        },
        {
          "name": "Sumuštinis (Joe & The Juice)",
          "local_name": "Sandwich",
          "price_eur": 8,
          "commons_filename": ""
        }
      ],
      "why": "Ne tradicinė virtuvė, bet greitas ir patikimas pasirinkimas prieš koncertą – daug prekystalių vos prie pat arenos."
    },
    {
      "name": "Aamanns Deli & Take Away (CPH oro uostas)",
      "address": "Copenhagen Airport, Terminal 3, 2770 Kastrup",
      "city": "Kopenhaga",
      "day": 4,
      "near": "Pietų ir laukimo laikas prieš skrydį CPH→KUN",
      "kind": "smørrebrodo parduotuvė oro uoste",
      "local_cuisine": true,
      "avg_price_eur": 14,
      "dinner_price_eur": 18,
      "must_try": [
        {
          "name": "Silkės smørrebrodas",
          "local_name": "Sildemad",
          "price_eur": 11,
          "commons_filename": "Sild.jpg"
        },
        {
          "name": "Krevetių smørrebrodas",
          "local_name": "Rejemad",
          "price_eur": 15,
          "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
        },
        {
          "name": "Rostbifo smørrebrodas",
          "local_name": "Roastbeefmad",
          "price_eur": 13,
          "commons_filename": ""
        }
      ],
      "why": "Geriausiai vertinama tradicinio smørrebrodo vieta oro uoste – paskutinė galimybė paragauti danų virtuvės prieš skrydį namo."
    }
  ],
  "dishes": [
    {
      "name": "Smørrebrodas",
      "local_name": "Smørrebrød",
      "description": "Atviras ruginės duonos sumuštinis su įvairiais priedais (silke, kiauliena, krevetėmis, kiaušiniu) – danų kasdienio maisto pagrindas.",
      "price_eur_min": 9,
      "price_eur_max": 18,
      "where_to_try": [
        "Christianshavns Bådudlejning og Café",
        "Nyhavns Færgekro",
        "Hallernes Smørrebrød (Torvehallerne)",
        "Tivoli Food Hall",
        "Aamanns Deli & Take Away (CPH oro uostas)"
      ],
      "commons_filename": "Smørrebrød in Copenhagen 01.jpg"
    },
    {
      "name": "Marinuota silkė",
      "local_name": "Sild",
      "description": "Marinuota silkė ant ruginės duonos, dažnai siūloma keliomis padažų versijomis – klasikinis danų užkandis prie akvavito.",
      "price_eur_min": 10,
      "price_eur_max": 15,
      "where_to_try": [
        "Nyhavns Færgekro",
        "Aamanns Deli & Take Away (CPH oro uostas)"
      ],
      "commons_filename": "Sild.jpg"
    },
    {
      "name": "Krintanti žvaigždė",
      "local_name": "Stjerneskud",
      "description": "Šventinis smørrebrodas su kepta ir virta žuvimis, krevetėmis, majonezu ir ikrais – vienas populiariausių restoranų patiekalų.",
      "price_eur_min": 15,
      "price_eur_max": 22,
      "where_to_try": [
        "Hallernes Smørrebrød (Torvehallerne)",
        "Nyhavns Færgekro"
      ],
      "commons_filename": "Stjerneskud (Bruun's Galleri).jpg"
    },
    {
      "name": "Frikadelės",
      "local_name": "Frikadeller",
      "description": "Kiaulienos ir jautienos maltinukai, patiekiami su ruginę duona ir raudonaisiais kopūstais arba bulvėmis – namų virtuvės klasika.",
      "price_eur_min": 12,
      "price_eur_max": 18,
      "where_to_try": [
        "Nyhavns Færgekro",
        "Restaurant Kanalen"
      ],
      "commons_filename": "Flickr - cyclonebill - Frikadeller med ristet rugbrød og cornichons.jpg"
    },
    {
      "name": "Kepta kiauliena su spirgučiais",
      "local_name": "Flæskesteg",
      "description": "Keptas kiaulienos sprandinė su traškia odele, patiekiama su raudonaisiais kopūstais ir bulvėmis – tradicinis šventinis patiekalas.",
      "price_eur_min": 13,
      "price_eur_max": 18,
      "where_to_try": [
        "Hallernes Smørrebrød (Torvehallerne)",
        "Nyhavns Færgekro"
      ],
      "commons_filename": "Flaeskesteg med svaer.jpg"
    },
    {
      "name": "Æbleskiver blyneliai",
      "local_name": "Æbleskiver",
      "description": "Apvalūs, pūsti blyneliai, keliami specialioje keptuvėje, patiekiami su uogiene ir cukraus pudra – populiarūs rudens/žiemos sezonu.",
      "price_eur_min": 6,
      "price_eur_max": 10,
      "where_to_try": [
        "Christianshavns Bådudlejning og Café",
        "Tivoli Food Hall"
      ],
      "commons_filename": "Aebleskiver.jpg"
    },
    {
      "name": "Danų dešrainis",
      "local_name": "Ristet hotdog",
      "description": "Keptas dešrainis su traškiais svogūnais, raugintais agurkais, garstyčiomis ir remulado padažu – gatvės maisto klasika.",
      "price_eur_min": 6,
      "price_eur_max": 9,
      "where_to_try": [
        "Tivoli Food Hall",
        "Field's"
      ],
      "commons_filename": ""
    },
    {
      "name": "Dano pyragaitis",
      "local_name": "Wienerbrød / kanelsnegl",
      "description": "Sluoksniuotos tešlos pyragaitis, dažniausiai su cinamonu ar vaisių įdaru – rytinis ar popietinis skanėstas su kava.",
      "price_eur_min": 4,
      "price_eur_max": 6,
      "where_to_try": [
        "Tivoli Food Hall",
        "Aamanns Deli & Take Away (CPH oro uostas)"
      ],
      "commons_filename": "Glazed apple Danish.jpg"
    }
  ],
  "bars": [
    {
      "name": "Hviids Vinstue",
      "address": "Kongens Nytorv 19, 1050 København K",
      "city": "Kopenhaga",
      "day": 1,
      "near": "Kongens Nytorv / Nyhavn",
      "why_special": "Kopenhagos seniausias nenutrūkstamai veikiantis baras, įkurtas 1723 m. – tamsaus medžio interjeras, žvakės ir senųjų menininkų portretai, matęs didžiuosius miesto gaisrus ir du pasaulinius karus."
    }
  ]
}
```

</details>

### 2. Daiktai — 20:23:38 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 57.6 s
- **Sistemos promptas:** `prompts/packing.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Danija (Kopenhaga)",
  "trip_type": "roundtrip",
  "start_date": "2026-10-23",
  "end_date": "2026-10-26",
  "travelers": 4,
  "budget_eur": null,
  "airport": "CPH",
  "return_flight_time": "15:15",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "kultūra",
    "maistas"
  ],
  "language": "lt",
  "notes": "Automobilis nebus nuomojamas — tikslas aplankyti objektus pasiekiamus tik pėsčiomis arba viešuoju transportu. Kelionės planą sudėlioti atsižvelgiant į numatomus orus (lauko/vidaus objektų santykis). Pridėti rekomenduojamo maisto vietas. Nakvynė: Saint - Nice 1-Bdr Apt by the Canals, København, Denmark, 1416. 2026-10-25 vakare Deep Purple koncertas Kopenhagoje (įtraukti į planą). Skrydis KUN→CPH 2026-10-23 išvykimas 09:10, atvykimas 09:40 vietos laiku; skrydis CPH→KUN 2026-10-26 išvykimas 15:15, atvykimas 17:45 vietos laiku."
}
```

Original request:
4 asmenų grupė vyksta į Kopenhagą. Skrydžių duomenys:
Išvykimas: Kaunas (KUN) 2026.10.23 09:10
Atvykimas: Kopenhaga (CPH) 09:40 (vietos laiku, -1 val. skirtumas)
Trukmė: 1 val. 30 min.Kelionės pabaiga:
Išvykimas: Kopenhaga (CPH) 2026.10.26 15:15
Atvykimas: Kaunas (KUN) 17:45 (vietos laiku, +1 val. skirtumas)
Trukmė: 1 val. 30 min. Gyvenamos vietos aprašymas:Saint - Nice 1-Bdr Apt by the Canals
København, Denmark, 1416 2026.10.25 vakare vyks  Deep Purple koncertasSugeneruok visą  atostogų planą.  Automobilis nebus  nuomojamas.  Tikslas aplankyti objektus  pasiekiamus pėsčiomis arba viešuoju transportu. Kelionės planą sudėliok atsižvelgiant į numatomus orus (buvimo lauko.vidaus objektuose santykis)Pridėk rekomenduojamo maisto vietas

**Itinerary:**

```json
{
  "days": [
    {
      "number": 1,
      "title": "Atvykimas ir Christianshavn",
      "stops": [
        {
          "name": "Kopenhagos oro uostas (CPH)",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "09:40",
          "depart": "10:00",
          "maps_query": "Copenhagen Airport (CPH), Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark",
          "notes": "Atvykimo skrydis iš Kauno. Atsiėmę bagažą, metro stotelėje nusipirkite bilietus Rejsebillet programėlėje arba automate (fizinis Rejsekort pamažu nebenaudojamas).",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Apartamentai Sanders Saint-Nice (Christianshavn)",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "10:16",
          "depart": "10:45",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Įsikurkite ir palikite bagažą – butas 3 min pėsčiomis nuo Christianshavn metro stotelės.",
          "arrive_by": "transit",
          "transit": "Metro M2: Lufthavnen → Christianshavn (tiesioginis, ~14 min)"
        },
        {
          "name": "Vor Frelsers Kirke (bokštas)",
          "lat": 55.673,
          "lon": 12.5942,
          "arrive": "10:55",
          "depart": "12:45",
          "maps_query": "Vor Frelsers Kirke, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Vor%20Frelsers%20Kirke%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Garsieji išorės sukasi laiptai su vaizdu į Christianshavn. Bokštas kasdien 09:00–20:00 (gali uždaryti stiprų vėją/lietų – jei taip, apžiūrėkite tik bažnyčią). Bilietas į bokštą ~70 DKK. Dviračių takai (cykelsti) – niekada jais neikite pėsčiomis.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Pietūs – Christianshavns Bådudlejning og Café",
          "lat": 55.6757,
          "lon": 12.592,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Christianshavns Bådudlejning og Café, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Jaukus kavinė tiesiai prie kanalo – geras smørrebrød ir vietinis alus.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nyhavn (diena)",
          "lat": 55.6799,
          "lon": 12.5898,
          "arrive": "14:20",
          "depart": "15:30",
          "maps_query": "Nyhavn, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Spalvingas kanalo krantas su laivais – klasikinė Kopenhagos atvirutė. Nemokama.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Amalienborg (kiemas, sargybos namai)",
          "lat": 55.684,
          "lon": 12.5933,
          "arrive": "15:40",
          "depart": "16:05",
          "maps_query": "Amalienborg, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Amalienborg%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karališkoji rezidencija – sargybos keitimas vyksta apie vidurdienį, bet kiemas gražus bet kuriuo metu. Muziejų aplankysime kitą rytą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Den Lille Havfrue (Mažoji jūrų nimfa)",
          "lat": 55.6929,
          "lon": 12.5993,
          "arrive": "16:25",
          "depart": "16:45",
          "maps_query": "Den Lille Havfrue, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Den%20Lille%20Havfrue%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Nedidelė, bet ikoniška skulptūra – trumpas vizitas užtenka. Popietė mažiau minios nei rytais, kai atvažiuoja turistų autobusai.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nyhavn vakare ir vakarienė (Nyhavns Færgekro)",
          "lat": 55.6797,
          "lon": 12.5905,
          "arrive": "17:10",
          "depart": "19:30",
          "maps_query": "Nyhavns Færgekro, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavns%20F%C3%A6rgekro%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Saulei nusileidus (~17:15) kanalas gražiausias apšviestas. Vakarienė tradicinėje danų restorane – rekomenduojamas smørrebrød ir žuvies patiekalai.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Grįžimas į apartamentus",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "19:50",
          "depart": "20:00",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Nakvynė Christianshavn.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 2,
      "title": "Pilys ir muziejai",
      "stops": [
        {
          "name": "Rosenborg Slot",
          "lat": 55.6857,
          "lon": 12.5777,
          "arrive": "09:35",
          "depart": "11:00",
          "maps_query": "Rosenborg Slot, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Rosenborg%20Slot%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karūnos brangenybės ir karališkoji istorija. Žiemos darbo laikas (spalis–kovas) 10:00–16:00. Bilietas ~140 DKK, nemokamai <18 m.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 18 min pėsčiomis iki pilies (arba pasivaikščiokite po Kongens Have parką prieš atidarymą)"
        },
        {
          "name": "SMK – Statens Museum for Kunst",
          "lat": 55.6896,
          "lon": 12.5799,
          "arrive": "11:12",
          "depart": "12:40",
          "maps_query": "SMK - Statens Museum for Kunst, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=SMK%20-%20Statens%20Museum%20for%20Kunst%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Danijos nacionalinė dailės galerija. Šeštadienį dirba 10:00–18:00. Bilietas ~140 DKK, nemokamai <18 m.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Pietūs – Torvehallerne",
          "lat": 55.6839,
          "lon": 12.5705,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Torvehallerne, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Torvehallerne%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Geriausia maisto turgavietė mieste – rekomenduojama Hallernes Smørrebrød prekystalis tradiciniam smørrebrød. Įėjimas nemokamas, mokama už prekes.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Christiansborg Slot",
          "lat": 55.6761,
          "lon": 12.5789,
          "arrive": "14:30",
          "depart": "16:00",
          "maps_query": "Christiansborg Palace, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christiansborg%20Palace%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Danijos parlamento būstinė, karališkosios reprezentacinės salės ir pilies griuvėsiai. Kasdien 10:00–17:00. Bilietas ~215 DKK internetu / 225 DKK vietoje, nemokamai <18 m.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Nationalmuseet",
          "lat": 55.6751,
          "lon": 12.5748,
          "arrive": "16:05",
          "depart": "17:00",
          "maps_query": "Nationalmuseet, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nationalmuseet%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Didžiausias Danijos muziejus, vikingų ir priešistorės kolekcijos. Dirba kasdien 10:00–17:00. Bilietas ~150 DKK – patikrinkite prie kasos, kai kurie šaltiniai teigia, kad nuolatinė ekspozicija nemokama.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Vakarienė – Ved Kanalen",
          "lat": 55.6745,
          "lon": 12.592,
          "arrive": "18:00",
          "depart": "19:30",
          "maps_query": "Ved Kanalen, Overgaden Neden Vandet, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ved%20Kanalen%2C%20Overgaden%20Neden%20Vandet%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Aukštai vertinamas tradicinis danų restoranas tiesiai prie kanalo, netoli nakvynės vietos.",
          "arrive_by": "walk",
          "transit": ""
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 3,
      "title": "Christiania, Tivoli ir Deep Purple koncertas",
      "stops": [
        {
          "name": "Freetown Christiania",
          "lat": 55.6738,
          "lon": 12.5983,
          "arrive": "09:20",
          "depart": "11:00",
          "maps_query": "Freetown Christiania, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Freetown%20Christiania%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Savivaldi alternatyvi bendruomenė, gatvės menas. Lankykite tik dienos metu. Pusher Street – nefotografuokite, laikykitės taisyklių. Nemokama. Šiąnakt (spalio 25-osios naktį) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Ny Carlsberg Glyptotek",
          "lat": 55.6735,
          "lon": 12.5727,
          "arrive": "11:25",
          "depart": "12:50",
          "maps_query": "Ny Carlsberg Glyptotek, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ny%20Carlsberg%20Glyptotek%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Antikos ir impresionistų kolekcija, žiemos sodas po stiklo kupolu. Sekmadienį dirba 10:00–17:00. Bilietas ~125 DKK.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv, persėdimas į M3 → Rådhuspladsen (~18 min iš viso), toliau 5 min pėsčiomis"
        },
        {
          "name": "Pietūs – Tivoli Food Hall",
          "lat": 55.673,
          "lon": 12.5678,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Tivoli Food Hall, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tivoli%20Food%20Hall%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Pietūs Tivoli sodų maisto salėje – įskaičiuota į bendrą Tivoli bilietą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Tivoli Gardens (Helovino tema)",
          "lat": 55.6736,
          "lon": 12.5681,
          "arrive": "14:00",
          "depart": "16:00",
          "maps_query": "Tivoli Gardens, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tivoli%20Gardens%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Istorinis pramogų parkas, per visą kelionę vyksta Helovino sezonas su 20 000 moliūgų dekoracijų. Vartai 11:00–23:00. Bilietas ~200 DKK suaugusiam.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Vakarienė – Field's",
          "lat": 55.6269,
          "lon": 12.5751,
          "arrive": "16:25",
          "depart": "17:45",
          "maps_query": "Field's, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Field%27s%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Didelis prekybos centras su maisto kiemeliu prie pat arenos – patogu prieš koncertą.",
          "arrive_by": "transit",
          "transit": "Traukinys/S-tog: København H → Ørestad (~7 min), toliau 5 min pėsčiomis"
        },
        {
          "name": "Royal Arena – Deep Purple koncertas",
          "lat": 55.6256,
          "lon": 12.5732,
          "arrive": "17:50",
          "depart": "22:00",
          "maps_query": "Royal Arena, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Royal%20Arena%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Durys atsidaro ~18:00, koncerto pradžia orientaciniai ~19:00–20:00 (patikslinti artimiau datai livenation.dk). Dėl vasaros laiko pabaigos šią naktį patikrinkite vėlyvo metro tvarkaraštį grįžtant.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Grįžimas į apartamentus",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "22:20",
          "depart": "22:30",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Po koncerto grįžtama tiesioginiu metro. Patikrinkite paskutinio traukinio laiką.",
          "arrive_by": "transit",
          "transit": "Metro M1: Ørestad → Christianshavn (~20 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 4,
      "title": "Amalienborg, Nyhavn ir skrydis namo",
      "stops": [
        {
          "name": "Amalienborg Museum",
          "lat": 55.684,
          "lon": 12.5933,
          "arrive": "09:50",
          "depart": "11:00",
          "maps_query": "Amalienborg Museum, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Amalienborg%20Museum%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Karališkųjų apartamentų interjerai. Prieš lapkričio 1 d. pirmadieniais dirba 10:00–15:00. Bilietas ~125 DKK internetu / 135 DKK vietoje, nemokamai <18 m.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 8 min pėsčiomis"
        },
        {
          "name": "Nyhavn (paskutinis apsilankymas)",
          "lat": 55.6799,
          "lon": 12.5898,
          "arrive": "11:10",
          "depart": "11:50",
          "maps_query": "Nyhavn, København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Trumpas laikas suvenyrams ir paskutinėms nuotraukoms prie kanalo.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Apartamentai – bagažas ir išsiregistravimas",
          "lat": 55.67,
          "lon": 12.5945,
          "arrive": "12:00",
          "depart": "12:20",
          "maps_query": "Christianshavns Torv, 1411 København K, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark",
          "notes": "Atsiimkite bagažą ir išsiregistruokite.",
          "arrive_by": "transit",
          "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)"
        },
        {
          "name": "Kopenhagos oro uostas (CPH) – pietūs ir skrydis",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "12:40",
          "depart": "15:15",
          "maps_query": "Copenhagen Airport (CPH), Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark",
          "notes": "Grįžtamasis skrydis CPH→KUN išvyksta 15:15. Pietus patogu užkąsti pačiame oro uoste – daug kavinių ir restoranų abipus saugumo patikros. Rekomenduojama iš anksto atlikti registraciją internetu, liks pakankamai laiko bagažo pridavimui ir saugumo patikrai.",
          "arrive_by": "transit",
          "transit": "Metro M2: Christianshavn → Lufthavnen (tiesioginis, ~14 min)"
        }
      ],
      "driving_minutes": 0,
      "overnight_city": "Kaunas"
    }
  ]
}
```

**Forecast:**

```json
{
  "generated_on": "2026-10-21",
  "days": [
    {
      "day": 1,
      "date": "2026-10-23",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 8.8,
      "temp_max_c": 12.4,
      "precip_chance_pct": 82,
      "precip_mm": 1.5,
      "wind_max_kmh": 24.8
    },
    {
      "day": 2,
      "date": "2026-10-24",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 10.4,
      "temp_max_c": 12.0,
      "precip_chance_pct": 78,
      "precip_mm": 2.9,
      "wind_max_kmh": 31.3
    },
    {
      "day": 3,
      "date": "2026-10-25",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Lietus",
      "temp_min_c": 9.1,
      "temp_max_c": 12.4,
      "precip_chance_pct": 87,
      "precip_mm": 12.4,
      "wind_max_kmh": 59.0
    },
    {
      "day": 4,
      "date": "2026-10-26",
      "place": "Kaunas",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 8.4,
      "temp_max_c": 12.1,
      "precip_chance_pct": 31,
      "precip_mm": 1.0,
      "wind_max_kmh": 29.2
    }
  ]
}
```

Rental car: false

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "baggage": "Tik rankinis bagažas (~8-10 kg/asmeniui) – skrydžiai KUN–CPH–KUN be registruoto bagažo. Skysčiai iki 100 ml, sudėti į vieną 1 l maišelį.",
  "categories": [
    {
      "name": "Drabužiai",
      "items": [
        {
          "name": "Neperšlampama striukė su gobtuvu",
          "note": "lietaus tikimybė 78-87% visas 3 dienas, 3-ią dieną vėjas iki 59 km/h – skėtis neišsilaikys"
        },
        {
          "name": "Šiltas megztinis ar flisas (2 vnt.)",
          "note": "8-12°C, vakarais vėsiau"
        },
        {
          "name": "Ilgos kelnės (2-3 poros)"
        },
        {
          "name": "Marškinėliai/palaidinukės ilgoms rankovėms sluoksniavimui",
          "note": "4 d."
        },
        {
          "name": "Šalikas ir plonos pirštinės",
          "note": "vėjuota, ypač spalio 25 d."
        },
        {
          "name": "Kepurė ar beisbolka",
          "note": "nuo lietaus/vėjo"
        },
        {
          "name": "Patogūs, įeiti vandeniui atsparūs batai",
          "note": "daug vaikščiojimo, Christianshavn/Nyhavn grindinys"
        },
        {
          "name": "Pižama, kojinės, apatiniai (4 d.)"
        },
        {
          "name": "Lengvesnė apranga koncertui",
          "note": "Royal Arena, 2026-10-25 vakare"
        }
      ]
    },
    {
      "name": "Dokumentai ir pinigai",
      "items": [
        {
          "name": "Asmens tapatybės kortelė arba pasas",
          "note": "ES/Šengenas – LT asmens kortelės pakanka"
        },
        {
          "name": "Skrydžių ir apgyvendinimo patvirtinimai (el. paštas/atsispausdinti)"
        },
        {
          "name": "Kelionės draudimas",
          "note": "polisas telefone/atsispausdintas"
        },
        {
          "name": "Mokėjimo kortelė",
          "note": "Danija beveik visur be grynųjų"
        },
        {
          "name": "Nedidelė suma DKK grynaisiais",
          "note": "atsarginiam atvejui, nors retai reikalinga"
        },
        {
          "name": "Koncerto bilietai (Deep Purple, Royal Arena)",
          "note": "PDF/el. bilietas telefone"
        }
      ]
    },
    {
      "name": "Kelionei ir elektronika",
      "items": [
        {
          "name": "Telefono įkroviklis"
        },
        {
          "name": "Nešiojama baterija (power bank)",
          "note": "ilgos dienos pėsčiomis/viešuoju transportu"
        },
        {
          "name": "Rejsebillet programėlė telefone",
          "note": "metro/traukinių bilietams, patikrinti prieš kelionę"
        },
        {
          "name": "Nedidelis vandeniui atsparus kuprinys/rankinė dienos žygiams"
        },
        {
          "name": "Ausų kištukai",
          "note": "garsus koncertas Royal Arena"
        },
        {
          "name": "Offline žemėlapis (Google Maps atsisiųstas CPH/Kopenhagos regionas)"
        }
      ]
    },
    {
      "name": "Higiena ir kita",
      "items": [
        {
          "name": "Kelioniniai higienos reikmenys (≤100 ml)",
          "note": "šampūnas, dušo želė, dezodorantas"
        },
        {
          "name": "Dantų šepetėlis ir pasta"
        },
        {
          "name": "Asmeniniai vaistai",
          "note": "+ paracetamolis, pleistrai"
        },
        {
          "name": "Rankų dezinfekantas, servetėlės"
        },
        {
          "name": "Maža skalbimo priemonė arba muilas",
          "note": "4 d. kelionė, galima skalbti apartamentuose"
        }
      ]
    }
  ],
  "tips": [
    "Visi skysčiai (šampūnas, dezodorantas, pasta) – iki 100 ml talpyklose, sudėti į vieną permatomą 1 l maišelį rankiniame bagaže.",
    "Vietoj skėčio rinktis tvirtą striukę su gobtuvu – spalio 25 d. prognozuojamas vėjas iki 59 km/h sugadins skėtį.",
    "Rengtis sluoksniais: lauke 8-12°C ir lietinga, bet muziejuose/pilyse (Rosenborg, Christiansborg, SMK) šilta – lengva nusivilkti viršutinį sluoksnį.",
    "Christianshavn ir Nyhavn turi akmenų grindinį – rinktis patogius, ne slidžius batų padus.",
    "Spalio 25-osios naktį Danijoje baigiasi vasaros laikas (laikrodžiai -1 val.) – naudinga patikrinti telefono laiką automatiškai atsinaujina.",
    "Danijos elektros lizdai sutampa su Lietuvos (Europlug/Type C,E tinka) – adapteris nereikalingas."
  ]
}
```

</details>

### 3. Biudžetas — 20:25:38 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 119.8 s
- **Sistemos promptas:** `prompts/budget.md`

<details><summary><b>Užklausa</b></summary>

````json
{
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas ir Christianshavn\",\"stops\":[{\"name\":\"Kopenhagos oro uostas (CPH)\",\"lat\":55.618,\"lon\":12.6476,\"arrive\":\"09:40\",\"depart\":\"10:00\",\"maps_query\":\"Copenhagen Airport (CPH), Kastrup, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark\",\"notes\":\"Atvykimo skrydis iš Kauno. Atsiėmę bagažą, metro stotelėje nusipirkite bilietus Rejsebillet programėlėje arba automate (fizinis Rejsekort pamažu nebenaudojamas).\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Apartamentai Sanders Saint-Nice (Christianshavn)\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"10:16\",\"depart\":\"10:45\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Įsikurkite ir palikite bagažą – butas 3 min pėsčiomis nuo Christianshavn metro stotelės.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M2: Lufthavnen → Christianshavn (tiesioginis, ~14 min)\"},{\"name\":\"Vor Frelsers Kirke (bokštas)\",\"lat\":55.673,\"lon\":12.5942,\"arrive\":\"10:55\",\"depart\":\"12:45\",\"maps_query\":\"Vor Frelsers Kirke, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Vor%20Frelsers%20Kirke%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Garsieji išorės sukasi laiptai su vaizdu į Christianshavn. Bokštas kasdien 09:00–20:00 (gali uždaryti stiprų vėją/lietų – jei taip, apžiūrėkite tik bažnyčią). Bilietas į bokštą ~70 DKK. Dviračių takai (cykelsti) – niekada jais neikite pėsčiomis.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Pietūs – Christianshavns Bådudlejning og Café\",\"lat\":55.6757,\"lon\":12.592,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Christianshavns Bådudlejning og Café, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Jaukus kavinė tiesiai prie kanalo – geras smørrebrød ir vietinis alus.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nyhavn (diena)\",\"lat\":55.6799,\"lon\":12.5898,\"arrive\":\"14:20\",\"depart\":\"15:30\",\"maps_query\":\"Nyhavn, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Spalvingas kanalo krantas su laivais – klasikinė Kopenhagos atvirutė. Nemokama.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Amalienborg (kiemas, sargybos namai)\",\"lat\":55.684,\"lon\":12.5933,\"arrive\":\"15:40\",\"depart\":\"16:05\",\"maps_query\":\"Amalienborg, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Amalienborg%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karališkoji rezidencija – sargybos keitimas vyksta apie vidurdienį, bet kiemas gražus bet kuriuo metu. Muziejų aplankysime kitą rytą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Den Lille Havfrue (Mažoji jūrų nimfa)\",\"lat\":55.6929,\"lon\":12.5993,\"arrive\":\"16:25\",\"depart\":\"16:45\",\"maps_query\":\"Den Lille Havfrue, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Den%20Lille%20Havfrue%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Nedidelė, bet ikoniška skulptūra – trumpas vizitas užtenka. Popietė mažiau minios nei rytais, kai atvažiuoja turistų autobusai.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nyhavn vakare ir vakarienė (Nyhavns Færgekro)\",\"lat\":55.6797,\"lon\":12.5905,\"arrive\":\"17:10\",\"depart\":\"19:30\",\"maps_query\":\"Nyhavns Færgekro, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavns%20F%C3%A6rgekro%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Saulei nusileidus (~17:15) kanalas gražiausias apšviestas. Vakarienė tradicinėje danų restorane – rekomenduojamas smørrebrød ir žuvies patiekalai.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Grįžimas į apartamentus\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"19:50\",\"depart\":\"20:00\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Nakvynė Christianshavn.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":2,\"title\":\"Pilys ir muziejai\",\"stops\":[{\"name\":\"Rosenborg Slot\",\"lat\":55.6857,\"lon\":12.5777,\"arrive\":\"09:35\",\"depart\":\"11:00\",\"maps_query\":\"Rosenborg Slot, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Rosenborg%20Slot%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karūnos brangenybės ir karališkoji istorija. Žiemos darbo laikas (spalis–kovas) 10:00–16:00. Bilietas ~140 DKK, nemokamai <18 m.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 18 min pėsčiomis iki pilies (arba pasivaikščiokite po Kongens Have parką prieš atidarymą)\"},{\"name\":\"SMK – Statens Museum for Kunst\",\"lat\":55.6896,\"lon\":12.5799,\"arrive\":\"11:12\",\"depart\":\"12:40\",\"maps_query\":\"SMK - Statens Museum for Kunst, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=SMK%20-%20Statens%20Museum%20for%20Kunst%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Danijos nacionalinė dailės galerija. Šeštadienį dirba 10:00–18:00. Bilietas ~140 DKK, nemokamai <18 m.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Pietūs – Torvehallerne\",\"lat\":55.6839,\"lon\":12.5705,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Torvehallerne, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Torvehallerne%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Geriausia maisto turgavietė mieste – rekomenduojama Hallernes Smørrebrød prekystalis tradiciniam smørrebrød. Įėjimas nemokamas, mokama už prekes.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Christiansborg Slot\",\"lat\":55.6761,\"lon\":12.5789,\"arrive\":\"14:30\",\"depart\":\"16:00\",\"maps_query\":\"Christiansborg Palace, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christiansborg%20Palace%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Danijos parlamento būstinė, karališkosios reprezentacinės salės ir pilies griuvėsiai. Kasdien 10:00–17:00. Bilietas ~215 DKK internetu / 225 DKK vietoje, nemokamai <18 m.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nationalmuseet\",\"lat\":55.6751,\"lon\":12.5748,\"arrive\":\"16:05\",\"depart\":\"17:00\",\"maps_query\":\"Nationalmuseet, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nationalmuseet%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Didžiausias Danijos muziejus, vikingų ir priešistorės kolekcijos. Dirba kasdien 10:00–17:00. Bilietas ~150 DKK – patikrinkite prie kasos, kai kurie šaltiniai teigia, kad nuolatinė ekspozicija nemokama.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Vakarienė – Ved Kanalen\",\"lat\":55.6745,\"lon\":12.592,\"arrive\":\"18:00\",\"depart\":\"19:30\",\"maps_query\":\"Ved Kanalen, Overgaden Neden Vandet, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ved%20Kanalen%2C%20Overgaden%20Neden%20Vandet%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Aukštai vertinamas tradicinis danų restoranas tiesiai prie kanalo, netoli nakvynės vietos.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":3,\"title\":\"Christiania, Tivoli ir Deep Purple koncertas\",\"stops\":[{\"name\":\"Freetown Christiania\",\"lat\":55.6738,\"lon\":12.5983,\"arrive\":\"09:20\",\"depart\":\"11:00\",\"maps_query\":\"Freetown Christiania, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Freetown%20Christiania%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Savivaldi alternatyvi bendruomenė, gatvės menas. Lankykite tik dienos metu. Pusher Street – nefotografuokite, laikykitės taisyklių. Nemokama. Šiąnakt (spalio 25-osios naktį) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Ny Carlsberg Glyptotek\",\"lat\":55.6735,\"lon\":12.5727,\"arrive\":\"11:25\",\"depart\":\"12:50\",\"maps_query\":\"Ny Carlsberg Glyptotek, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ny%20Carlsberg%20Glyptotek%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Antikos ir impresionistų kolekcija, žiemos sodas po stiklo kupolu. Sekmadienį dirba 10:00–17:00. Bilietas ~125 DKK.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv, persėdimas į M3 → Rådhuspladsen (~18 min iš viso), toliau 5 min pėsčiomis\"},{\"name\":\"Pietūs – Tivoli Food Hall\",\"lat\":55.673,\"lon\":12.5678,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Tivoli Food Hall, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tivoli%20Food%20Hall%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Pietūs Tivoli sodų maisto salėje – įskaičiuota į bendrą Tivoli bilietą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Tivoli Gardens (Helovino tema)\",\"lat\":55.6736,\"lon\":12.5681,\"arrive\":\"14:00\",\"depart\":\"16:00\",\"maps_query\":\"Tivoli Gardens, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tivoli%20Gardens%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Istorinis pramogų parkas, per visą kelionę vyksta Helovino sezonas su 20 000 moliūgų dekoracijų. Vartai 11:00–23:00. Bilietas ~200 DKK suaugusiam.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Vakarienė – Field's\",\"lat\":55.6269,\"lon\":12.5751,\"arrive\":\"16:25\",\"depart\":\"17:45\",\"maps_query\":\"Field's, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Field%27s%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Didelis prekybos centras su maisto kiemeliu prie pat arenos – patogu prieš koncertą.\",\"arrive_by\":\"transit\",\"transit\":\"Traukinys/S-tog: København H → Ørestad (~7 min), toliau 5 min pėsčiomis\"},{\"name\":\"Royal Arena – Deep Purple koncertas\",\"lat\":55.6256,\"lon\":12.5732,\"arrive\":\"17:50\",\"depart\":\"22:00\",\"maps_query\":\"Royal Arena, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Royal%20Arena%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Durys atsidaro ~18:00, koncerto pradžia orientaciniai ~19:00–20:00 (patikslinti artimiau datai livenation.dk). Dėl vasaros laiko pabaigos šią naktį patikrinkite vėlyvo metro tvarkaraštį grįžtant.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Grįžimas į apartamentus\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"22:20\",\"depart\":\"22:30\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Po koncerto grįžtama tiesioginiu metro. Patikrinkite paskutinio traukinio laiką.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1: Ørestad → Christianshavn (~20 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":4,\"title\":\"Amalienborg, Nyhavn ir skrydis namo\",\"stops\":[{\"name\":\"Amalienborg Museum\",\"lat\":55.684,\"lon\":12.5933,\"arrive\":\"09:50\",\"depart\":\"11:00\",\"maps_query\":\"Amalienborg Museum, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Amalienborg%20Museum%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karališkųjų apartamentų interjerai. Prieš lapkričio 1 d. pirmadieniais dirba 10:00–15:00. Bilietas ~125 DKK internetu / 135 DKK vietoje, nemokamai <18 m.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 8 min pėsčiomis\"},{\"name\":\"Nyhavn (paskutinis apsilankymas)\",\"lat\":55.6799,\"lon\":12.5898,\"arrive\":\"11:10\",\"depart\":\"11:50\",\"maps_query\":\"Nyhavn, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Trumpas laikas suvenyrams ir paskutinėms nuotraukoms prie kanalo.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Apartamentai – bagažas ir išsiregistravimas\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"12:00\",\"depart\":\"12:20\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Atsiimkite bagažą ir išsiregistruokite.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)\"},{\"name\":\"Kopenhagos oro uostas (CPH) – pietūs ir skrydis\",\"lat\":55.618,\"lon\":12.6476,\"arrive\":\"12:40\",\"depart\":\"15:15\",\"maps_query\":\"Copenhagen Airport (CPH), Kastrup, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark\",\"notes\":\"Grįžtamasis skrydis CPH→KUN išvyksta 15:15. Pietus patogu užkąsti pačiame oro uoste – daug kavinių ir restoranų abipus saugumo patikros. Rekomenduojama iš anksto atlikti registraciją internetu, liks pakankamai laiko bagažo pridavimui ir saugumo patikrai.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M2: Christianshavn → Lufthavnen (tiesioginis, ~14 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kaunas\"}]}",
  "accommodation": "## Nakvynė — Kopenhaga (2026-10-23 → 2026-10-26, 3 naktys, viena stotelė)\n\nKelionėje automobilis nenuomojamas, todėl prioritetas – greta stotelės/metro ir centro. Svečiai jau nurodė konkretų, rezervuotą butą, tad jį pateikiu kaip pagrindinį variantą ir pridedu 2 atsargines alternatyvas tuo atveju, jei rezervacija nepatvirtinta arba reikėtų keisti.\n\n### 1. Sanders Saint-Nice 1-Bdr Apt by the Canals (jau pasirinkta/nurodyta keliautojo)\n- **Kaina**: ~$158/naktis (Expedia duomenys, apytiksliai €135–145/naktis priklausomai nuo kurso — tiksli kaina priklauso nuo rezervacijos platformos ir datų, netikrinta tiesiogiai EUR)\n- **Kodėl tinka**: Christianshavn rajone, prie kanalų, 1 min. nuo Vor Frelsers Kirke (bokštas suderintas su kultūros prioritetu); **3 min pėsčiomis iki Christianshavn metro stoties (M1/M2)** — puikiai tinka be automobilio; ~15 min pėsčiomis iki Nyhavn/Strøget. Virtuvėlė su indaplove ir orkaite, interneto prieiga, centrinis šildymas.\n- **Pastaba**: skelbiamas kaip \"1-Bdr\" (1 miegamasis) — jei kelionėje 4 keliautojai, verta patvirtinti miegamųjų vietų skaičių prieš galutinį patvirtinimą.\n- **Booking nuorodos**: [Tripadvisor](https://www.tripadvisor.com/VacationRentalReview-g189541-d18852743-Sanders_Saint_Nice_1_Bdr_Apt_By_the_Canals-Copenhagen_Zealand.html) · [Expedia](https://www.expedia.com/Copenhagen-Hotels-Cozy-Apartment-In-Christianshavn.h45157366.Hotel-Information) · [Hotels.com](https://hotels.com/ho1446035712/cozy-apartment-in-christianshavn-copenhagen-copenhagen-denmark)\n\n### 2. Central Canal Apartments (Christianshavn) — atsarginis variantas\n- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai\n- **Kodėl tinka**: tame pačiame Christianshavn rajone prie kanalų, ~15 min pėsčiomis iki Strøget; kelios butų kategorijos, galimai tinka 4 žmonėms.\n- **Nuoroda**: [copenhagen-hotel.org](https://www.copenhagen-hotel.org/en/property/central-canal-apartments.html)\n\n### 3. CABINN Apartments — atsarginis variantas\n- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai (CABINN tinklas paprastai priklauso biudžetinei/vidutinei kategorijai)\n- **Kodėl tinka**: 4 asmenų 2 kambarių butas, **greta metro stoties**, pusryčiai siūlomi gretimame CABINN Metro (05:30–10:00 darbo dienomis, 06:00–10:30 savaitgaliais) — atitinka \"pusryčiai įskaičiuoti\" prioritetą, kurio pirmasis variantas neturi patvirtinto.\n- **Nuoroda**: [CABINN Apartments](https://en.cabinn.com/hotel/cabinn-apartments)\n\n**Neatitikimai/rizikos**: Nei vienam variantui nepavyko rasti patvirtintos kainos EUR valiuta tiesiogiai iš rezervacijos sistemos konkrečioms 2026-10-23–26 datoms — rekomenduoju patikrinti kainą ir laisvas vietas (ypač miegamųjų skaičių pagrindiniame bute) booking.com/Expedia tiesiogiai prieš galutinį patvirtinimą.\n\n```json\n{\"picks\": [{\"city\": \"Kopenhaga\", \"name\": \"Sanders Saint-Nice 1-Bdr Apt by the Canals\", \"checkin\": \"2026-10-23\", \"checkout\": \"2026-10-26\", \"price_per_night_eur\": 140}]}\n```",
  "car_rental": {
    "needed": false,
    "recommended_car_types": [],
    "companies": [],
    "tips": []
  },
  "food": {
    "eateries": [
      {
        "name": "Christianshavns Bådudlejning og Café",
        "city": "Kopenhaga",
        "address": "Overgaden Neden Vandet 29, 1414 København K",
        "day": 1,
        "near": "Pietų stotelė maršrute, 2 min nuo Vor Frelsers Kirke",
        "kind": "kanalo kavinė valčių nuomos punkte",
        "local_cuisine": true,
        "avg_price_eur": 20,
        "dinner_price_eur": 28,
        "must_try": [
          {
            "name": "Smørrebrodų rinkinys",
            "local_name": "Smørrebrød",
            "price_eur": 18,
            "commons_filename": "Smørrebrød in Copenhagen 01.jpg"
          },
          {
            "name": "Æbleskiver su uogiene ir cukraus pudra",
            "local_name": "Æbleskiver",
            "price_eur": 9,
            "commons_filename": "Aebleskiver.jpg"
          },
          {
            "name": "Lašišos salotos",
            "local_name": "Laksesalat",
            "price_eur": 15,
            "commons_filename": ""
          }
        ],
        "why": "Veikia nuo 1905 m., jauki kavinė tiesiai ant kanalo su valčių nuoma – gera vieta atsipūsti po bokšto lipimo Vor Frelsers Kirke.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20Overgaden%20Neden%20Vandet%2029%2C%201414%20K%C3%B8benhavn%20K"
      },
      {
        "name": "Nyhavns Færgekro",
        "city": "Kopenhaga",
        "address": "Nyhavn 5, 1051 København K",
        "day": 1,
        "near": "Vakarienės stotelė Nyhavn vakare",
        "kind": "tradicinė danų krogė (taverna)",
        "local_cuisine": true,
        "avg_price_eur": 28,
        "dinner_price_eur": 38,
        "must_try": [
          {
            "name": "Silkių bufetas (10+ rūšių)",
            "local_name": "Sildebuffet",
            "price_eur": 25,
            "commons_filename": "Sild.jpg"
          },
          {
            "name": "Krintanti žvaigždė (žuvies smørrebrodas)",
            "local_name": "Stjerneskud",
            "price_eur": 20,
            "commons_filename": "Stjerneskud (Bruun's Galleri).jpg"
          },
          {
            "name": "Namų gamybos akvavitas",
            "local_name": "Akvavit",
            "price_eur": 6,
            "commons_filename": ""
          }
        ],
        "why": "Vienas geriausių kainos/kokybės santykių Nyhavn kanalo pakrantėje – garsus savo silkių bufetu ir terasa prie vandens saulėlydžio metu.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavns%20F%C3%A6rgekro%2C%20Nyhavn%205%2C%201051%20K%C3%B8benhavn%20K"
      },
      {
        "name": "Hallernes Smørrebrød (Torvehallerne)",
        "city": "Kopenhaga",
        "address": "Frederiksborggade 21, 1360 København K (Torvehallerne, Hal 1)",
        "day": 2,
        "near": "Pietų stotelė Torvehallerne turgavietėje",
        "kind": "turgavietės smørrebrodo prekystalis",
        "local_cuisine": true,
        "avg_price_eur": 16,
        "dinner_price_eur": 22,
        "must_try": [
          {
            "name": "Krevetių smørrebrodas",
            "local_name": "Rejestykke",
            "price_eur": 17,
            "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
          },
          {
            "name": "Jautienos tataras",
            "local_name": "Tatar",
            "price_eur": 14,
            "commons_filename": "Steak Tartare in Dresden.jpg"
          },
          {
            "name": "Kepta kiauliena su spirgučiais",
            "local_name": "Flæskesteg",
            "price_eur": 13,
            "commons_filename": "Flaeskesteg med svaer.jpg"
          }
        ],
        "why": "Geriausios reputacijos smørrebrodo prekystalis mieste, tiesiai turgavietėje tarp šviežios žuvies ir sūrių prekystalių.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Hallernes%20Sm%C3%B8rrebr%C3%B8d%20%28Torvehallerne%29%2C%20Frederiksborggade%2021%2C%201360%20K%C3%B8benhavn%20K%20%28Torvehallerne%2C%20Hal%201%29"
      },
      {
        "name": "Restaurant Kanalen",
        "city": "Kopenhaga",
        "address": "Wilders Plads 2, 1403 København K",
        "day": 2,
        "near": "Vakarienės stotelė Ved Kanalen, 5 min nuo nakvynės Christianshavn",
        "kind": "aukštesnės klasės danų-prancūziška virtuvė (Michelin Plate)",
        "local_cuisine": true,
        "avg_price_eur": 55,
        "dinner_price_eur": 65,
        "must_try": [
          {
            "name": "Sezoninis degustacinis meniu (3 patiekalai)",
            "local_name": "Menu",
            "price_eur": 47,
            "commons_filename": ""
          },
          {
            "name": "Sūris su traškia duona",
            "local_name": "Ost med sprødt brød",
            "price_eur": 7,
            "commons_filename": ""
          },
          {
            "name": "Šokoladinis panna cotta",
            "local_name": "Chokolade panna cotta",
            "price_eur": 11,
            "commons_filename": ""
          }
        ],
        "why": "Michelin gide pažymėtas restoranas tiesiai ant Christianshavn kanalo kranto – atmosfera atpalaiduojanti, be snobizmo, nepaisant apdovanojimo.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Restaurant%20Kanalen%2C%20Wilders%20Plads%202%2C%201403%20K%C3%B8benhavn%20K"
      },
      {
        "name": "Tivoli Food Hall",
        "city": "Kopenhaga",
        "address": "Bernstorffsgade 3, 1577 København V (Tivoli Gardens)",
        "day": 3,
        "near": "Pietų stotelė prieš Tivoli Gardens",
        "kind": "maisto salė su 15-20 prekystalių",
        "local_cuisine": true,
        "avg_price_eur": 16,
        "dinner_price_eur": 20,
        "must_try": [
          {
            "name": "Klasikinis danų dešrainis su traškiais svogūnais",
            "local_name": "Ristet hotdog (Tivoligrillen)",
            "price_eur": 7,
            "commons_filename": ""
          },
          {
            "name": "Krevetių smørrebrodas",
            "local_name": "Rejemad (Hallernes Smørrebrød)",
            "price_eur": 17,
            "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
          },
          {
            "name": "Lašišos smørrebrodas",
            "local_name": "Laksemad",
            "price_eur": 16,
            "commons_filename": ""
          }
        ],
        "why": "Įvairiausių danų greito maisto prekystalių rinkinys viename stogo po – praktiška pietų pertrauka tarp Christiania ir Tivoli.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Tivoli%20Food%20Hall%2C%20Bernstorffsgade%203%2C%201577%20K%C3%B8benhavn%20V%20%28Tivoli%20Gardens%29"
      },
      {
        "name": "Field's",
        "city": "Kopenhaga",
        "address": "Arne Jacobsens Allé 12, 2300 København S",
        "day": 3,
        "near": "Vakarienės stotelė prieš Royal Arena koncertą",
        "kind": "prekybos centro maisto kiemelis",
        "local_cuisine": false,
        "avg_price_eur": 14,
        "dinner_price_eur": 16,
        "must_try": [
          {
            "name": "Burgeris (Sunset Boulevard, danų tinklas)",
            "local_name": "Original burger",
            "price_eur": 10,
            "commons_filename": ""
          },
          {
            "name": "Bulvytės",
            "local_name": "Pommes frites",
            "price_eur": 5,
            "commons_filename": ""
          },
          {
            "name": "Sumuštinis (Joe & The Juice)",
            "local_name": "Sandwich",
            "price_eur": 8,
            "commons_filename": ""
          }
        ],
        "why": "Ne tradicinė virtuvė, bet greitas ir patikimas pasirinkimas prieš koncertą – daug prekystalių vos prie pat arenos.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Field%27s%2C%20Arne%20Jacobsens%20All%C3%A9%2012%2C%202300%20K%C3%B8benhavn%20S"
      },
      {
        "name": "Aamanns Deli & Take Away (CPH oro uostas)",
        "city": "Kopenhaga",
        "address": "Copenhagen Airport, Terminal 3, 2770 Kastrup",
        "day": 4,
        "near": "Pietų ir laukimo laikas prieš skrydį CPH→KUN",
        "kind": "smørrebrodo parduotuvė oro uoste",
        "local_cuisine": true,
        "avg_price_eur": 14,
        "dinner_price_eur": 18,
        "must_try": [
          {
            "name": "Silkės smørrebrodas",
            "local_name": "Sildemad",
            "price_eur": 11,
            "commons_filename": "Sild.jpg"
          },
          {
            "name": "Krevetių smørrebrodas",
            "local_name": "Rejemad",
            "price_eur": 15,
            "commons_filename": "Smørrebrød. Rejemad på franskbrød fra Hallernes Smørrebrød. Torvehallerne i København. Foto Hans Christian Hansen.jpg"
          },
          {
            "name": "Rostbifo smørrebrodas",
            "local_name": "Roastbeefmad",
            "price_eur": 13,
            "commons_filename": ""
          }
        ],
        "why": "Geriausiai vertinama tradicinio smørrebrodo vieta oro uoste – paskutinė galimybė paragauti danų virtuvės prieš skrydį namo.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Aamanns%20Deli%20%26%20Take%20Away%20%28CPH%20oro%20uostas%29%2C%20Copenhagen%20Airport%2C%20Terminal%203%2C%202770%20Kastrup"
      }
    ],
    "dishes": [
      {
        "name": "Smørrebrodas",
        "local_name": "Smørrebrød",
        "description": "Atviras ruginės duonos sumuštinis su įvairiais priedais (silke, kiauliena, krevetėmis, kiaušiniu) – danų kasdienio maisto pagrindas.",
        "price_eur_min": 9,
        "price_eur_max": 18,
        "where_to_try": [
          "Christianshavns Bådudlejning og Café",
          "Nyhavns Færgekro",
          "Hallernes Smørrebrød (Torvehallerne)",
          "Tivoli Food Hall",
          "Aamanns Deli & Take Away (CPH oro uostas)"
        ],
        "commons_filename": "Smørrebrød in Copenhagen 01.jpg"
      },
      {
        "name": "Marinuota silkė",
        "local_name": "Sild",
        "description": "Marinuota silkė ant ruginės duonos, dažnai siūloma keliomis padažų versijomis – klasikinis danų užkandis prie akvavito.",
        "price_eur_min": 10,
        "price_eur_max": 15,
        "where_to_try": [
          "Nyhavns Færgekro",
          "Aamanns Deli & Take Away (CPH oro uostas)"
        ],
        "commons_filename": "Sild.jpg"
      },
      {
        "name": "Krintanti žvaigždė",
        "local_name": "Stjerneskud",
        "description": "Šventinis smørrebrodas su kepta ir virta žuvimis, krevetėmis, majonezu ir ikrais – vienas populiariausių restoranų patiekalų.",
        "price_eur_min": 15,
        "price_eur_max": 22,
        "where_to_try": [
          "Hallernes Smørrebrød (Torvehallerne)",
          "Nyhavns Færgekro"
        ],
        "commons_filename": "Stjerneskud (Bruun's Galleri).jpg"
      },
      {
        "name": "Frikadelės",
        "local_name": "Frikadeller",
        "description": "Kiaulienos ir jautienos maltinukai, patiekiami su ruginę duona ir raudonaisiais kopūstais arba bulvėmis – namų virtuvės klasika.",
        "price_eur_min": 12,
        "price_eur_max": 18,
        "where_to_try": [
          "Nyhavns Færgekro",
          "Restaurant Kanalen"
        ],
        "commons_filename": "Flickr - cyclonebill - Frikadeller med ristet rugbrød og cornichons.jpg"
      },
      {
        "name": "Kepta kiauliena su spirgučiais",
        "local_name": "Flæskesteg",
        "description": "Keptas kiaulienos sprandinė su traškia odele, patiekiama su raudonaisiais kopūstais ir bulvėmis – tradicinis šventinis patiekalas.",
        "price_eur_min": 13,
        "price_eur_max": 18,
        "where_to_try": [
          "Hallernes Smørrebrød (Torvehallerne)",
          "Nyhavns Færgekro"
        ],
        "commons_filename": "Flaeskesteg med svaer.jpg"
      },
      {
        "name": "Æbleskiver blyneliai",
        "local_name": "Æbleskiver",
        "description": "Apvalūs, pūsti blyneliai, keliami specialioje keptuvėje, patiekiami su uogiene ir cukraus pudra – populiarūs rudens/žiemos sezonu.",
        "price_eur_min": 6,
        "price_eur_max": 10,
        "where_to_try": [
          "Christianshavns Bådudlejning og Café",
          "Tivoli Food Hall"
        ],
        "commons_filename": "Aebleskiver.jpg"
      },
      {
        "name": "Danų dešrainis",
        "local_name": "Ristet hotdog",
        "description": "Keptas dešrainis su traškiais svogūnais, raugintais agurkais, garstyčiomis ir remulado padažu – gatvės maisto klasika.",
        "price_eur_min": 6,
        "price_eur_max": 9,
        "where_to_try": [
          "Tivoli Food Hall",
          "Field's"
        ],
        "commons_filename": ""
      },
      {
        "name": "Dano pyragaitis",
        "local_name": "Wienerbrød / kanelsnegl",
        "description": "Sluoksniuotos tešlos pyragaitis, dažniausiai su cinamonu ar vaisių įdaru – rytinis ar popietinis skanėstas su kava.",
        "price_eur_min": 4,
        "price_eur_max": 6,
        "where_to_try": [
          "Tivoli Food Hall",
          "Aamanns Deli & Take Away (CPH oro uostas)"
        ],
        "commons_filename": "Glazed apple Danish.jpg"
      }
    ],
    "bars": [
      {
        "name": "Hviids Vinstue",
        "city": "Kopenhaga",
        "address": "Kongens Nytorv 19, 1050 København K",
        "day": 1,
        "near": "Kongens Nytorv / Nyhavn",
        "why_special": "Kopenhagos seniausias nenutrūkstamai veikiantis baras, įkurtas 1723 m. – tamsaus medžio interjeras, žvakės ir senųjų menininkų portretai, matęs didžiuosius miesto gaisrus ir du pasaulinius karus.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Hviids%20Vinstue%2C%20Kongens%20Nytorv%2019%2C%201050%20K%C3%B8benhavn%20K"
      }
    ]
  }
}
````

</details>

<details><summary><b>Atsakymas</b></summary>

# Biudžeto suvestinė — Kopenhaga, 2026-10-23–26 (4 d. / 3 naktys, 4 keliautojai, be automobilio)

**Prielaida:** skaičiuota 4 suaugusiems keliautojams (pagal Apgyvendinimo agento užuominą apie CABINN 4-vietų variantą). Jei keliautojų skaičius kitoks, visos "per asmenį" eilutės skalinamos tiesiogiai.

## 1. Skrydžiai — **PATVIRTINTA** (Kiwi.com paieška)
| | |
|---|---|
| Maršrutas | Kaunas (KUN) ⇄ Kopenhaga (CPH), Ryanair |
| Atitinka maršrutą (09:40 atvykimas / 15:15 išvykimas) | FR6156 23-10 09:10→09:40; FR6155 26-10 15:15→17:45 |
| **Kaina 4 keleiviams** | **499 € iš viso** (~124,75 €/asm.) |

*Pastaba:* yra ir pigesnis variantas (394 €/4 keleiviams, FR7621 naktinis skrydis 23:45), bet jis neatitinka plane nurodyto 09:40 atvykimo laiko — jei laikas lankstus, tai sutaupytų ~105 €.

## 2. Viešasis transportas (automobilis nenuomojamas) — **DALINAI ĮVERTINTA**
City Pass Small (zonos 1–4, įsk. oro uostą): 24 val. = 100 DKK, 48 val. = 160 DKK, 72 val. = 220 DKK ([copenhagenmetro.org](https://copenhagenmetro.org/tickets-and-fares/)).
Maršrute ~9 metro/S-tog kelionės/asm. per 4 dienas → optimalu pirkti 72 val. City Pass atvykus + 1 papildomas bilietas paskutinei kelionei į oro uostą.

| | Min | Tikėtina | Max |
|---|---|---|---|
| Per asmenį | 220 DKK (~29,5 €) | 280 DKK (~37,5 €) | 350 DKK (~47 €) |
| **4 asmenims** | **~118 €** | **~150 €** | **~188 €** |

## 3. Apgyvendinimas — **DALINAI PATVIRTINTA** (Expedia kaina, nepatvirtinta tiesiogiai EUR)
Sanders Saint-Nice 1-Bdr Apt by the Canals, Christianshavn, 3 naktys.

| | Min | Tikėtina | Max |
|---|---|---|---|
| Kaina/naktis | 135 € | 140 € | 150 € |
| **3 naktys iš viso** | **405 €** | **420 €** | **450 €** |

## 4. Maistas — **ĮVERTINTA pagal konkrečius Food agento prekystalius/restoranus**
Skaičiuota pagal nurodytas `avg_price_eur`/`dinner_price_eur` + ~8 €/asm. pusryčiams (nenurodyta atskirai).

| Diena | Pusryčiai | Pietūs | Vakarienė | Iš viso/asm. |
|---|---|---|---|---|
| 1 (Bådudlejning / Færgekro) | 8 € | 20 € | 38 € | 66 € |
| 2 (Torvehallerne / Restaurant Kanalen) | 8 € | 16 € | 55–65 € | 79–89 € |
| 3 (Tivoli Food Hall / Field's) | 8 € | 16 € | 16 € | 40 € |
| 4 (Aamanns, oro uoste) | 8 € | 16 € | — | 24 € |
| **Iš viso/asm.** | | | | **209–219 €** |

| | Min | Tikėtina | Max |
|---|---|---|---|
| **4 asmenims (4 d.)** | **~836 €** | **~876 €** | **~1 050 €** (su barais/užkandžiais) |

## 5. Bilietai į objektus — **PATVIRTINTA** (kainos iš maršruto/Research agento pastabų)
Per asmenį (DKK, konvertuota kursu 1 € ≈ 7,46 DKK):

| Objektas | DKK | € |
|---|---|---|
| Vor Frelsers Kirke bokštas | 70 | 9,4 |
| Rosenborg Slot | 140 | 18,8 |
| SMK | 140 | 18,8 |
| Christiansborg Slot | 215 | 28,8 |
| Nationalmuseet | 150 | 20,1 |
| Ny Carlsberg Glyptotek | 125 | 16,8 |
| Tivoli Gardens | 200 | 26,8 |
| Amalienborg Museum | 125 | 16,8 |
| **Muziejai/parkai iš viso** | **1 165** | **~156 €** |
| Deep Purple, Royal Arena (25-10) — **papildomai patikrinta WebSearch** | 495–720 (PL4 450+45+15 … PL1 650+55+15) | 66–97 € |

| | Min | Tikėtina | Max |
|---|---|---|---|
| Per asmenį | ~225 € | ~241 € | ~253 € |
| **4 asmenims** | **~898 €** | **~963 €** | **~1 011 €** |

---

## 📊 Bendra suvestinė (4 keliautojai, 4 d. / 3 naktys)

| Kategorija | Statusas | Min | Tikėtina | Max |
|---|---|---|---|---|
| Skrydžiai | ✅ patvirtinta | 499 € | 499 € | 499 € |
| Viešasis transportas | ⚠️ įvertinta | 118 € | 150 € | 188 € |
| Apgyvendinimas | ⚠️ dalinai patvirtinta | 405 € | 420 € | 450 € |
| Maistas | ⚠️ įvertinta (konkretūs restoranai) | 836 € | 876 € | 1 050 € |
| Bilietai į objektus | ✅ dauguma patvirtinta, koncertas tikslintas | 898 € | 963 € | 1 011 € |
| **IŠ VISO** | | **~2 756 €** | **~2 908 €** | **~3 198 €** |
| **Vienam asmeniui** | | **~689 €** | **~727 €** | **~800 €** |

**Didžiausios rizikos biudžetui:** (1) apgyvendinimo kaina nepatvirtinta tiesiogiai EUR konkrečioms datoms; (2) Deep Purple bilieto kategorija/vieta nepasirinkta — skirtumas tarp PL4 ir PL1 ~23 €/asm.; (3) maisto skaičiavimas remiasi rekomenduotais restoranais, realios išlaidos priklausys nuo užsakytų patiekalų kiekio ir gėrimų (ypač Restaurant Kanalen ir barai, pvz. Hviids Vinstue).

Sources:
- [Copenhagen Metro Tickets and Prices 2026](https://copenhagenmetro.org/tickets-and-fares/)
- [Deep Purple Tickets, Royal Arena](https://www.royalarena.dk/all-events/deep-purple-tickets-ae3790)

</details>

### 4. Puslapis — 20:37:33 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 715.3 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

You are updating an already published trip page, not designing a new one. Below are the current page and the current data. Apply the listed changes and make every part of the page match the current data, but keep the design -- colors, layout, CSS, JS, section order -- and all wording that isn't affected exactly as it is. Keep the <!-- PACKING_LIST --> and <!-- TRIP_MAP --> lines where they are.

Changes:
Updated data: Maistas ir barai, Orų prognozė, Daiktai, Biudžetas

**Current data:**

```json
{
  "language": "lt",
  "research": "# Research Summary — Copenhagen, 2026-10-23 to 2026-10-26 (4 travelers, no rental car, priorities: culture + food)\n\n## Candidate stops\n\n| Stop | Why recommended | Hours / closed days | Adult price | Source |\n|---|---|---|---|---|\n| **Nyhavn** canal front | Iconic harbor, photos best early morning or after dark before crowds; free to walk | Always open (outdoor) | Free | [Traverse-blog](https://www.traverse-blog.com/copenhagen-denmark-itinerary/), [wheregoesrose](https://www.wheregoesrose.com/freetown-christiania-travel-guide-tips/) (2026) |\n| **Christianshavn / canals** (near booked apartment) | Picturesque canal district, walkable from Nyhavn, local-feel | Always open (outdoor) | Free | general |\n| **Rundetårn (Round Tower)** | Oldest functioning observatory in Europe, spiral ramp, views over old town | Oct–Mar: daily 10:00–18:00 | 60 DKK, free <18 | [copenhagentourism.org](https://www.copenhagentourism.org/round-tower-rundetaarn-copenhagen/) |\n| **Vor Frelsers Kirke (Church of Our Saviour)** tower | Famous spiral external staircase, views of Christianshavn | Tower daily 09:00–20:00 (closes in rain/snow/strong wind — real risk in Oct); church 11:00–15:30 | Tower: 70 DKK adult / 20 DKK child; church free | [vorfrelserskirke.dk](https://www.vorfrelsersk irke.dk/taarn/tower/booking), [copenhagencard.com](https://copenhagencard.com/attractions/church-of-our-saviour) (2026) |\n| **Rosenborg Castle** | Crown jewels, royal history | Winter hours (Oct–Mar) likely 10:00–16:00, **closed Mondays** off-season | 140 DKK, free <18 | [tourismattractions.net / parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/rosenborg/) (2026) — **verify exact Oct 2026 hours before trip, source conflicts on winter Monday closure** |\n| **Christiansborg Palace** (Reception Rooms/Ruins/Kitchen) | Seat of parliament, royal reception rooms | Daily 10:00–17:00 (through Nov 1); Tower closed Mondays | 215 DKK online / 225 at door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/christiansborg-palace/plan-your-visit/opening-hours/) (2026) |\n| **Amalienborg Museum** | Royal residence, changing of the guard (~noon) | Mon–Fri 10:00–15:00, Sat–Sun 10:00–16:00 (Nov 1 on, closed Mondays) | 125 DKK online/135 door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/amalienborg-museum/plan-your-visit/opening-hours/) (2026) |\n| **National Museum (Nationalmuseet)** | Denmark's largest museum, Viking/prehistory collections | Daily 10:00–17:00 (Apr–Oct); price info **conflicting** — official ticket page lists 150 DKK adult, other sources say permanent collection free | 150 DKK adult (verify at door — may be free) | [nationalmuseet.dk/en/tickets](https://nationalmuseet.dk/en/tickets), [copenhagentourism.org](https://www.copenhagentourism.org/national-museum-denmark-copenhagen/) |\n| **SMK – National Gallery of Denmark** | Major art museum | Closed **Mon**; Tue 10–18, Wed 10–20, Thu–Sun 10–18 | 140 DKK adult, free <18 | [parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/smk/) (2026) |\n| **Ny Carlsberg Glyptotek** | Antiquities + Impressionist art, winter garden | Closed **Mon**; Tue–Sun 10–17 (Thu to 21) | 125 DKK, **free every Tuesday** | search aggregate (2026) |\n| **Designmuseum Danmark** | Danish design heritage | Closed **Mon**; Tue–Sun 10–18 (Thu to 20) | 130 DKK, free <18 | aggregate (2026) |\n| **Freetown Christiania** | Alternative self-governing community, street art | Daytime only — avoid after dark and avoid photos on Pusher Street | Free | [copenhagentourism.org](https://www.copenhagentourism.org/freetown-christiania-copenhagen/) |\n| **Tivoli Gardens** | Historic amusement park, Halloween theming Oct 2–Nov 1 2026 (20,000 pumpkins) | Gates 11:00, closes 23:00 (extended Fri/Sat) | 200 DKK adult, 100 DKK child 3–7 | [copenhagentourism.org](https://www.copenhagentourism.org/tivoli-gardens-copenhagen/) (2026) |\n| **Torvehallerne food market** | Best food hall, Hallernes Smørrebrød stall recommended for traditional smørrebrød | Mon–Fri 10–19, Sat–Sun 10–18 | Free entry (pay per item) | [scandinaviastandard.com](https://www.scandinaviastandard.com/the-ultimate-guide-to-the-best-food-halls-in-copenhagen/) |\n| **Reffen street food park** | Affordable (from 70 DKK), harborside, casual | **Confirmed open on trip dates** — Autumn/Halloween season runs Oct 1–Nov 2; stalls ~11:30–20:30 | Free entry | [reffen.dk](https://reffen.dk/en/info-2025/), search re: season dates |\n| **Stromma canal boat tour** | Classic way to see the harbor/canals | Oct: Mon–Sat 10:00–16:50, live-guided only (no recorded commentary off-season) | Not confirmed — check stromma.com | [copenhagencard.com](https://copenhagencard.com/attractions/canal-tours-copenhagen) |\n| **The Little Mermaid statue** | Iconic photo stop, but widely called overrated/small/crowded on forums; go early morning | Outdoor, always visible | Free | reddit/forum aggregate — \"go before 9am to beat tour buses\" |\n\n## Events on trip dates (2026-10-23 to 10-26)\n\n- **Deep Purple concert** — Royal Arena, Hannemanns Allé 18, 2300 København S — **Sunday 2026-10-25, doors/support act timing suggests show starts ~18:00–20:00** (one source lists 18:00). Confirm exact doors/start time closer to date. [livenation.dk](https://www.livenation.dk/en/event/deep-purple-k%C3%B8benhavn-s-tickets-edp1635370), [songkick](https://www.songkick.com/concerts/42897389-deep-purple-at-royal-arena)\n- **Daylight Saving Time ends** — Sunday 2026-10-25 at 03:00, clocks go back 1 hour. This affects the Deep Purple concert evening and the Oct 26 flight-day schedule — build in the extra hour. [timeanddate.com](https://www.timeanddate.com/holidays/denmark/2026)\n- **HRH Crown Prince Christian's birthday flag day** — 2026-10-15 (before trip, no impact).\n- **Kulturnatten (Culture Night)** — 2026-10-09 (before trip, no impact).\n- No Danish statutory public holidays fall within Oct 23–26, 2026 — museums/shops operate normal hours except their usual weekly closures (mostly Mondays).\n- Tivoli's Halloween season (pumpkins, decorations) runs through the full trip window.\n\n## Road/logistics warnings\n\nNot applicable — no car rental for this trip; travel is entirely on foot and public transport within Copenhagen. No bekelė/4x4 road risk applies.\n\n## Public transport & logistics notes\n\n- 2026 ticketing: **Rejsebillet app** is replacing the old DOT Billetter app; physical Rejsekort is being phased out. Buy single tickets in-app or at station machines, or get **City Pass Small** (zones 1–4, unlimited 24h) for heavy sightseeing days. [denmarkguide.dk](https://denmarkguide.dk/en/oplev-danmark/transport-og-mobilitet/offentlig-transport/rejsekort-rejsebillet-dsb-app/)\n- **Copenhagen Card**: worth it only if doing 3+ paid attractions/day; for a culture-heavy 3-night trip with Rosenborg + Christiansborg + SMK/Glyptotek + Amalienborg it likely pays off — do the math against your actual chosen stops before buying. [routesnorth.com](https://www.routesnorth.com/denmark/copenhagen/copenhagen-card-worth-buying/)\n- Metro runs from CPH airport directly to the city center (M2 line) — relevant for the 09:40 arrival and 15:15 departure.\n\n## Seasonal / weather notes\n\n- October in Copenhagen: avg **13°C day / 7°C night**, ~14–15 rainy days/month, ~50–68mm total rainfall — pack rain gear; plan a roughly even mix of indoor (museums) and outdoor stops, with flexible ordering to shift outdoor stops (Nyhavn, Christiania, canal walk) to drier windows and indoor museums to rain windows. [wanderlog](https://wanderlog.com/weather/9643/10/copenhagen-weather-in-october), [weather-atlas](https://www.weather-atlas.com/en/denmark/copenhagen-weather-october)\n- Daylight shrinks fast late October: sunset ~18:04 on Oct 18 narrowing toward ~16:30s after the Oct 25 clock change — plan outdoor sightseeing for mid-day/early afternoon, reserve dark hours for Nyhavn's lit-up evening look, dinners, and the Oct 25 concert. [tutiempo.net](https://en.tutiempo.net/daylight-hours/copenhagen.html)\n- Vor Frelsers Kirke tower closes on wind/rain days without notice — do not schedule it as the only activity in a time slot; have a museum backup.\n\n## What's overrated/skippable (forum consensus)\n\n- **Little Mermaid statue**: widely called underwhelming/tiny, crowded with tour buses even early; visit briefly and early morning only, don't build a half-day around it.\n- Pusher Street inside Christiania: skip photography there specifically (camera-breaking incidents reported); rest of Christiania fine in daylight.\n\n## Practical information (Lithuanian/EU citizens)\n\n- **Documents**: Valid passport or national ID card sufficient — Denmark is Schengen, no visa needed for EU citizens, stays up to 90 days. [visitcopenhagen.com](https://www.visitcopenhagen.com/copenhagen/planning/basic-need-know-information)\n- **Currency**: Danish Krone (DKK), **not euro** — Denmark is EU but outside the eurozone. Cards are very widely accepted everywhere, including small purchases; carrying some cash is still wise for Christiania (ATMs scarce there) and some small/independent food stalls.\n- **Tipping**: Not expected — service is included in restaurant/hotel/taxi bills. Round up or ~10% for exceptional service only.\n- **Health**: Bring EHIC/European Health Insurance Card for free/reduced emergency treatment as an EU citizen.\n- **Emergency number**: **112** (police/fire/ambulance, free call). Non-emergency medical advice line: **1813** (English-speaking staff).\n- **Public transport tickets**: Rejsebillet app (replacing DOT app in 2026) or City Pass; see above.\n- **Customs/etiquette**: Danes value punctuality, queueing, and personal space; \"hygge\" culture — low-key, unpretentious; bike lanes are serious — never walk in the cykelsti (marked bike lane), tourists get yelled at/hit.\n- **Safety**: Copenhagen is generally very safe; normal urban precautions apply (watch belongings in tourist-dense Nyhavn/Strøget). Christiania safe in daylight, avoid after dark, follow posted community rules (no running, no photos on Pusher Street).\n\n## Unconfirmed — verify before finalizing itinerary\n\n- Exact Rosenborg Castle Monday closure status for Oct 2026 (sources conflict on winter weekday hours).\n- National Museum adult ticket price — official site states 150 DKK but several tourism sites claim permanent collection is free; confirm at nationalmuseet.dk/en/tickets closer to the date.\n- Deep Purple exact doors/start time at Royal Arena (confirm via livenation.dk nearer the date).\n- Stromma canal tour exact departure times/prices for Oct 23–26, 2026 (only general October hours found).",
  "accommodation": "## Nakvynė — Kopenhaga (2026-10-23 → 2026-10-26, 3 naktys, viena stotelė)\n\nKelionėje automobilis nenuomojamas, todėl prioritetas – greta stotelės/metro ir centro. Svečiai jau nurodė konkretų, rezervuotą butą, tad jį pateikiu kaip pagrindinį variantą ir pridedu 2 atsargines alternatyvas tuo atveju, jei rezervacija nepatvirtinta arba reikėtų keisti.\n\n### 1. Sanders Saint-Nice 1-Bdr Apt by the Canals (jau pasirinkta/nurodyta keliautojo)\n- **Kaina**: ~$158/naktis (Expedia duomenys, apytiksliai €135–145/naktis priklausomai nuo kurso — tiksli kaina priklauso nuo rezervacijos platformos ir datų, netikrinta tiesiogiai EUR)\n- **Kodėl tinka**: Christianshavn rajone, prie kanalų, 1 min. nuo Vor Frelsers Kirke (bokštas suderintas su kultūros prioritetu); **3 min pėsčiomis iki Christianshavn metro stoties (M1/M2)** — puikiai tinka be automobilio; ~15 min pėsčiomis iki Nyhavn/Strøget. Virtuvėlė su indaplove ir orkaite, interneto prieiga, centrinis šildymas.\n- **Pastaba**: skelbiamas kaip \"1-Bdr\" (1 miegamasis) — jei kelionėje 4 keliautojai, verta patvirtinti miegamųjų vietų skaičių prieš galutinį patvirtinimą.\n- **Booking nuorodos**: [Tripadvisor](https://www.tripadvisor.com/VacationRentalReview-g189541-d18852743-Sanders_Saint_Nice_1_Bdr_Apt_By_the_Canals-Copenhagen_Zealand.html) · [Expedia](https://www.expedia.com/Copenhagen-Hotels-Cozy-Apartment-In-Christianshavn.h45157366.Hotel-Information) · [Hotels.com](https://hotels.com/ho1446035712/cozy-apartment-in-christianshavn-copenhagen-copenhagen-denmark)\n\n### 2. Central Canal Apartments (Christianshavn) — atsarginis variantas\n- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai\n- **Kodėl tinka**: tame pačiame Christianshavn rajone prie kanalų, ~15 min pėsčiomis iki Strøget; kelios butų kategorijos, galimai tinka 4 žmonėms.\n- **Nuoroda**: [copenhagen-hotel.org](https://www.copenhagen-hotel.org/en/property/central-canal-apartments.html)\n\n### 3. CABINN Apartments — atsarginis variantas\n- **Kaina**: nerasta tiksli kaina paieškoje — tikrinti tiesiogiai (CABINN tinklas paprastai priklauso biudžetinei/vidutinei kategorijai)\n- **Kodėl tinka**: 4 asmenų 2 kambarių butas, **greta metro stoties**, pusryčiai siūlomi gretimame CABINN Metro (05:30–10:00 darbo dienomis, 06:00–10:30 savaitgaliais) — atitinka \"pusryčiai įskaičiuoti\" prioritetą, kurio pirmasis variantas neturi patvirtinto.\n- **Nuoroda**: [CABINN Apartments](https://en.cabinn.com/hotel/cabinn-apartments)\n\n**Neatitikimai/rizikos**: Nei vienam variantui nepavyko rasti patvirtintos kainos EUR valiuta tiesiogiai iš rezervacijos sistemos konkrečioms 2026-10-23–26 datoms — rekomenduoju patikrinti kainą ir laisvas vietas (ypač miegamųjų skaičių pagrindiniame bute) booking.com/Expedia tiesiogiai prieš galutinį patvirtinimą.",
  "booking_search": [
    {
      "city": "Kopenhaga",
      "name": "Sanders Saint-Nice 1-Bdr Apt by the Canals",
      "checkin": "2026-10-23",
      "checkout": "2026-10-26",
      "nights": 3,
      "price_per_night_eur": 140,
      "url": "https://www.booking.com/searchresults.html?ss=Sanders+Saint-Nice+1-Bdr+Apt+by+the+Canals%2C+Kopenhaga&checkin=2026-10-23&checkout=2026-10-26&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas ir Christianshavn\",\"stops\":[{\"name\":\"Kopenhagos oro uostas (CPH)\",\"lat\":55.618,\"lon\":12.6476,\"arrive\":\"09:40\",\"depart\":\"10:00\",\"maps_query\":\"Copenhagen Airport (CPH), Kastrup, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark\",\"notes\":\"Atvykimo skrydis iš Kauno. Atsiėmę bagažą, metro stotelėje nusipirkite bilietus Rejsebillet programėlėje arba automate (fizinis Rejsekort pamažu nebenaudojamas).\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Apartamentai Sanders Saint-Nice (Christianshavn)\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"10:16\",\"depart\":\"10:45\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Įsikurkite ir palikite bagažą – butas 3 min pėsčiomis nuo Christianshavn metro stotelės.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M2: Lufthavnen → Christianshavn (tiesioginis, ~14 min)\"},{\"name\":\"Vor Frelsers Kirke (bokštas)\",\"lat\":55.673,\"lon\":12.5942,\"arrive\":\"10:55\",\"depart\":\"12:45\",\"maps_query\":\"Vor Frelsers Kirke, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Vor%20Frelsers%20Kirke%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Garsieji išorės sukasi laiptai su vaizdu į Christianshavn. Bokštas kasdien 09:00–20:00 (gali uždaryti stiprų vėją/lietų – jei taip, apžiūrėkite tik bažnyčią). Bilietas į bokštą ~70 DKK. Dviračių takai (cykelsti) – niekada jais neikite pėsčiomis.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Pietūs – Christianshavns Bådudlejning og Café\",\"lat\":55.6757,\"lon\":12.592,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Christianshavns Bådudlejning og Café, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Jaukus kavinė tiesiai prie kanalo – geras smørrebrød ir vietinis alus.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nyhavn (diena)\",\"lat\":55.6799,\"lon\":12.5898,\"arrive\":\"14:20\",\"depart\":\"15:30\",\"maps_query\":\"Nyhavn, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Spalvingas kanalo krantas su laivais – klasikinė Kopenhagos atvirutė. Nemokama.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Amalienborg (kiemas, sargybos namai)\",\"lat\":55.684,\"lon\":12.5933,\"arrive\":\"15:40\",\"depart\":\"16:05\",\"maps_query\":\"Amalienborg, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Amalienborg%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karališkoji rezidencija – sargybos keitimas vyksta apie vidurdienį, bet kiemas gražus bet kuriuo metu. Muziejų aplankysime kitą rytą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Den Lille Havfrue (Mažoji jūrų nimfa)\",\"lat\":55.6929,\"lon\":12.5993,\"arrive\":\"16:25\",\"depart\":\"16:45\",\"maps_query\":\"Den Lille Havfrue, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Den%20Lille%20Havfrue%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Nedidelė, bet ikoniška skulptūra – trumpas vizitas užtenka. Popietė mažiau minios nei rytais, kai atvažiuoja turistų autobusai.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nyhavn vakare ir vakarienė (Nyhavns Færgekro)\",\"lat\":55.6797,\"lon\":12.5905,\"arrive\":\"17:10\",\"depart\":\"19:30\",\"maps_query\":\"Nyhavns Færgekro, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavns%20F%C3%A6rgekro%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Saulei nusileidus (~17:15) kanalas gražiausias apšviestas. Vakarienė tradicinėje danų restorane – rekomenduojamas smørrebrød ir žuvies patiekalai.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Grįžimas į apartamentus\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"19:50\",\"depart\":\"20:00\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Nakvynė Christianshavn.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":2,\"title\":\"Pilys ir muziejai\",\"stops\":[{\"name\":\"Rosenborg Slot\",\"lat\":55.6857,\"lon\":12.5777,\"arrive\":\"09:35\",\"depart\":\"11:00\",\"maps_query\":\"Rosenborg Slot, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Rosenborg%20Slot%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karūnos brangenybės ir karališkoji istorija. Žiemos darbo laikas (spalis–kovas) 10:00–16:00. Bilietas ~140 DKK, nemokamai <18 m.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 18 min pėsčiomis iki pilies (arba pasivaikščiokite po Kongens Have parką prieš atidarymą)\"},{\"name\":\"SMK – Statens Museum for Kunst\",\"lat\":55.6896,\"lon\":12.5799,\"arrive\":\"11:12\",\"depart\":\"12:40\",\"maps_query\":\"SMK - Statens Museum for Kunst, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=SMK%20-%20Statens%20Museum%20for%20Kunst%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Danijos nacionalinė dailės galerija. Šeštadienį dirba 10:00–18:00. Bilietas ~140 DKK, nemokamai <18 m.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Pietūs – Torvehallerne\",\"lat\":55.6839,\"lon\":12.5705,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Torvehallerne, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Torvehallerne%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Geriausia maisto turgavietė mieste – rekomenduojama Hallernes Smørrebrød prekystalis tradiciniam smørrebrød. Įėjimas nemokamas, mokama už prekes.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Christiansborg Slot\",\"lat\":55.6761,\"lon\":12.5789,\"arrive\":\"14:30\",\"depart\":\"16:00\",\"maps_query\":\"Christiansborg Palace, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christiansborg%20Palace%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Danijos parlamento būstinė, karališkosios reprezentacinės salės ir pilies griuvėsiai. Kasdien 10:00–17:00. Bilietas ~215 DKK internetu / 225 DKK vietoje, nemokamai <18 m.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Nationalmuseet\",\"lat\":55.6751,\"lon\":12.5748,\"arrive\":\"16:05\",\"depart\":\"17:00\",\"maps_query\":\"Nationalmuseet, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nationalmuseet%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Didžiausias Danijos muziejus, vikingų ir priešistorės kolekcijos. Dirba kasdien 10:00–17:00. Bilietas ~150 DKK – patikrinkite prie kasos, kai kurie šaltiniai teigia, kad nuolatinė ekspozicija nemokama.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Vakarienė – Ved Kanalen\",\"lat\":55.6745,\"lon\":12.592,\"arrive\":\"18:00\",\"depart\":\"19:30\",\"maps_query\":\"Ved Kanalen, Overgaden Neden Vandet, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ved%20Kanalen%2C%20Overgaden%20Neden%20Vandet%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Aukštai vertinamas tradicinis danų restoranas tiesiai prie kanalo, netoli nakvynės vietos.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":3,\"title\":\"Christiania, Tivoli ir Deep Purple koncertas\",\"stops\":[{\"name\":\"Freetown Christiania\",\"lat\":55.6738,\"lon\":12.5983,\"arrive\":\"09:20\",\"depart\":\"11:00\",\"maps_query\":\"Freetown Christiania, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Freetown%20Christiania%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Savivaldi alternatyvi bendruomenė, gatvės menas. Lankykite tik dienos metu. Pusher Street – nefotografuokite, laikykitės taisyklių. Nemokama. Šiąnakt (spalio 25-osios naktį) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Ny Carlsberg Glyptotek\",\"lat\":55.6735,\"lon\":12.5727,\"arrive\":\"11:25\",\"depart\":\"12:50\",\"maps_query\":\"Ny Carlsberg Glyptotek, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ny%20Carlsberg%20Glyptotek%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Antikos ir impresionistų kolekcija, žiemos sodas po stiklo kupolu. Sekmadienį dirba 10:00–17:00. Bilietas ~125 DKK.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv, persėdimas į M3 → Rådhuspladsen (~18 min iš viso), toliau 5 min pėsčiomis\"},{\"name\":\"Pietūs – Tivoli Food Hall\",\"lat\":55.673,\"lon\":12.5678,\"arrive\":\"13:00\",\"depart\":\"14:00\",\"maps_query\":\"Tivoli Food Hall, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tivoli%20Food%20Hall%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Pietūs Tivoli sodų maisto salėje – įskaičiuota į bendrą Tivoli bilietą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Tivoli Gardens (Helovino tema)\",\"lat\":55.6736,\"lon\":12.5681,\"arrive\":\"14:00\",\"depart\":\"16:00\",\"maps_query\":\"Tivoli Gardens, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tivoli%20Gardens%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Istorinis pramogų parkas, per visą kelionę vyksta Helovino sezonas su 20 000 moliūgų dekoracijų. Vartai 11:00–23:00. Bilietas ~200 DKK suaugusiam.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Vakarienė – Field's\",\"lat\":55.6269,\"lon\":12.5751,\"arrive\":\"16:25\",\"depart\":\"17:45\",\"maps_query\":\"Field's, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Field%27s%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Didelis prekybos centras su maisto kiemeliu prie pat arenos – patogu prieš koncertą.\",\"arrive_by\":\"transit\",\"transit\":\"Traukinys/S-tog: København H → Ørestad (~7 min), toliau 5 min pėsčiomis\"},{\"name\":\"Royal Arena – Deep Purple koncertas\",\"lat\":55.6256,\"lon\":12.5732,\"arrive\":\"17:50\",\"depart\":\"22:00\",\"maps_query\":\"Royal Arena, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Royal%20Arena%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Durys atsidaro ~18:00, koncerto pradžia orientaciniai ~19:00–20:00 (patikslinti artimiau datai livenation.dk). Dėl vasaros laiko pabaigos šią naktį patikrinkite vėlyvo metro tvarkaraštį grįžtant.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Grįžimas į apartamentus\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"22:20\",\"depart\":\"22:30\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Po koncerto grįžtama tiesioginiu metro. Patikrinkite paskutinio traukinio laiką.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1: Ørestad → Christianshavn (~20 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kopenhaga\"},{\"number\":4,\"title\":\"Amalienborg, Nyhavn ir skrydis namo\",\"stops\":[{\"name\":\"Amalienborg Museum\",\"lat\":55.684,\"lon\":12.5933,\"arrive\":\"09:50\",\"depart\":\"11:00\",\"maps_query\":\"Amalienborg Museum, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Amalienborg%20Museum%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Karališkųjų apartamentų interjerai. Prieš lapkričio 1 d. pirmadieniais dirba 10:00–15:00. Bilietas ~125 DKK internetu / 135 DKK vietoje, nemokamai <18 m.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Christianshavn → Kongens Nytorv (~4 min), toliau 8 min pėsčiomis\"},{\"name\":\"Nyhavn (paskutinis apsilankymas)\",\"lat\":55.6799,\"lon\":12.5898,\"arrive\":\"11:10\",\"depart\":\"11:50\",\"maps_query\":\"Nyhavn, København, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20K%C3%B8benhavn%2C%20Denmark\",\"notes\":\"Trumpas laikas suvenyrams ir paskutinėms nuotraukoms prie kanalo.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Apartamentai – bagažas ir išsiregistravimas\",\"lat\":55.67,\"lon\":12.5945,\"arrive\":\"12:00\",\"depart\":\"12:20\",\"maps_query\":\"Christianshavns Torv, 1411 København K, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Christianshavns%20Torv%2C%201411%20K%C3%B8benhavn%20K%2C%20Denmark\",\"notes\":\"Atsiimkite bagažą ir išsiregistruokite.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)\"},{\"name\":\"Kopenhagos oro uostas (CPH) – pietūs ir skrydis\",\"lat\":55.618,\"lon\":12.6476,\"arrive\":\"12:40\",\"depart\":\"15:15\",\"maps_query\":\"Copenhagen Airport (CPH), Kastrup, Denmark\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%20%28CPH%29%2C%20Kastrup%2C%20Denmark\",\"notes\":\"Grįžtamasis skrydis CPH→KUN išvyksta 15:15. Pietus patogu užkąsti pačiame oro uoste – daug kavinių ir restoranų abipus saugumo patikros. Rekomenduojama iš anksto atlikti registraciją internetu, liks pakankamai laiko bagažo pridavimui ir saugumo patikrai.\",\"arrive_by\":\"transit\",\"transit\":\"Metro M2: Christianshavn → Lufthavnen (tiesioginis, ~14 min)\"}],\"driving_minutes\":0,\"overnight_city\":\"Kaunas\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas ir Christianshavn",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Copenhagen+Airport+%28CPH%29,+Kastrup,+Denmark&destination=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&travelmode=transit",
        "https://www.google.com/maps/dir/?api=1&origin=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&destination=Nyhavns+F%C3%A6rgekro,+K%C3%B8benhavn,+Denmark&travelmode=walking&waypoints=Vor+Frelsers+Kirke,+K%C3%B8benhavn,+Denmark|Christianshavns+B%C3%A5dudlejning+og+Caf%C3%A9,+K%C3%B8benhavn,+Denmark|Nyhavn,+K%C3%B8benhavn,+Denmark|Amalienborg,+K%C3%B8benhavn,+Denmark|Den+Lille+Havfrue,+K%C3%B8benhavn,+Denmark",
        "https://www.google.com/maps/dir/?api=1&origin=Nyhavns+F%C3%A6rgekro,+K%C3%B8benhavn,+Denmark&destination=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&travelmode=transit"
      ],
      "modes": [
        "transit",
        "walk",
        "transit"
      ]
    },
    {
      "day": 2,
      "title": "Pilys ir muziejai",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Rosenborg+Slot,+K%C3%B8benhavn,+Denmark&destination=Ved+Kanalen,+Overgaden+Neden+Vandet,+K%C3%B8benhavn,+Denmark&travelmode=walking&waypoints=SMK+-+Statens+Museum+for+Kunst,+K%C3%B8benhavn,+Denmark|Torvehallerne,+K%C3%B8benhavn,+Denmark|Christiansborg+Palace,+K%C3%B8benhavn,+Denmark|Nationalmuseet,+K%C3%B8benhavn,+Denmark"
      ],
      "modes": [
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Christiania, Tivoli ir Deep Purple koncertas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Freetown+Christiania,+K%C3%B8benhavn,+Denmark&destination=Ny+Carlsberg+Glyptotek,+K%C3%B8benhavn,+Denmark&travelmode=transit",
        "https://www.google.com/maps/dir/?api=1&origin=Ny+Carlsberg+Glyptotek,+K%C3%B8benhavn,+Denmark&destination=Tivoli+Gardens,+K%C3%B8benhavn,+Denmark&travelmode=walking&waypoints=Tivoli+Food+Hall,+K%C3%B8benhavn,+Denmark",
        "https://www.google.com/maps/dir/?api=1&origin=Tivoli+Gardens,+K%C3%B8benhavn,+Denmark&destination=Field%27s,+K%C3%B8benhavn,+Denmark&travelmode=transit",
        "https://www.google.com/maps/dir/?api=1&origin=Field%27s,+K%C3%B8benhavn,+Denmark&destination=Royal+Arena,+K%C3%B8benhavn,+Denmark&travelmode=walking",
        "https://www.google.com/maps/dir/?api=1&origin=Royal+Arena,+K%C3%B8benhavn,+Denmark&destination=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&travelmode=transit"
      ],
      "modes": [
        "transit",
        "walk",
        "transit",
        "walk",
        "transit"
      ]
    },
    {
      "day": 4,
      "title": "Amalienborg, Nyhavn ir skrydis namo",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Amalienborg+Museum,+K%C3%B8benhavn,+Denmark&destination=Nyhavn,+K%C3%B8benhavn,+Denmark&travelmode=walking",
        "https://www.google.com/maps/dir/?api=1&origin=Nyhavn,+K%C3%B8benhavn,+Denmark&destination=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&travelmode=transit",
        "https://www.google.com/maps/dir/?api=1&origin=Christianshavns+Torv,+1411+K%C3%B8benhavn+K,+Denmark&destination=Copenhagen+Airport+%28CPH%29,+Kastrup,+Denmark&travelmode=transit"
      ],
      "modes": [
        "walk",
        "transit",
        "transit"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Kopenhagos oro uostas (CPH)",
        "to_stop": "Apartamentai Sanders Saint-Nice (Christianshavn)",
        "mode": "transit",
        "distance_km": 4.0,
        "minutes": 16,
        "transit_kind": "metro",
        "transit": "Metro M2: Lufthavnen → Christianshavn (tiesioginis, ~14 min), bilietas Rejsebillet programėlėje arba automate",
        "road": "",
        "icon": "🚇"
      },
      {
        "day": 1,
        "from_stop": "Apartamentai Sanders Saint-Nice (Christianshavn)",
        "to_stop": "Vor Frelsers Kirke (bokštas)",
        "mode": "walk",
        "distance_km": 0.5,
        "minutes": 6,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per Christianshavn kvartalą",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Vor Frelsers Kirke (bokštas)",
        "to_stop": "Pietūs – Christianshavns Bådudlejning og Café",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 8,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per Christianshavn",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Pietūs – Christianshavns Bådudlejning og Café",
        "to_stop": "Nyhavn (diena)",
        "mode": "walk",
        "distance_km": 1.1,
        "minutes": 15,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per kanalą jungiantį tiltą į senamiestį",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Nyhavn (diena)",
        "to_stop": "Amalienborg (kiemas, sargybos namai)",
        "mode": "walk",
        "distance_km": 0.7,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis senamiesčiu",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Amalienborg (kiemas, sargybos namai)",
        "to_stop": "Den Lille Havfrue (Mažoji jūrų nimfa)",
        "mode": "walk",
        "distance_km": 1.2,
        "minutes": 15,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis palei pakrantę",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Den Lille Havfrue (Mažoji jūrų nimfa)",
        "to_stop": "Nyhavn vakare ir vakarienė (Nyhavns Færgekro)",
        "mode": "walk",
        "distance_km": 1.8,
        "minutes": 24,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis palei pakrantę atgal į Nyhavn",
        "icon": "🚶"
      },
      {
        "day": 1,
        "from_stop": "Nyhavn vakare ir vakarienė (Nyhavns Færgekro)",
        "to_stop": "Grįžimas į apartamentus",
        "mode": "transit",
        "distance_km": 2.0,
        "minutes": 20,
        "transit_kind": "metro",
        "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)",
        "road": "",
        "icon": "🚇"
      },
      {
        "day": 2,
        "from_stop": "Rosenborg Slot",
        "to_stop": "SMK – Statens Museum for Kunst",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 8,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per Kongens Have parką",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "SMK – Statens Museum for Kunst",
        "to_stop": "Pietūs – Torvehallerne",
        "mode": "walk",
        "distance_km": 1.1,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis centro gatvėmis",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Pietūs – Torvehallerne",
        "to_stop": "Christiansborg Slot",
        "mode": "walk",
        "distance_km": 1.4,
        "minutes": 18,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Christiansborg Slot",
        "to_stop": "Nationalmuseet",
        "mode": "walk",
        "distance_km": 0.3,
        "minutes": 4,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis tuo pačiu kvartalu",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Nationalmuseet",
        "to_stop": "Vakarienė – Ved Kanalen",
        "mode": "walk",
        "distance_km": 1.4,
        "minutes": 19,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis link Christianshavn kanalo",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Freetown Christiania",
        "to_stop": "Ny Carlsberg Glyptotek",
        "mode": "transit",
        "distance_km": 3.5,
        "minutes": 25,
        "transit_kind": "metro",
        "transit": "Metro M1/M2: Christianshavn → Kongens Nytorv, persėdimas į M3 → Rådhuspladsen, toliau ~5 min pėsčiomis",
        "road": "",
        "icon": "🚇"
      },
      {
        "day": 3,
        "from_stop": "Ny Carlsberg Glyptotek",
        "to_stop": "Pietūs – Tivoli Food Hall",
        "mode": "walk",
        "distance_km": 0.5,
        "minutes": 7,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis centro gatvėmis",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Pietūs – Tivoli Food Hall",
        "to_stop": "Tivoli Gardens (Helovino tema)",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "tas pats sodo kompleksas",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Tivoli Gardens (Helovino tema)",
        "to_stop": "Vakarienė – Field's",
        "mode": "transit",
        "distance_km": 6.0,
        "minutes": 25,
        "transit_kind": "train",
        "transit": "Regioninis/Öresund traukinys (ne S-tog): København H → Ørestad, ~7 min, kursuoja kas 20 min, toliau ~5 min pėsčiomis",
        "road": "",
        "icon": "🚆"
      },
      {
        "day": 3,
        "from_stop": "Vakarienė – Field's",
        "to_stop": "Royal Arena – Deep Purple koncertas",
        "mode": "walk",
        "distance_km": 0.3,
        "minutes": 4,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per Ørestad rajoną",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Royal Arena – Deep Purple koncertas",
        "to_stop": "Grįžimas į apartamentus",
        "mode": "transit",
        "distance_km": 4.0,
        "minutes": 20,
        "transit_kind": "metro",
        "transit": "Metro M1: Ørestad → Christianshavn (~8 min, tiesioginis)",
        "road": "",
        "icon": "🚇"
      },
      {
        "day": 4,
        "from_stop": "Amalienborg Museum",
        "to_stop": "Nyhavn (paskutinis apsilankymas)",
        "mode": "walk",
        "distance_km": 0.7,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis senamiesčiu",
        "icon": "🚶"
      },
      {
        "day": 4,
        "from_stop": "Nyhavn (paskutinis apsilankymas)",
        "to_stop": "Apartamentai – bagažas ir išsiregistravimas",
        "mode": "transit",
        "distance_km": 2.0,
        "minutes": 15,
        "transit_kind": "metro",
        "transit": "Metro M1/M2: Kongens Nytorv → Christianshavn (~4 min)",
        "road": "",
        "icon": "🚇"
      },
      {
        "day": 4,
        "from_stop": "Apartamentai – bagažas ir išsiregistravimas",
        "to_stop": "Kopenhagos oro uostas (CPH) – pietūs ir skrydis",
        "mode": "transit",
        "distance_km": 4.0,
        "minutes": 20,
        "transit_kind": "metro",
        "transit": "Metro M2: Christianshavn → Lufthavnen (tiesioginis, ~14 min)",
        "road": "",
        "icon": "🚇"
      }
    ],
    "traveler_tips": [
      "Visoms viešojo transporto atkarpoms patogiausia pirkti bilietus Rejsebillet programėlėje telefone – ji galioja metro, traukiniams ir autobusams pagal zonas.",
      "Apartamentai Christianshavn rajone yra per kelias minutes pėsčiomis nuo Christianshavn metro stotelės – iš jos tiesioginiu M2 pasiekiamas oro uostas, o M1/M2 – Kongens Nytorv senamiesčio link.",
      "Keliaujant iš Tivoli sodų į Field's/Royal Areną, naudojamas ne S-tog, o regioninis/Öresund traukinys – jis kursuoja tik kas 20 min, todėl geriau iš Tivoli išeiti kelias minutes anksčiau arba pasitikrinti tikslų išvykimo laiką.",
      "Jei į Rosenborg pilį atvykstate anksčiau nei ji atidaroma (10:00 žiemą), gražiausia palaukti pasivaikščiojant po Kongens Have parką prie pat pilies.",
      "Naktį tarp šeštadienio ir sekmadienio (spalio 24–25 d.) Danijoje baigiasi
… (sutrumpinta, iš viso 95343 simbolių)
```

Current page:
[HTML puslapis, 67 KB — nerodomas]

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

```
atidarote (10:00 žiemą), gražiausia palaukti pasivaikščiojant po Kongens Have parką prie pat pilies.</li>
    <li>🕐 <strong>Laiko pakeitimas:</strong> naktį tarp šeštadienio ir sekmadienio (spalio 24–25 d.) Danijoje baigiasi vasaros laikas – laikrodžiai pasukami 1 val. atgal, patikrinkite, ar telefonas laiką pakeičia automatiškai.</li>
  </ul>
</section>

<section id="pasiimti">
  <h2>🎒 Ką pasiimti</h2>
  <!-- PACKING_LIST -->
</section>

<section id="pavalgyti">
  <h2>🍽 Kur pavalgyti</h2>

  <h3>Diena 1</h3>
  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Christianshavns%20B%C3%A5dudlejning%20og%20Caf%C3%A9%2C%20Overgaden%20Neden%20Vandet%2029%2C%201414%20K%C3%B8benhavn%20K" target="_blank">Christianshavns Bådudlejning og Café</a></h3>
    <p>Netoli: Vor Frelsers Kirke / pietų stotelė maršrute · kanalo kavinė valčių nuomos punkte · ~20 €/asmeniui</p>
    <p>Veikia nuo 1905 m., jauki kavinė tiesiai ant kanalo su valčių nuoma – gera vieta atsipūsti po bokšto lipimo Vor Frelsers Kirke.</p>
    <p><strong>Ką paragauti čia</strong></p>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/sm-rrebrodas-ad36844c.jpg" alt="Smørrebrodų rinkinys"><figcaption>Smørrebrodų rinkinys (Smørrebrød) – 18 €<br><span class="credit">Kritzolina, CC BY-SA 4.0</span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/bleskiver-blyneliai-b7aa8791.jpg" alt="Æbleskiver"><figcaption>Æbleskiver su uogiene ir cukraus pudra – 9 €<br><span class="credit">JoachimK, Public domain</span></figcaption></figure>
    </div>
    <p><em>Lašišos salotos (Laksesalat), 15 € (nuotraukos nėra)</em></p>
  </div>

  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Nyhavns%20F%C3%A6rgekro%2C%20Nyhavn%205%2C%201051%20K%C3%B8benhavn%20K" target="_blank">Nyhavns Færgekro</a></h3>
    <p>Netoli: Nyhavn vakare / vakarienė maršrute · tradicinė danų krogė (taverna) · ~28 €/asmeniui · Vakarienė ~38 € asmeniui</p>
    <p>Vienas geriausių kainos/kokybės santykių Nyhavn kanalo pakrantėje – garsus savo silkių bufetu ir terasa prie vandens saulėlydžio metu.</p>
    <p><strong>Ką paragauti čia</strong></p>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/marinuota-silk-f7dc6724.jpg" alt="Sildebuffet"><figcaption>Silkių bufetas (Sildebuffet) – 25 €<br><span class="credit">cyclone bill, CC BY-SA 2.0</span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/krintanti-vaig-d-72b6718b.jpg" alt="Stjerneskud"><figcaption>Krintanti žvaigždė (Stjerneskud) – 20 €<br><span class="credit">RhinoMind, CC BY-SA 4.0</span></figcaption></figure>
    </div>
    <p><em>Namų gamybos akvavitas (Akvavit), 6 € (nuotraukos nėra)</em></p>
  </div>

  <h3>Diena 2</h3>
  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Hallernes%20Sm%C3%B8rrebr%C3%B8d%20%28Torvehallerne%29%2C%20Frederiksborggade%2021%2C%201360%20K%C3%B8benhavn%20K%20%28Torvehallerne%2C%20Hal%201%29" target="_blank">Hallernes Smørrebrød (Torvehallerne)</a></h3>
    <p>Netoli: Rosenborg Slot / SMK, pietų stotelė maršrute · turgavietės smørrebrodo prekystalis · ~16 €/asmeniui</p>
    <p>Geriausios reputacijos smørrebrodo prekystalis mieste, tiesiai turgavietėje tarp šviežios žuvies ir sūrių prekystalių.</p>
    <p><strong>Ką paragauti čia</strong></p>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/kreveti-sm-rrebrodas-1879ff96.jpg" alt="Rejestykke"><figcaption>Krevetių smørrebrodas (Rejestykke) – 17 €<br><span class="credit">XYZA-2400, CC0</span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/jautienos-tataras-7371f720.jpg" alt="Tatar"><figcaption>Jautienos tataras (Tatar) – 14 €<br><span class="credit">Dr. Bernd Gross, CC BY-SA 4.0</span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/kepta-kiauliena-su-spirgu-iais-b8c80393.jpg" alt="Flæskesteg"><figcaption>Kepta kiauliena su spirgučiais (Flæskesteg) – 13 €<br><span class="credit">fru_green, CC BY-SA 2.0</span></figcaption></figure>
    </div>
  </div>

  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Restaurant%20Kanalen%2C%20Wilders%20Plads%202%2C%201403%20K%C3%B8benhavn%20K" target="_blank">Restaurant Kanalen</a></h3>
    <p>Netoli: vakarienės stotelė Ved Kanalen, 5 min nuo nakvynės Christianshavn · aukštesnės klasės danų-prancūziška virtuvė (Michelin Plate) · ~55 €/asmeniui · Vakarienė ~65 € asmeniui</p>
    <p>Michelin gide pažymėtas restoranas tiesiai ant Christianshavn kanalo kranto – atmosfera atpalaiduojanti, be snobizmo, nepaisant apdovanojimo.</p>
    <p><strong>Ką paragauti čia:</strong> Sezoninis degustacinis meniu, 3 patiekalai (Menu), 47 €; Sūris su traškia duona (Ost med sprødt brød), 7 €; Šokoladinis panna cotta (Chokolade panna cotta), 11 €</p>
  </div>

  <h3>Diena 3</h3>
  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Tivoli%20Food%20Hall%2C%20Bernstorffsgade%203%2C%201577%20K%C3%B8benhavn%20V%20%28Tivoli%20Gardens%29" target="_blank">Tivoli Food Hall</a></h3>
    <p>Netoli: Tivoli Gardens, pietų stotelė maršrute · maisto salė su 15-20 prekystalių · ~16 €/asmeniui</p>
    <p>Įvairiausių danų greito maisto prekystalių rinkinys viename stogo po – praktiška pietų pertrauka tarp Christiania ir Tivoli.</p>
    <p><strong>Ką paragauti čia</strong></p>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/kreveti-sm-rrebrodas-1879ff96.jpg" alt="Rejemad"><figcaption>Krevetių smørrebrodas (Rejemad, Hallernes Smørrebrød) – 17 €<br><span class="credit">XYZA-2400, CC0</span></figcaption></figure>
    </div>
    <p><em>Klasikinis danų dešrainis su traškiais svogūnais (Ristet hotdog, Tivoligrillen), 7 € · Lašišos smørrebrodas (Laksemad), 16 € (nuotraukų nėra)</em></p>
  </div>

  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Field%27s%2C%20Arne%20Jacobsens%20All%C3%A9%2012%2C%202300%20K%C3%B8benhavn%20S" target="_blank">Field's</a></h3>
    <p>Netoli: Royal Arena / Deep Purple koncertas · prekybos centro maisto kiemelis · ~14 €/asmeniui · Vakarienė ~16 € asmeniui</p>
    <p>Ne tradicinė virtuvė, bet greitas ir patikimas pasirinkimas prieš koncertą – daug prekystalių vos prie pat arenos.</p>
    <p><strong>Ką paragauti čia:</strong> Burgeris (Sunset Boulevard, danų tinklas), Original burger, 10 €; Bulvytės (Pommes frites), 5 €; Sumuštinis (Joe &amp; The Juice), Sandwich, 8 €</p>
  </div>

  <h3>Diena 4</h3>
  <div class="card">
    <h3 style="margin-top:0;"><a href="https://www.google.com/maps/search/?api=1&amp;query=Aamanns%20Deli%20%26%20Take%20Away%20%28CPH%20oro%20uostas%29%2C%20Copenhagen%20Airport%2C%20Terminal%203%2C%202770%20Kastrup" target="_blank">Aamanns Deli &amp; Take Away (CPH oro uostas)</a></h3>
    <p>Netoli: Kopenhagos oro uostas (CPH), pietūs prieš skrydį · smørrebrodo parduotuvė oro uoste · ~14 €/asmeniui</p>
    <p>Geriausiai vertinama tradicinio smørrebrodo vieta oro uoste – paskutinė galimybė paragauti danų virtuvės prieš skrydį namo.</p>
    <p><strong>Ką paragauti čia</strong></p>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/marinuota-silk-f7dc6724.jpg" alt="Sildemad"><figcaption>Silkės smørrebrodas (Sildemad) – 11 €<br><span class="credit">cyclone bill, CC BY-SA 2.0</span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/kreveti-sm-rrebrodas-1879ff96.jpg" alt="Rejemad"><figcaption>Krevetių smørrebrodas (Rejemad) – 15 €<br><span class="credit">XYZA-2400, CC0</span></figcaption></figure>
    </div>
    <p><em>Rostbifo smørrebrodas (Roastbeefmad), 13 € (nuotraukos nėra)</em></p>
  </div>

  <h3>🍸 Barai</h3>
  <ul>
    <li><strong>Hviids Vinstue</strong> (Diena 1) – Kongens Nytorv 19, prie Kongens Nytorv/Nyhavn. Kopenhagos seniausias nenutrūkstamai veikiantis baras, įkurtas 1723 m. – tamsaus medžio interjeras, žvakės ir senųjų menininkų portretai, matęs didžiuosius miesto gaisrus ir du pasaulinius karus. <a href="https://www.google.com/maps/search/?api=1&amp;query=Hviids%20Vinstue%2C%20Kongens%20Nytorv%2019%2C%201050%20K%C3%B8benhavn%20K" target="_blank">📍 Google Maps</a></li>
  </ul>
</section>

<section id="paragauti">
  <h2>🥘 Ką paragauti</h2>
  <div class="dish-grid">
    <figure>
      <img class="spot-thumb dish-thumb" src="images/sm-rrebrodas-ad36844c.jpg" alt="Smørrebrodas">
      <figcaption><strong>Smørrebrodas</strong><br>Atviras ruginės duonos sumuštinis su įvairiais priedais (silke, kiauliena, krevetėmis, kiaušiniu) – danų kasdienio maisto pagrindas.<br>9–18 €<br>Kur: Christianshavns Bådudlejning og Café, Nyhavns Færgekro, Hallernes Smørrebrød (Torvehallerne), Tivoli Food Hall, Aamanns Deli &amp; Take Away (CPH oro uostas)<br><span class="credit">Kritzolina, CC BY-SA 4.0</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/marinuota-silk-f7dc6724.jpg" alt="Sild">
      <figcaption><strong>Marinuota silkė (Sild)</strong><br>Marinuota silkė ant ruginės duonos, dažnai siūloma keliomis padažų versijomis – klasikinis danų užkandis prie akvavito.<br>10–15 €<br>Kur: Nyhavns Færgekro, Aamanns Deli &amp; Take Away (CPH oro uostas)<br><span class="credit">cyclone bill, CC BY-SA 2.0</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/krintanti-vaig-d-72b6718b.jpg" alt="Stjerneskud">
      <figcaption><strong>Krintanti žvaigždė (Stjerneskud)</strong><br>Šventinis smørrebrodas su kepta ir virta žuvimis, krevetėmis, majonezu ir ikrais – vienas populiariausių restoranų patiekalų.<br>15–22 €<br>Kur: Hallernes Smørrebrød (Torvehallerne), Nyhavns Færgekro<br><span class="credit">RhinoMind, CC BY-SA 4.0</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/frikadel-s-9e606cdd.jpg" alt="Frikadeller">
      <figcaption><strong>Frikadelės (Frikadeller)</strong><br>Kiaulienos ir jautienos maltinukai, patiekiami su ruginę duona ir raudonaisiais kopūstais arba bulvėmis – namų virtuvės klasika.<br>12–18 €<br>Kur: Nyhavns Færgekro, Restaurant Kanalen<br><span class="credit">cyclonebill, CC BY-SA 2.0</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/kepta-kiauliena-su-spirgu-iais-b8c80393.jpg" alt="Flæskesteg">
      <figcaption><strong>Kepta kiauliena su spirgučiais (Flæskesteg)</strong><br>Keptas kiaulienos sprandinė su traškia odele, patiekiama su raudonaisiais kopūstais ir bulvėmis – tradicinis šventinis patiekalas.<br>13–18 €<br>Kur: Hallernes Smørrebrød (Torvehallerne), Nyhavns Færgekro<br><span class="credit">fru_green, CC BY-SA 2.0</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/bleskiver-blyneliai-b7aa8791.jpg" alt="Æbleskiver">
      <figcaption><strong>Æbleskiver blyneliai</strong><br>Apvalūs, pūsti blyneliai, keliami specialioje keptuvėje, patiekiami su uogiene ir cukraus pudra – populiarūs rudens/žiemos sezonu.<br>6–10 €<br>Kur: Christianshavns Bådudlejning og Café, Tivoli Food Hall<br><span class="credit">JoachimK, Public domain</span></figcaption>
    </figure>
    <figure>
      <figcaption><strong>Danų dešrainis (Ristet hotdog)</strong><br>Keptas dešrainis su traškiais svogūnais, raugintais agurkais, garstyčiomis ir remulado padažu – gatvės maisto klasika.<br>6–9 €<br>Kur: Tivoli Food Hall, Field's<br><span class="credit">(nuotraukos nėra)</span></figcaption>
    </figure>
    <figure>
      <img class="spot-thumb dish-thumb" src="images/dano-pyragaitis-c2d2dda0.jpg" alt="Dano pyragaitis">
      <figcaption><strong>Dano pyragaitis (Wienerbrød / kanelsnegl)</strong><br>Sluoksniuotos tešlos pyragaitis, dažniausiai su cinamonu ar vaisių įdaru – rytinis ar popietinis skanėstas su kava.<br>4–6 €<br>Kur: Tivoli Food Hall, Aamanns Deli &amp; Take Away (CPH oro uostas)<br><span class="credit">Peter Isotalo, CC BY-SA 3.0</span></figcaption>
    </figure>
  </div>
</section>

<section>
  <h2>📋 Praktinė info kelionei</h2>
  <div class="card">
    <ul>
      <li>✈️ Skrydis KUN → CPH: 09:10–09:40 (2026-10-23)</li>
      <li>✈️ Skrydis CPH → KUN: 15:15–17:45 (2026-10-26)</li>
      <li>🕐 Butas – atsiskaitymas: ___ : ___ · atsiregistravimas: 12:00</li>
      <li>📞 Kelionės koordinatorius: _____________</li>
      <li>🏥 Draudimo kortelės/EHIC numeris: _____________</li>
    </ul>
  </div>
</section>

</div>

<div id="lightbox-overlay"><img id="lightbox-img" src="" alt=""></div>

<footer>
  <!-- BUILD_TIME -->
</footer>

<script>
document.addEventListener('click', function(e){
  var img = e.target.closest('.spot-thumb');
  if(img){
    var overlay = document.getElementById('lightbox-overlay');
    var lbImg = document.getElementById('lightbox-img');
    lbImg.src = img.src;
    lbImg.alt = img.alt || '';
    overlay.classList.add('open');
    return;
  }
  if(e.target.id === 'lightbox-overlay' || e.target.id === 'lightbox-img'){
    document.getElementById('lightbox-overlay').classList.remove('open');
  }
});
document.addEventListener('keydown', function(e){
  if(e.key === 'Escape'){
    document.getElementById('lightbox-overlay').classList.remove('open');
  }
});
</script>

</body>
</html>
```

</details>

