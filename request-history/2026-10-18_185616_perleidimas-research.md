# Perleidimas nuo žingsnio „Tyrimas“ — 2026-10-18 18:56:16 UTC

- **Kelionė:** `d85b1e13fecc`
- **Pradžia / pabaiga:** 2026-10-18 18:56:16 → 19:00:21 (4 min.)
- **Agentų rinkinys:** Base
- **Rezultatas:** ❌ Nepavyko
- **Klaida:** cannot access local variable 'picks' where it is not associated with a value

## Eiga

- `18:56:16` Perleidžiama nuo žingsnio: research...
- `18:56:16` Tyrimas (kelionės objektai, keliai, sezoniškumas)...
- `18:58:36` Orų/sezono patikra...
- `18:59:13` Nakvynės paieška...
- `19:00:21` Nepavyko: cannot access local variable 'picks' where it is not associated with a value

## Agentų kvietimai (3)

### 1. Tyrimas — 18:58:36 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 140.1 s
- **Sistemos promptas:** `prompts/research.md`

<details><summary><b>Užklausa</b></summary>

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

</details>

<details><summary><b>Atsakymas</b></summary>

# Research Summary — Copenhagen, 2026-10-23 to 2026-10-26 (4 travelers, no rental car, priorities: culture + food)

## Candidate stops

