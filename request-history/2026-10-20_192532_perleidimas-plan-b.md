# Perleidimas nuo žingsnio „Planas B“ — 2026-10-20 19:25:32 UTC

- **Kelionė:** `d85b1e13fecc`
- **Pradžia / pabaiga:** 2026-10-20 19:25:32 → 19:35:59 (10 min.)
- **Agentų rinkinys:** Base
- **Rezultatas:** ❌ Nepavyko
- **Klaida:** Kelių duomenų tarnyba (Overpass) šiuo metu nepasiekiama, todėl nepavyko patikrinti šių Plano B kelių:
- Day 2: Nikolaj Kunsthal -> Reffen
Tai ne kelio problema -- pakartok „↻ Planas B“ po kurio laiko.

## Eiga

- `19:25:32` Perleidžiama nuo žingsnio: plan_b...
- `19:25:32` Planas B blogam orui (alternatyvos ir kelių patikra)...
- `19:35:59` Nepavyko: Kelių duomenų tarnyba (Overpass) šiuo metu nepasiekiama, todėl nepavyko patikrinti šių Plano B kelių:
- Day 2: Nikolaj Kunsthal -> Reffen
Tai ne kelio problema -- pakartok „↻ Planas B“ po kurio laiko.

## Agentų kvietimai (1)

### 1. Planas B — 19:31:55 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 383.7 s
- **Sistemos promptas:** `prompts/plan_b.md`

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

**Itinerary (main plan):**

```json
{
  "days": [
    {
      "number": 1,
      "title": "1 diena (2026-10-23, penktadienis): Atvykimas ir Christianshavn",
      "stops": [
        {
          "name": "Kopenhagos oro uostas (CPH)",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "09:40",
          "depart": "10:10",
          "maps_query": "Copenhagen Airport, Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%2C%20Kastrup%2C%20Denmark",
          "notes": "Atvykimas iš Kauno. Atsiėmę bagažą, pasukite pas M2 metro ženklus – tiesioginis traukinys į centrą (Christianshavn / Kongens Nytorv), persėdinėti nereikia. Bilietą pirkite 'Rejsebillet' programėlėje arba automate stotyje. Bagažą pasiimsite su savimi visą dieną – į apartamentus vyksime tik vakare, nes įsiregistravimas galimas nuo 15:00."
        },
        {
          "name": "Vor Frelsers Kirke (Išganytojo bažnyčia)",
          "lat": 55.6725,
          "lon": 12.5939,
          "arrive": "10:35",
          "depart": "11:35",
          "maps_query": "Vor Frelsers Kirke, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Vor%20Frelsers%20Kirke%2C%20Copenhagen%2C%20Denmark",
          "notes": "Tiesioginis M2 metro reisas iš oro uosto iki Christianshavn stotelės užtrunka apie 17 min, dar ~5 min pėsčiomis iki bažnyčios. Žymūs išoriniai sraigtiniai laiptai ant bokšto – vaizdas į visą Christianshavn ir senamiestį. Bilietas į bokštą ~70 DKK, atvira 09:00–20:00. Bokštas uždaromas vėjuotu ar lietingu oru – tokiu atveju užeikite tik į pačią bažnyčią (nemokama, 11:00–15:30). Po apžiūros liks laisvo laiko pasivaikščioti Christianshavn kanalų pakrantėmis prieš pietus."
        },
        {
          "name": "Café Wilder",
          "lat": 55.6719,
          "lon": 12.592,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Café Wilder, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Caf%C3%A9%20Wilder%2C%20Copenhagen%2C%20Denmark",
          "notes": "Pietūs jaukioje Christianshavn kavinėje su prancūzišku-danišku bistro meniu – geras pirmas įspūdis apie vietinę virtuvę."
        },
        {
          "name": "Nyhavn",
          "lat": 55.6799,
          "lon": 12.59,
          "arrive": "14:30",
          "depart": "15:30",
          "maps_query": "Nyhavn, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Nyhavn%2C%20Copenhagen%2C%20Denmark",
          "notes": "~12 min pėsčiomis nuo Café Wilder. Spalvingas kanalo krantas su senais laivais – pati žinomiausia Kopenhagos vieta. Saugokite daiktus, vieta turistinė ir gana žmonių pilna."
        },
        {
          "name": "Rundetårn (Apvalusis bokštas)",
          "lat": 55.6808,
          "lon": 12.5775,
          "arrive": "15:45",
          "depart": "16:45",
          "maps_query": "Rundetårn, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Rundet%C3%A5rn%2C%20Copenhagen%2C%20Denmark",
          "notes": "~10 min pėsčiomis nuo Nyhavn. Seniausia veikianti observatorija Europoje – į viršų kyla ne laiptai, o sraigtinė rampa. Bilietas 60 DKK, atvira 10:00–18:00. Geras laikas pataikyti į saulėlydį senamiesčio panoramoje."
        },
        {
          "name": "Torvehallerne maisto turgus",
          "lat": 55.6838,
          "lon": 12.5683,
          "arrive": "17:00",
          "depart": "18:45",
          "maps_query": "Torvehallerne, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Torvehallerne%2C%20Copenhagen%2C%20Denmark",
          "notes": "~9 min pėsčiomis nuo Rundetårn. Geriausia miesto maisto turgavietė – paragaukite tradicinio smørrebrød prie 'Hallernes Smørrebrød' prekystalio. Penktadienį atvira iki 19:00. Po turgaus vyksime įsikurti į apartamentus Sydhavnenyje – metro su persėdimu prie Nørreport, kelionė apie 25 min."
        },
        {
          "name": "Apartamentai su kanalo vaizdu – įsiregistravimas (Sydhavnen)",
          "lat": 55.656,
          "lon": 12.5475,
          "arrive": "19:15",
          "depart": "19:45",
          "maps_query": "Kenny Drews Vej 37, 2450 København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kenny%20Drews%20Vej%2037%2C%202450%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Naujas apartamentas su kanalo vaizdu Sydhavnen rajone (Kenny Drews Vej 37, 2 a., 9 būst., 2450 Kopenhaga) – visa nuoma trims naktims 780 €. Automobilio šioje kelionėje nenuomojame – visur keliausime pėsčiomis arba viešuoju transportu. Vakarienei netoliese (10–15 min keliaujant viešuoju transportu ar dviračiu) keletas tradicinio danų maisto vietų, tinkamų šiam ar kitiems kelionės vakarams: 'Bodega' (Vesterbrogade 72) – klasikinė danų bodega su frikadelėmis ir silke; 'Café Dyrehaven' (Sønder Boulevard 72) – vietinių mėgstama smørrebrød vieta; 'Kødbyens Fiskebar' (Flæsketorvet 100) – žuvies ir jūros gėrybių restoranas senajame skerdyklų kvartale; 'Bistro Bohème' (Flæsketorvet 57) – jaukus bistro tame pačiame kvartale; 'Halvandet' (Islands Brygge) – restoranas prie vandens su danų klasika. Darbo laiką ir rezervacijos reikalingumą verta pasitikrinti iš anksto."
        }
      ],
      "driving_minutes": 90,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 2,
      "title": "2 diena (2026-10-24, šeštadienis): Karališkoji Kopenhaga ir menas",
      "stops": [
        {
          "name": "Christiania",
          "lat": 55.6736,
          "lon": 12.5983,
          "arrive": "09:20",
          "depart": "10:00",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.673600%2C12.598300",
          "notes": "Iš apartamentų (Sydhavnen) iki Christianijos ~30 min kelione metro (M4 iki centro, persėdimas į M1/M2 iki Christianshavn) ir trumpu pėsčiomis. Savivaldi alternatyvi bendruomenė su ryškiu gatvės menu. Lankykite dieną, Pusher Street zonoje nuotraukų nedarykite."
        },
        {
          "name": "Rosenborgo pilis",
          "lat": 55.6857,
          "lon": 12.5775,
          "arrive": "10:30",
          "depart": "11:40",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.685700%2C12.577500",
          "notes": "Nuo Christianijos iki pilies maloniausia nueiti pėsčiomis per senamiestį (~30 min) arba važiuoti autobusu. Karališkos regalijos ir senas pilies sodas. Bilietas ~140 DKK, žiemos laikotarpiu atvira apie 10:00–16:00 – darbo laiką verta pasitikrinti prieš kelionę."
        },
        {
          "name": "Amalienborgas",
          "lat": 55.684,
          "lon": 12.5934,
          "arrive": "12:05",
          "depart": "12:40",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.684000%2C12.593400",
          "notes": "Nuo Rosenborgo iki Amalienborgo ~15 min pėsčiomis. Karališkoji rezidencija – sargybos keitimas vyksta apie 12:00. Muziejaus bilietas 125 DKK, šeštadienį atvira 10:00–16:00."
        },
        {
          "name": "Restaurant Schønnemann",
          "lat": 55.6799,
          "lon": 12.5759,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.679900%2C12.575900",
          "notes": "Nuo Amalienborgo ~15 min pėsčiomis. Vienas seniausių ir labiausiai vertinamų smørrebrød restoranų mieste – tikras klasikinis danų pietų patiekalas."
        },
        {
          "name": "SMK – Danijos nacionalinė dailės galerija",
          "lat": 55.6866,
          "lon": 12.5805,
          "arrive": "14:20",
          "depart": "16:00",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.686600%2C12.580500",
          "notes": "Nuo restorano ~10 min pėsčiomis. Didelė dailės kolekcija nuo senųjų meistrų iki modernaus meno – gera vidaus alternatyva, jei lyja. Bilietas 140 DKK, šeštadienį atvira 10:00–18:00."
        },
        {
          "name": "Pasiplaukiojimas kanalais (Canal Tours Copenhagen, Nyhavn prieplauka)",
          "lat": 55.6799,
          "lon": 12.59,
          "arrive": "16:20",
          "depart": "17:20",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.679900%2C12.590000",
          "notes": "Nuo SMK iki Nyhavno prieplaukos ~12 min pėsčiomis. Valandos trukmės pasiplaukiojimas kanalais ir uostu – pamatysite Christianiją, Operos rūmus ir senamiesčio kanalus iš vandens, puikiu laiku saulėlydžiui (apie 17:15). Bilietas suaugusiam apie 100–130 DKK (~13–17 €); spalio pabaigoje reisų gali būti rečiau – tvarkaraštį verta pasitikrinti prieplaukoje ar internetu iš anksto."
        },
        {
          "name": "Reffen",
          "lat": 55.6963,
          "lon": 12.6126,
          "arrive": "17:50",
          "depart": "19:10",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.696300%2C12.612600",
          "notes": "Iš Nyhavno prieplaukos po pasiplaukiojimo patogiausia plaukti Havnebusu (viešojo vandens transporto linija, galioja tas pats bilietas kaip autobusui ar metro) tiesiai iki Reffen prieplaukos – apie 20–25 min kelionė. Didžiausias gatvės maisto parkas prie vandens, patiekalai nuo ~70 DKK. Vieta atvira, vakarais vėsu – apsirenkite šiltai."
        }
      ],
      "driving_minutes": 140,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 3,
      "title": "3 diena (2026-10-25, sekmadienis): Senamiestis, Tivoli ir Deep Purple koncertas",
      "stops": [
        {
          "name": "Christiansborgo pilis",
          "lat": 55.6761,
          "lon": 12.5789,
          "arrive": "10:00",
          "depart": "11:30",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.676100%2C12.578900",
          "notes": "Iš apartamentų (Sydhavnen) iki senamiesčio ~30 min kelione metro (M4 iki centro) ir pėsčiomis. Parlamento rūmai su karališkomis priėmimo salėmis ir senovinėmis griuvėsiomis požemiuose. Bilietas 215 DKK (internetu) / 225 DKK vietoje, atvira 10:00–17:00."
        },
        {
          "name": "Ny Carlsberg Glyptotek",
          "lat": 55.6744,
          "lon": 12.5774,
          "arrive": "11:45",
          "depart": "12:50",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.674400%2C12.577400",
          "notes": "Čia pat, ~3 min pėsčiomis nuo Christiansborgo. Antikos ir impresionizmo kolekcija aplink palmėmis apsodintą žiemos sodą – puiki vidaus alternatyva lietingai dienai. Bilietas 125 DKK, sekmadienį atvira 10:00–17:00."
        },
        {
          "name": "Café Glyptoteket",
          "lat": 55.6744,
          "lon": 12.5774,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.674400%2C12.577400",
          "notes": "Pietūs tiesiog muziejaus žiemos sode tarp palmių – rami ir netikėta vieta pietums."
        },
        {
          "name": "Tivoli",
          "lat": 55.6736,
          "lon": 12.5681,
          "arrive": "14:15",
          "depart": "16:00",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.673600%2C12.568100",
          "notes": "~8 min pėsčiomis nuo muziejaus. Senas pramogų parkas, spalio pabaigoje papuoštas tūkstančiais Helovino moliūgų. Bilietas 200 DKK, vartai atviri nuo 11:00."
        },
        {
          "name": "Field's prekybos centras (vakarienė)",
          "lat": 55.6286,
          "lon": 12.5713,
          "arrive": "16:30",
          "depart": "17:30",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.628600%2C12.571300",
          "notes": "Nuo Tivoli iki Field's patogiausia M1 metro linija (Rådhuspladsen ar Nørreport → Ørestad stotelė), kelionė ~20 min su trumpu pėsčiomis iki stotelės. Greita vakarienė prekybos centro maisto prekystaliuose prieš koncertą – patogu, nes čia pat Ørestado metro stotis, viena stotelė iki Royal Arena."
        },
        {
          "name": "Royal Arena – Deep Purple koncertas",
          "lat": 55.6256,
          "lon": 12.5726,
          "arrive": "17:45",
          "depart": "22:30",
          "maps_query": "",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=55.625600%2C12.572600",
          "notes": "Deep Purple koncertas – durys atsidaro apie 18:00, tikslų laiką patikrinkite artėjant renginiui. Prie Ørestado stoties šį vakarą tikėtinos minios prieš ir po koncerto, skirkite laiko eilėms. Naktį į sekmadienį laikrodžiai pasukami į žiemos laiką – patikrinkite, ar telefonas atsinaujino automatiškai."
        }
      ],
      "driving_minutes": 70,
      "overnight_city": "Kopenhaga"
    },
    {
      "number": 4,
      "title": "4 diena (2026-10-26, pirmadienis): Frederiksberg parkas ir skrydis namo",
      "stops": [
        {
          "name": "Frederiksberg Have (parkas)",
          "lat": 55.6775,
          "lon": 12.5236,
          "arrive": "10:00",
          "depart": "11:15",
          "maps_query": "Frederiksberg Have, Copenhagen, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Frederiksberg%20Have%2C%20Copenhagen%2C%20Denmark",
          "notes": "Iš apartamentų (Sydhavnen) iki parko ~25 min kelione autobusu/metro (tiksliausią jungtį patikrinkite Rejseplanen appe). Nemokamas, visada atviras parkas su kanalais, tiltukais ir gulbėmis – rami vieta paskutiniam rytiniam pasivaikščiojimui prieš kelionę į oro uostą (Nationalmuseet šią savaitės dieną uždarytas, nes pirmadienis – daugumos Kopenhagos muziejų poilsio diena). Automobilio šioje kelionėje nenuomojame – grįžkite į apartamentus tuo pačiu viešuoju transportu. Jei liko laiko, pro šalį – Frederiksberg Allé su kavinėmis."
        },
        {
          "name": "Apartamentai su kanalo vaizdu – atsiskaitymas (Sydhavnen)",
          "lat": 55.656,
          "lon": 12.5475,
          "arrive": "11:40",
          "depart": "12:00",
          "maps_query": "Kenny Drews Vej 37, 2450 København, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kenny%20Drews%20Vej%2037%2C%202450%20K%C3%B8benhavn%2C%20Denmark",
          "notes": "Apartamento atsiskaitymas ir bagažo pasiėmimas (Kenny Drews Vej 37, 2 a., 9 būst., Sydhavnen, 2450 Kopenhaga). Iš Sydhavnen iki oro uosto viešuoju transportu (traukinys/metro per centrą) užtrunka apie 40 min – ilgiau nei iš centro, tad išvykite ne vėliau kaip 12:00."
        },
        {
          "name": "Kopenhagos oro uostas (CPH) – registracija ir sauga",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "12:40",
          "depart": "13:00",
          "maps_query": "Copenhagen Airport, Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%2C%20Kastrup%2C%20Denmark",
          "notes": "Praeikite registraciją ir saugumo patikrą su atsargos laiku prieš 15:15 skrydį."
        },
        {
          "name": "Pietūs oro uosto terminale",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Copenhagen Airport, Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%2C%20Kastrup%2C%20Denmark",
          "notes": "Paskutiniai pietūs Danijoje terminalo kavinėse po saugumo patikros."
        },
        {
          "name": "Išvykimo vartai – skrydis CPH→KUN",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "14:00",
          "depart": "15:15",
          "maps_query": "Copenhagen Airport, Kastrup, Denmark",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Copenhagen%20Airport%2C%20Kastrup%2C%20Denmark",
          "notes": "Laukimas prie išvykimo vartų, skrydis į Kauną išvyksta 15:15, atvykimas 17:45 vietos laiku."
        }
      ],
      "driving_minutes": 90,
      "overnight_city": "Kaunas"
    }
  ]
}
```