| Stop | Why recommended | Hours / closed days | Adult price | Source |
|---|---|---|---|---|
| **Nyhavn** canal front | Iconic harbor, photos best early morning or after dark before crowds; free to walk | Always open (outdoor) | Free | [Traverse-blog](https://www.traverse-blog.com/copenhagen-denmark-itinerary/), [wheregoesrose](https://www.wheregoesrose.com/freetown-christiania-travel-guide-tips/) (2026) |
| **Christianshavn / canals** (near booked apartment) | Picturesque canal district, walkable from Nyhavn, local-feel | Always open (outdoor) | Free | general |
| **Rundetårn (Round Tower)** | Oldest functioning observatory in Europe, spiral ramp, views over old town | Oct–Mar: daily 10:00–18:00 | 60 DKK, free <18 | [copenhagentourism.org](https://www.copenhagentourism.org/round-tower-rundetaarn-copenhagen/) |
| **Vor Frelsers Kirke (Church of Our Saviour)** tower | Famous spiral external staircase, views of Christianshavn | Tower daily 09:00–20:00 (closes in rain/snow/strong wind — real risk in Oct); church 11:00–15:30 | Tower: 70 DKK adult / 20 DKK child; church free | [vorfrelserskirke.dk](https://www.vorfrelsersk irke.dk/taarn/tower/booking), [copenhagencard.com](https://copenhagencard.com/attractions/church-of-our-saviour) (2026) |
| **Rosenborg Castle** | Crown jewels, royal history | Winter hours (Oct–Mar) likely 10:00–16:00, **closed Mondays** off-season | 140 DKK, free <18 | [tourismattractions.net / parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/rosenborg/) (2026) — **verify exact Oct 2026 hours before trip, source conflicts on winter Monday closure** |
| **Christiansborg Palace** (Reception Rooms/Ruins/Kitchen) | Seat of parliament, royal reception rooms | Daily 10:00–17:00 (through Nov 1); Tower closed Mondays | 215 DKK online / 225 at door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/christiansborg-palace/plan-your-visit/opening-hours/) (2026) |
| **Amalienborg Museum** | Royal residence, changing of the guard (~noon) | Mon–Fri 10:00–15:00, Sat–Sun 10:00–16:00 (Nov 1 on, closed Mondays) | 125 DKK online/135 door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/amalienborg-museum/plan-your-visit/opening-hours/) (2026) |
| **National Museum (Nationalmuseet)** | Denmark's largest museum, Viking/prehistory collections | Daily 10:00–17:00 (Apr–Oct); price info **conflicting** — official ticket page lists 150 DKK adult, other sources say permanent collection free | 150 DKK adult (verify at door — may be free) | [nationalmuseet.dk/en/tickets](https://nationalmuseet.dk/en/tickets), [copenhagentourism.org](https://www.copenhagentourism.org/national-museum-denmark-copenhagen/) |
| **SMK – National Gallery of Denmark** | Major art museum | Closed **Mon**; Tue 10–18, Wed 10–20, Thu–Sun 10–18 | 140 DKK adult, free <18 | [parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/smk/) (2026) |
| **Ny Carlsberg Glyptotek** | Antiquities + Impressionist art, winter garden | Closed **Mon**; Tue–Sun 10–17 (Thu to 21) | 125 DKK, **free every Tuesday** | search aggregate (2026) |
| **Designmuseum Danmark** | Danish design heritage | Closed **Mon**; Tue–Sun 10–18 (Thu to 20) | 130 DKK, free <18 | aggregate (2026) |
| **Freetown Christiania** | Alternative self-governing community, street art | Daytime only — avoid after dark and avoid photos on Pusher Street | Free | [copenhagentourism.org](https://www.copenhagentourism.org/freetown-christiania-copenhagen/) |
| **Tivoli Gardens** | Historic amusement park, Halloween theming Oct 2–Nov 1 2026 (20,000 pumpkins) | Gates 11:00, closes 23:00 (extended Fri/Sat) | 200 DKK adult, 100 DKK child 3–7 | [copenhagentourism.org](https://www.copenhagentourism.org/tivoli-gardens-copenhagen/) (2026) |
| **Torvehallerne food market** | Best food hall, Hallernes Smørrebrød stall recommended for traditional smørrebrød | Mon–Fri 10–19, Sat–Sun 10–18 | Free entry (pay per item) | [scandinaviastandard.com](https://www.scandinaviastandard.com/the-ultimate-guide-to-the-best-food-halls-in-copenhagen/) |
| **Reffen street food park** | Affordable (from 70 DKK), harborside, casual | **Confirmed open on trip dates** — Autumn/Halloween season runs Oct 1–Nov 2; stalls ~11:30–20:30 | Free entry | [reffen.dk](https://reffen.dk/en/info-2025/), search re: season dates |
| **Stromma canal boat tour** | Classic way to see the harbor/canals | Oct: Mon–Sat 10:00–16:50, live-guided only (no recorded commentary off-season) | Not confirmed — check stromma.com | [copenhagencard.com](https://copenhagencard.com/attractions/canal-tours-copenhagen) |
| **The Little Mermaid statue** | Iconic photo stop, but widely called overrated/small/crowded on forums; go early morning | Outdoor, always visible | Free | reddit/forum aggregate — "go before 9am to beat tour buses" |

## Events on trip dates (2026-10-23 to 10-26)

- **Deep Purple concert** — Royal Arena, Hannemanns Allé 18, 2300 København S — **Sunday 2026-10-25, doors/support act timing suggests show starts ~18:00–20:00** (one source lists 18:00). Confirm exact doors/start time closer to date. [livenation.dk](https://www.livenation.dk/en/event/deep-purple-k%C3%B8benhavn-s-tickets-edp1635370), [songkick](https://www.songkick.com/concerts/42897389-deep-purple-at-royal-arena)
- **Daylight Saving Time ends** — Sunday 2026-10-25 at 03:00, clocks go back 1 hour. This affects the Deep Purple concert evening and the Oct 26 flight-day schedule — build in the extra hour. [timeanddate.com](https://www.timeanddate.com/holidays/denmark/2026)
- **HRH Crown Prince Christian's birthday flag day** — 2026-10-15 (before trip, no impact).
- **Kulturnatten (Culture Night)** — 2026-10-09 (before trip, no impact).
- No Danish statutory public holidays fall within Oct 23–26, 2026 — museums/shops operate normal hours except their usual weekly closures (mostly Mondays).
- Tivoli's Halloween season (pumpkins, decorations) runs through the full trip window.

## Road/logistics warnings

Not applicable — no car rental for this trip; travel is entirely on foot and public transport within Copenhagen. No bekelė/4x4 road risk applies.

## Public transport & logistics notes

- 2026 ticketing: **Rejsebillet app** is replacing the old DOT Billetter app; physical Rejsekort is being phased out. Buy single tickets in-app or at station machines, or get **City Pass Small** (zones 1–4, unlimited 24h) for heavy sightseeing days. [denmarkguide.dk](https://denmarkguide.dk/en/oplev-danmark/transport-og-mobilitet/offentlig-transport/rejsekort-rejsebillet-dsb-app/)
- **Copenhagen Card**: worth it only if doing 3+ paid attractions/day; for a culture-heavy 3-night trip with Rosenborg + Christiansborg + SMK/Glyptotek + Amalienborg it likely pays off — do the math against your actual chosen stops before buying. [routesnorth.com](https://www.routesnorth.com/denmark/copenhagen/copenhagen-card-worth-buying/)
- Metro runs from CPH airport directly to the city center (M2 line) — relevant for the 09:40 arrival and 15:15 departure.

## Seasonal / weather notes

- October in Copenhagen: avg **13°C day / 7°C night**, ~14–15 rainy days/month, ~50–68mm total rainfall — pack rain gear; plan a roughly even mix of indoor (museums) and outdoor stops, with flexible ordering to shift outdoor stops (Nyhavn, Christiania, canal walk) to drier windows and indoor museums to rain windows. [wanderlog](https://wanderlog.com/weather/9643/10/copenhagen-weather-in-october), [weather-atlas](https://www.weather-atlas.com/en/denmark/copenhagen-weather-october)
- Daylight shrinks fast late October: sunset ~18:04 on Oct 18 narrowing toward ~16:30s after the Oct 25 clock change — plan outdoor sightseeing for mid-day/early afternoon, reserve dark hours for Nyhavn's lit-up evening look, dinners, and the Oct 25 concert. [tutiempo.net](https://en.tutiempo.net/daylight-hours/copenhagen.html)
- Vor Frelsers Kirke tower closes on wind/rain days without notice — do not schedule it as the only activity in a time slot; have a museum backup.

## What's overrated/skippable (forum consensus)

- **Little Mermaid statue**: widely called underwhelming/tiny, crowded with tour buses even early; visit briefly and early morning only, don't build a half-day around it.
- Pusher Street inside Christiania: skip photography there specifically (camera-breaking incidents reported); rest of Christiania fine in daylight.

## Practical information (Lithuanian/EU citizens)

- **Documents**: Valid passport or national ID card sufficient — Denmark is Schengen, no visa needed for EU citizens, stays up to 90 days. [visitcopenhagen.com](https://www.visitcopenhagen.com/copenhagen/planning/basic-need-know-information)
- **Currency**: Danish Krone (DKK), **not euro** — Denmark is EU but outside the eurozone. Cards are very widely accepted everywhere, including small purchases; carrying some cash is still wise for Christiania (ATMs scarce there) and some small/independent food stalls.
- **Tipping**: Not expected — service is included in restaurant/hotel/taxi bills. Round up or ~10% for exceptional service only.
- **Health**: Bring EHIC/European Health Insurance Card for free/reduced emergency treatment as an EU citizen.
- **Emergency number**: **112** (police/fire/ambulance, free call). Non-emergency medical advice line: **1813** (English-speaking staff).
- **Public transport tickets**: Rejsebillet app (replacing DOT app in 2026) or City Pass; see above.
- **Customs/etiquette**: Danes value punctuality, queueing, and personal space; "hygge" culture — low-key, unpretentious; bike lanes are serious — never walk in the cykelsti (marked bike lane), tourists get yelled at/hit.
- **Safety**: Copenhagen is generally very safe; normal urban precautions apply (watch belongings in tourist-dense Nyhavn/Strøget). Christiania safe in daylight, avoid after dark, follow posted community rules (no running, no photos on Pusher Street).

## Unconfirmed — verify before finalizing itinerary

- Exact Rosenborg Castle Monday closure status for Oct 2026 (sources conflict on winter weekday hours).
- National Museum adult ticket price — official site states 150 DKK but several tourism sites claim permanent collection is free; confirm at nationalmuseet.dk/en/tickets closer to the date.
- Deep Purple exact doors/start time at Royal Arena (confirm via livenation.dk nearer the date).
- Stromma canal tour exact departure times/prices for Oct 23–26, 2026 (only general October hours found).

</details>

### 2. Oras/sezonas — 18:59:12 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 36.2 s
- **Sistemos promptas:** `prompts/weather.md`

<details><summary><b>Užklausa</b></summary>

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

Use Bash to check typical conditions: `python3 tools/open_meteo.py --lat .. --lon .. --month <1-12>`. Use WebSearch for anything not covered by that (e.g. seasonal road closures).

</details>

<details><summary><b>Atsakymas</b></summary>

## Weather & Season Summary — Kopenhaga, 2026-10-23 → 10-26

**Temperatūra:** ~9–13°C (remiantis daugiamečiu Open-Meteo vidurkiu spalio mėn.)

**Kritulių tikimybė:** vidutinė — istoriškai ~8 iš 28 dienų su >1mm lietaus (≈29% dienų), t.y. verta turėti lietpaltį/skėtį, bet nėra nuolatinio lietaus sezono.

**Sezoniškumas:** Spalis patenka į Kopenhagos **rekomenduojamą (shoulder) sezoną** — ne piko vasaros sezonas, bet laikomas geru laiku lankytis: ruduo, mažesni turistų srautai, žemesnės kainos, ruduo parkuose. **Datos NEIŠKRENTA iš rekomenduojamo sezono**, tik oras jau vėsesnis/drėgnesnis nei vasarą.

**Sezoninis kelių/prieigos aspektas:** Netaikoma kalnų pravažumo prasme (lygumų miestas, be nuomojamo automobilio pagal užklausą). Tačiau svarbu Logistics Validator / Itinerary Planner:
- **2026-10-25 (šeštadienį) Danijoje baigiasi vasaros laikas (DST)** — tai savaitgalis per kelionę, patikrinti ar tai neįtakoja viešojo transporto tvarkaraščių ar koncerto laiko.
- Spalio pabaigoje saulė leidžiasi ~17:15–17:30 vietos laiku (po laiko keitimo dar anksčiau) — **trumpa diena, riboja lauko objektų laiką po pietų**; rekomenduoti didesnę vidaus objektų (muziejai, bažnyčios, Tivoli po patamsio) dalį popietėmis/vakarais.
- Lietaus tikimybė (~29% dienų) reiškia, kad planui verta turėti vidaus alternatyvą (Plan B agentui) bent 1 dienai.

Sources:
- [Copenhagen in October: What to See & Do](https://www.nomadotravel.app/en/guides/copenhagen-in-october)
- [Best Time to Visit Copenhagen: Month by Month (2026)](https://www.copenhagentourism.org/best-time-to-visit-copenhagen/)
- [A Local's Guide to Autumn in Copenhagen](https://danny-cph.com/copenhagen-autumn-visitor-guide/)

</details>

### 3. Nakvynė — 19:00:21 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 68.7 s
- **Sistemos promptas:** `prompts/accommodation.md`

<details><summary><b>Užklausa</b></summary>

**requirements**

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

**research**

# Research Summary — Copenhagen, 2026-10-23 to 2026-10-26 (4 travelers, no rental car, priorities: culture + food)

## Candidate stops

| Stop | Why recommended | Hours / closed days | Adult price | Source |
|---|---|---|---|---|
| **Nyhavn** canal front | Iconic harbor, photos best early morning or after dark before crowds; free to walk | Always open (outdoor) | Free | [Traverse-blog](https://www.traverse-blog.com/copenhagen-denmark-itinerary/), [wheregoesrose](https://www.wheregoesrose.com/freetown-christiania-travel-guide-tips/) (2026) |
| **Christianshavn / canals** (near booked apartment) | Picturesque canal district, walkable from Nyhavn, local-feel | Always open (outdoor) | Free | general |
| **Rundetårn (Round Tower)** | Oldest functioning observatory in Europe, spiral ramp, views over old town | Oct–Mar: daily 10:00–18:00 | 60 DKK, free <18 | [copenhagentourism.org](https://www.copenhagentourism.org/round-tower-rundetaarn-copenhagen/) |
| **Vor Frelsers Kirke (Church of Our Saviour)** tower | Famous spiral external staircase, views of Christianshavn | Tower daily 09:00–20:00 (closes in rain/snow/strong wind — real risk in Oct); church 11:00–15:30 | Tower: 70 DKK adult / 20 DKK child; church free | [vorfrelserskirke.dk](https://www.vorfrelsersk irke.dk/taarn/tower/booking), [copenhagencard.com](https://copenhagencard.com/attractions/church-of-our-saviour) (2026) |
| **Rosenborg Castle** | Crown jewels, royal history | Winter hours (Oct–Mar) likely 10:00–16:00, **closed Mondays** off-season | 140 DKK, free <18 | [tourismattractions.net / parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/rosenborg/) (2026) — **verify exact Oct 2026 hours before trip, source conflicts on winter Monday closure** |
| **Christiansborg Palace** (Reception Rooms/Ruins/Kitchen) | Seat of parliament, royal reception rooms | Daily 10:00–17:00 (through Nov 1); Tower closed Mondays | 215 DKK online / 225 at door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/christiansborg-palace/plan-your-visit/opening-hours/) (2026) |
| **Amalienborg Museum** | Royal residence, changing of the guard (~noon) | Mon–Fri 10:00–15:00, Sat–Sun 10:00–16:00 (Nov 1 on, closed Mondays) | 125 DKK online/135 door, free <18 | [denkongeligesamling.dk](https://denkongeligesamling.dk/en/amalienborg-museum/plan-your-visit/opening-hours/) (2026) |
| **National Museum (Nationalmuseet)** | Denmark's largest museum, Viking/prehistory collections | Daily 10:00–17:00 (Apr–Oct); price info **conflicting** — official ticket page lists 150 DKK adult, other sources say permanent collection free | 150 DKK adult (verify at door — may be free) | [nationalmuseet.dk/en/tickets](https://nationalmuseet.dk/en/tickets), [copenhagentourism.org](https://www.copenhagentourism.org/national-museum-denmark-copenhagen/) |
| **SMK – National Gallery of Denmark** | Major art museum | Closed **Mon**; Tue 10–18, Wed 10–20, Thu–Sun 10–18 | 140 DKK adult, free <18 | [parkmuseerne.dk](https://www.parkmuseerne.dk/en/museer/smk/) (2026) |
| **Ny Carlsberg Glyptotek** | Antiquities + Impressionist art, winter garden | Closed **Mon**; Tue–Sun 10–17 (Thu to 21) | 125 DKK, **free every Tuesday** | search aggregate (2026) |
| **Designmuseum Danmark** | Danish design heritage | Closed **Mon**; Tue–Sun 10–18 (Thu to 20) | 130 DKK, free <18 | aggregate (2026) |
| **Freetown Christiania** | Alternative self-governing community, street art | Daytime only — avoid after dark and avoid photos on Pusher Street | Free | [copenhagentourism.org](https://www.copenhagentourism.org/freetown-christiania-copenhagen/) |
| **Tivoli Gardens** | Historic amusement park, Halloween theming Oct 2–Nov 1 2026 (20,000 pumpkins) | Gates 11:00, closes 23:00 (extended Fri/Sat) | 200 DKK adult, 100 DKK child 3–7 | [copenhagentourism.org](https://www.copenhagentourism.org/tivoli-gardens-copenhagen/) (2026) |
| **Torvehallerne food market** | Best food hall, Hallernes Smørrebrød stall recommended for traditional smørrebrød | Mon–Fri 10–19, Sat–Sun 10–18 | Free entry (pay per item) | [scandinaviastandard.com](https://www.scandinaviastandard.com/the-ultimate-guide-to-the-best-food-halls-in-copenhagen/) |
| **Reffen street food park** | Affordable (from 70 DKK), harborside, casual | **Confirmed open on trip dates** — Autumn/Halloween season runs Oct 1–Nov 2; stalls ~11:30–20:30 | Free entry | [reffen.dk](https://reffen.dk/en/info-2025/), search re: season dates |
| **Stromma canal boat tour** | Classic way to see the harbor/canals | Oct: Mon–Sat 10:00–16:50, live-guided only (no recorded commentary off-season) | Not confirmed — check stromma.com | [copenhagencard.com](https://copenhagencard.com/attractions/canal-tours-copenhagen) |
| **The Little Mermaid statue** | Iconic photo stop, but widely called overrated/small/crowded on forums; go early morning | Outdoor, always visible | Free | reddit/forum aggregate — "go before 9am to beat tour buses" |

## Events on trip dates (2026-10-23 to 10-26)

- **Deep Purple concert** — Royal Arena, Hannemanns Allé 18, 2300 København S — **Sunday 2026-10-25, doors/support act timing suggests show starts ~18:00–20:00** (one source lists 18:00). Confirm exact doors/start time closer to date. [livenation.dk](https://www.livenation.dk/en/event/deep-purple-k%C3%B8benhavn-s-tickets-edp1635370), [songkick](https://www.songkick.com/concerts/42897389-deep-purple-at-royal-arena)
- **Daylight Saving Time ends** — Sunday 2026-10-25 at 03:00, clocks go back 1 hour. This affects the Deep Purple concert evening and the Oct 26 flight-day schedule — build in the extra hour. [timeanddate.com](https://www.timeanddate.com/holidays/denmark/2026)
- **HRH Crown Prince Christian's birthday flag day** — 2026-10-15 (before trip, no impact).
- **Kulturnatten (Culture Night)** — 2026-10-09 (before trip, no impact).
- No Danish statutory public holidays fall within Oct 23–26, 2026 — museums/shops operate normal hours except their usual weekly closures (mostly Mondays).
- Tivoli's Halloween season (pumpkins, decorations) runs through the full trip window.

## Road/logistics warnings

Not applicable — no car rental for this trip; travel is entirely on foot and public transport within Copenhagen. No bekelė/4x4 road risk applies.

## Public transport & logistics notes

- 2026 ticketing: **Rejsebillet app** is replacing the old DOT Billetter app; physical Rejsekort is being phased out. Buy single tickets in-app or at station machines, or get **City Pass Small** (zones 1–4, unlimited 24h) for heavy sightseeing days. [denmarkguide.dk](https://denmarkguide.dk/en/oplev-danmark/transport-og-mobilitet/offentlig-transport/rejsekort-rejsebillet-dsb-app/)
- **Copenhagen Card**: worth it only if doing 3+ paid attractions/day; for a culture-heavy 3-night trip with Rosenborg + Christiansborg + SMK/Glyptotek + Amalienborg it likely pays off — do the math against your actual chosen stops before buying. [routesnorth.com](https://www.routesnorth.com/denmark/copenhagen/copenhagen-card-worth-buying/)
- Metro runs from CPH airport directly to the city center (M2 line) — relevant for the 09:40 arrival and 15:15 departure.

## Seasonal / weather notes

- October in Copenhagen: avg **13°C day / 7°C night**, ~14–15 rainy days/month, ~50–68mm total rainfall — pack rain gear; plan a roughly even mix of indoor (museums) and outdoor stops, with flexible ordering to shift outdoor stops (Nyhavn, Christiania, canal walk) to drier windows and indoor museums to rain windows. [wanderlog](https://wanderlog.com/weather/9643/10/copenhagen-weather-in-october), [weather-atlas](https://www.weather-atlas.com/en/denmark/copenhagen-weather-october)
- Daylight shrinks fast late October: sunset ~18:04 on Oct 18 narrowing toward ~16:30s after the Oct 25 clock change — plan outdoor sightseeing for mid-day/early afternoon, reserve dark hours for Nyhavn's lit-up evening look, dinners, and the Oct 25 concert. [tutiempo.net](https://en.tutiempo.net/daylight-hours/copenhagen.html)
- Vor Frelsers Kirke tower closes on wind/rain days without notice — do not schedule it as the only activity in a time slot; have a museum backup.

## What's overrated/skippable (forum consensus)

- **Little Mermaid statue**: widely called underwhelming/tiny, crowded with tour buses even early; visit briefly and early morning only, don't build a half-day around it.
- Pusher Street inside Christiania: skip photography there specifically (camera-breaking incidents reported); rest of Christiania fine in daylight.

## Practical information (Lithuanian/EU citizens)

- **Documents**: Valid passport or national ID card sufficient — Denmark is Schengen, no visa needed for EU citizens, stays up to 90 days. [visitcopenhagen.com](https://www.visitcopenhagen.com/copenhagen/planning/basic-need-know-information)
- **Currency**: Danish Krone (DKK), **not euro** — Denmark is EU but outside the eurozone. Cards are very widely accepted everywhere, including small purchases; carrying some cash is still wise for Christiania (ATMs scarce there) and some small/independent food stalls.
- **Tipping**: Not expected — service is included in restaurant/hotel/taxi bills. Round up or ~10% for exceptional service only.
- **Health**: Bring EHIC/European Health Insurance Card for free/reduced emergency treatment as an EU citizen.
- **Emergency number**: **112** (police/fire/ambulance, free call). Non-emergency medical advice line: **1813** (English-speaking staff).
- **Public transport tickets**: Rejsebillet app (replacing DOT app in 2026) or City Pass; see above.
- **Customs/etiquette**: Danes value punctuality, queueing, and personal space; "hygge" culture — low-key, unpretentious; bike lanes are serious — never walk in the cykelsti (marked bike lane), tourists get yelled at/hit.
- **Safety**: Copenhagen is generally very safe; normal urban precautions apply (watch belongings in tourist-dense Nyhavn/Strøget). Christiania safe in daylight, avoid after dark, follow posted community rules (no running, no photos on Pusher Street).

## Unconfirmed — verify before finalizing itinerary

- Exact Rosenborg Castle Monday closure status for Oct 2026 (sources conflict on winter weekday hours).
- National Museum adult ticket price — official site states 150 DKK but several tourism sites claim permanent collection is free; confirm at nationalmuseet.dk/en/tickets closer to the date.
- Deep Purple exact doors/start time at Royal Arena (confirm via livenation.dk nearer the date).
- Stromma canal tour exact departure times/prices for Oct 23–26, 2026 (only general October hours found).

</details>

<details><summary><b>Atsakymas</b></summary>

## Nakvynė — Kopenhaga (2026-10-23 → 2026-10-26, 3 naktys)

Kelionės užrašuose nakvynė **jau nurodyta kaip pasirinkta** — tai nėra paieška nuo nulio, todėl pagrindinis variantas yra patvirtinti šią vietą, o kiti du pateikti kaip atsarginiai, jei dėl kokių priežasčių tektų keisti.

### 1. ⭐ Sanders Saint-Nice 1-Bdr Apt by the Canals (pasirinkta, rekomenduojama)
- **Vieta:** Christianshavn, prie kanalų — 1416 Kopenhaga. Pėsčiomis ~3 min iki Christianshavn metro stoties, ~15 min pėsčiomis iki Nyhavn ir Strøget, prie pat Vor Frelsers Kirke (bažnyčios bokšto).
- **Kaina:** ~158 USD/naktis (≈ 145 EUR/naktis) pagal TripAdvisor/Expedia duomenis — **tiksli 2026-10-23–26 kaina nepatvirtinta**, kainos svyruoja $126–$336/naktis skirtingose platformose ir sezonuose, patikrinti prieš galutinį rezervavimą.
- **Kodėl tinka:** Vienbutis apartamentas su atskiru miegamuoju, pilnai įrengta virtuvėle, privatus įėjimas, kontaktinis atvykimas (lankstu, jei diena nusitęstų, pvz. po Deep Purple koncerto 10-25 vakare). Christianshavn rajonas idealiai atitinka prioritetus (kultūra — tiesiai prie bažnyčios bokšto ir kanalų, maistas — netoli Torvehallerne/Reffen).
- **Rezervavimas:** [Tripadvisor](https://www.tripadvisor.com/VacationRentalReview-g189541-d18852743-Sanders_Saint_Nice_1_Bdr_Apt_By_the_Canals-Copenhagen_Zealand.html), [Expedia](https://www.expedia.com/Copenhagen-Hotels-Cozy-Apartment-In-Christianshavn.h45157366.Hotel-Information)

### 2. Atsarginis — Christianshavn Canalside Luxury Apartment
- **Vieta:** Christianshavn, prie kanalo, ~1.6 mylios (2,6 km) nuo centrinės stoties.
- **Kaina:** nerasta tiksli kaina šiai paieškai — tikrinti Booking.com tiesiogiai.
- **Kodėl tinka:** 2 miegamieji (daugiau vietos 4 keliautojams nei originalus 1 miegamojo variantas), kanalo vaizdas, tas pats rajonas kaip ir pirmas pasirinkimas — patogu, jei reikėtų greito pakaitalo be lokacijos keitimo.
- **Rezervavimas:** [Booking.com](https://www.booking.com/hotel/dk/christianshavn-canalside-luxury-apartment.html)

### 3. Atsarginis — City Apartment in Copenhagen (1-2 miegamieji, 4 asmenims), netoli Nyhavn
- **Vieta:** tyliame kiemelyje, ~100 m nuo Nyhavn, lengvai pasiekiama pėsčiomis iki daugumos kultūros objektų (Amalienborg, Nationalmuseet, Rundetårn).
- **Kaina:** nerasta tiksli kaina šiai paieškai — tikrinti Expedia/Booking.com.
- **Kodėl tinka:** centriškiausia iš trijų — arčiausiai Nyhavn/Strøget zonos, jei norėtumėte dar mažiau pėsčiomis iki senamiesčio objektų nei Christianshavn variantai.
- **Rezervavimas:** [Expedia](https://www.expedia.com/Copenhagen-Hotels-City-Apartment-In-Copenhagen-With-2-Bedrooms-Sleeps-4.h32948943.Hotel-Information)

**Pastaba:** `accommodation_type`, `max_price_per_night_eur` ir `accommodation_area` lauk(ai) reikalavimuose nebuvo nurodyti atskirai — traveller pats jau pasirinko konkretų apartamentą pastabose, todėl laikau tai esamu sprendimu, ne atviru ieškojimu. Automobilio nėra, tad "free parking" kriterijus netaikomas.

```json
{"picks": [{"city": "Kopenhaga", "name": "Sanders Saint - Nice 1-Bdr Apt by the Canals", "checkin": "2026-10-23", "checkout": "2026-10-26", "price_per_night_eur": 145}]}
```

</details>