**Weather for the trip dates:**

```json
{
  "generated_on": "2026-10-20",
  "days": [
    {
      "day": 1,
      "date": "2026-10-23",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 7.8,
      "temp_max_c": 11.5,
      "precip_chance_pct": 53,
      "precip_mm": 1.1,
      "wind_max_kmh": 19.1
    },
    {
      "day": 2,
      "date": "2026-10-24",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 9.6,
      "temp_max_c": 11.5,
      "precip_chance_pct": 55,
      "precip_mm": 8.1,
      "wind_max_kmh": 39.5
    },
    {
      "day": 3,
      "date": "2026-10-25",
      "place": "Kopenhaga",
      "source": "forecast",
      "summary": "Lietus",
      "temp_min_c": 9.4,
      "temp_max_c": 10.6,
      "precip_chance_pct": 69,
      "precip_mm": 12.2,
      "wind_max_kmh": 48.4
    },
    {
      "day": 4,
      "date": "2026-10-26",
      "place": "Kaunas",
      "source": "forecast",
      "summary": "Dulksna",
      "temp_min_c": 9.0,
      "temp_max_c": 10.6,
      "precip_chance_pct": 20,
      "precip_mm": 2.8,
      "wind_max_kmh": 27.3
    }
  ]
}
```

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "days": [
    {
      "day": 1,
      "needed": true,
      "title": "Christianshavn dengtose vietose: bažnyčios ir meno salė vietoj bokšto ir Nyhavno",
      "weather_sensitive": "Vor Frelsers Kirke bokštas (sraigtiniai laiptai lauke) uždaromas vėjuotu ar lietingu oru, o pasivaikščiojimas Nyhavno krantinėmis tampa nemalonus lyjant ir pučiant vėjui.",
      "tip": "Bokšto bilieto iš anksto nepirkite – jis parduodamas tik vietoje tą dieną, nes priklauso nuo oro; jei uždarytas, apsiribokite nemokama Vor Frelsers Kirke bažnyčios lanka 11:00–15:30.",
      "stops": [
        {
          "name": "Kopenhagos oro uostas (CPH)",
          "lat": 55.618,
          "lon": 12.6476,
          "arrive": "09:40",
          "depart": "10:10",
          "maps_query": "Copenhagen Airport, Kastrup, Denmark",
          "notes": "Atvykimas iš Kauno, kaip ir pagrindiniame plane. M2 metro iki Christianshavn stotelės, ~17 min."
        },
        {
          "name": "Christians Kirke",
          "lat": 55.6706,
          "lon": 12.5906,
          "arrive": "10:35",
          "depart": "11:20",
          "maps_query": "Christians Kirke, Strandgade 1, Copenhagen, Denmark",
          "notes": "Rokoko stiliaus bažnyčia su trijų aukštų galerijomis ir kripta – jauki vidaus alternatyva lietingam rytui. Dirba antradienį–sekmadienį 9:00–16:00 (penktadienį atvira)."
        },
        {
          "name": "Vor Frelsers Kirke (tik bažnyčios vidus)",
          "lat": 55.6725,
          "lon": 12.5939,
          "arrive": "11:30",
          "depart": "12:45",
          "maps_query": "Vor Frelsers Kirke, Copenhagen, Denmark",
          "notes": "Blogu oru bokštas uždarytas – apžiūrėkite tik nemokamą bažnyčios vidų (atvira 11:00–15:30), skirkite daugiau laiko interjerui ir altoriui. ~5 min pėsčiomis nuo Christians Kirke."
        },
        {
          "name": "Café Wilder",
          "lat": 55.6719,
          "lon": 12.592,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Café Wilder, Copenhagen, Denmark",
          "notes": "Pietūs tas pats jaukus bistro kaip pagrindiniame plane, visiškai po stogu."
        },
        {
          "name": "Kunsthal Charlottenborg",
          "lat": 55.6796,
          "lon": 12.5841,
          "arrive": "14:15",
          "depart": "15:30",
          "maps_query": "Kunsthal Charlottenborg, Copenhagen, Denmark",
          "notes": "Vietoj pasivaikščiojimo Nyhavno krantinėmis – šiuolaikinio meno parodos tiesiog prie Nyhavno, tame pačiame rūmų komplekse. Penktadienį atvira 11:00–19:00."
        },
        {
          "name": "Rundetårn (Apvalusis bokštas)",
          "lat": 55.6808,
          "lon": 12.5775,
          "arrive": "15:45",
          "depart": "16:45",
          "maps_query": "Rundetårn, Copenhagen, Denmark",
          "notes": "Lieka plane – kelias į viršų eina dengta sraigtine rampa, tad tinka ir blogam orui; viršuje trumpiau pasilikite, jei pučia stiprus vėjas."
        },
        {
          "name": "Torvehallerne maisto turgus",
          "lat": 55.6838,
          "lon": 12.5683,
          "arrive": "17:00",
          "depart": "18:45",
          "maps_query": "Torvehallerne, Copenhagen, Denmark",
          "notes": "Dengta turgavietė, kaip ir pagrindiniame plane – idealu pabėgti nuo lietaus prieš grįžtant į apartamentus."
        },
        {
          "name": "Apartamentai su kanalo vaizdu – įsiregistravimas (Sydhavnen)",
          "lat": 55.656,
          "lon": 12.5475,
          "arrive": "19:15",
          "depart": "19:45",
          "maps_query": "Kenny Drews Vej 37, 2450 København, Denmark",
          "notes": "Tas pats įsiregistravimas kaip pagrindiniame plane."
        }
      ]
    },
    {
      "day": 2,
      "needed": true,
      "title": "Muziejų diena vietoj kanalų plaukimo ir lauko turgaus",
      "weather_sensitive": "Stiprus vėjas (prognozuojama iki ~40 km/h) ir lietus dažnai stabdo kanalų pasiplaukiojimus, o Reffen yra atviras lauko maisto turgus – abu tampa nemalonūs ar neįmanomi blogu oru.",
      "tip": "Kanalų pasiplaukiojimo bendrovės (pvz. Canal Tours) audringu oru reisus dažnai atšaukia ir grąžina pinigus – prieš važiuojant į prieplauką patikrinkite internetu, ar reisas vyksta.",
      "stops": [
        {
          "name": "Christiania",
          "lat": 55.6736,
          "lon": 12.5983,
          "arrive": "09:20",
          "depart": "10:00",
          "maps_query": "Christiania, Copenhagen, Denmark",
          "notes": "Blogu oru trumpinkite laiką lauke – užsukite į dengtus galerijų pastatus ir Nemoland paviljoną, Pusher Street zonoje nuotraukų nedarykite."
        },
        {
          "name": "Rosenborgo pilis",
          "lat": 55.6857,
          "lon": 12.5775,
          "arrive": "10:30",
          "depart": "11:40",
          "maps_query": "Rosenborg Slot, Copenhagen, Denmark",
          "notes": "Nepakitę – visiškai vidaus objektas, karališkos regalijos ir pilies menės."
        },
        {
          "name": "Amalienborgas",
          "lat": 55.684,
          "lon": 12.5934,
          "arrive": "12:05",
          "depart": "12:40",
          "maps_query": "Amalienborg, Copenhagen, Denmark",
          "notes": "Pats muziejus vidinis – sargybos keitimą stebėkite trumpai po skėčiu, ilgiau pasilikite muziejaus salėse."
        },
        {
          "name": "Restaurant Schønnemann",
          "lat": 55.6799,
          "lon": 12.5759,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Restaurant Schønnemann, Copenhagen, Denmark",
          "notes": "Nepakitę – smørrebrød pietūs patalpoje."
        },
        {
          "name": "SMK – Danijos nacionalinė dailės galerija",
          "lat": 55.6866,
          "lon": 12.5805,
          "arrive": "14:20",
          "depart": "15:50",
          "maps_query": "Statens Museum for Kunst (SMK), Copenhagen, Denmark",
          "notes": "Vizitas sutrumpintas 10 min, kad spėtumėte į Nikolaj Kunsthal prieš uždarymą."
        },
        {
          "name": "Nikolaj Kunsthal",
          "lat": 55.6775,
          "lon": 12.5825,
          "arrive": "16:10",
          "depart": "16:55",
          "maps_query": "Nikolaj Kunsthal, Copenhagen, Denmark",
          "notes": "Vietoj kanalų pasiplaukiojimo – šiuolaikinio meno salė senoje bažnyčioje prie Nyhavno. Šeštadienį dirba iki 17:00, tad neužtrukite."
        },
        {
          "name": "Reffen",
          "lat": 55.6963,
          "lon": 12.6126,
          "arrive": "17:25",
          "depart": "18:50",
          "maps_query": "Reffen, Copenhagen, Denmark",
          "notes": "Iki Reffen plaukite Havnebusu nuo Nyhavno prieplaukos (~20–25 min, tas pats bilietas kaip metro/autobusui). Rinkitės dengtas sales ir konteinerių vidų, ne atviro oro staliukus; apsirenkite šiltai ir vėjui atspariai."
        }
      ]
    },
    {
      "day": 3,
      "needed": true,
      "title": "Meno diena vietoj Tivoli parko",
      "weather_sensitive": "Tivoli yra lauko pramogų parkas su atviromis eilėmis ir atrakcionais – stipriame lietuje bei vėjyje (prognozuojama iki ~48 km/h) dalis atrakcionų nedirba, o vaikščioti neperlyjus beveik neįmanoma.",
      "tip": "Thorvaldsens muziejus sekmadienį dirba 10:00–17:00 ir yra vos 2–3 min pėsčiomis nuo Christiansborgo/Glyptoteko – patogu įterpti be papildomo kelio.",
      "stops": [
        {
          "name": "Christiansborgo pilis",
          "lat": 55.6761,
          "lon": 12.5789,
          "arrive": "10:00",
          "depart": "11:30",
          "maps_query": "Christiansborg Slot, Copenhagen, Denmark",
          "notes": "Nepakitę – vidaus objektas, parlamento rūmai ir požeminės griuvėsios."
        },
        {
          "name": "Ny Carlsberg Glyptotek",
          "lat": 55.6744,
          "lon": 12.5774,
          "arrive": "11:45",
          "depart": "12:50",
          "maps_query": "Ny Carlsberg Glyptotek, Copenhagen, Denmark",
          "notes": "Nepakitę – antikos ir impresionizmo kolekcija po stogu."
        },
        {
          "name": "Café Glyptoteket",
          "lat": 55.6744,
          "lon": 12.5774,
          "arrive": "13:00",
          "depart": "14:00",
          "maps_query": "Café Glyptoteket, Ny Carlsberg Glyptotek, Copenhagen, Denmark",
          "notes": "Nepakitę – pietūs muziejaus žiemos sode."
        },
        {
          "name": "Thorvaldsens muziejus",
          "lat": 55.6751,
          "lon": 12.5776,
          "arrive": "14:15",
          "depart": "15:30",
          "maps_query": "Thorvaldsens Museum, Copenhagen, Denmark",
          "notes": "Vietoj Tivoli – skulptūrų muziejus čia pat prie Christiansborgo, visiškai po stogu. Sekmadienį dirba 10:00–17:00."
        },
        {
          "name": "Field's prekybos centras (vakarienė)",
          "lat": 55.6286,
          "lon": 12.5713,
          "arrive": "16:15",
          "depart": "17:15",
          "maps_query": "Field's, Copenhagen, Denmark",
          "notes": "Nepakitę – dengtas prekybos centras, greita vakarienė prieš koncertą, metro iki Ørestado."
        },
        {
          "name": "Royal Arena – Deep Purple koncertas",
          "lat": 55.6256,
          "lon": 12.5726,
          "arrive": "17:45",
          "depart": "22:30",
          "maps_query": "Royal Arena, Copenhagen, Denmark",
          "notes": "Nepakitę – koncertas vyksta patalpoje nepriklausomai nuo oro. Prisiminkite – naktį laikrodžiai pasukami į žiemos laiką."
        }
      ]
    },
    {
      "day": 4,
      "needed": false
    }
  ]
}
```

</details>

