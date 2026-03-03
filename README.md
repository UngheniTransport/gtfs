# GTFS Ungheni (Official Feed)

[RO] Acesta este depozitul oficial de date deschise (Open Data) pentru transportul public din Municipiul Ungheni și rutele raionale/interurbane, gestionat de **Transport Public Ungheni – Eurohome Construct S.R.L.** (via **unghenitransport.md**).

[EN] This is the official open data repository for public transport in Ungheni Municipality and district/interurban routes, maintained by **Transport Public Ungheni – Eurohome Construct S.R.L.** (via **unghenitransport.md**).

---

## 📂 Download Data / Descărcare Date

Pentru dezvoltatori și integratori (Google Maps, Apple Maps, Moovit, Transitland), utilizați acest link permanent pentru preluarea automată a datelor:

For developers and integrators, please use this permanent direct link for automated data fetching:

🔗 **DOWNLOAD / DESCARCĂ `ungheni_gtfs.zip` (Direct Link)**  
https://github.com/UngheniTransport/gtfs/raw/main/ungheni_gtfs.zip

**Note for developers:** This link always serves the latest production version of the feed.

---

## 🚍 Routes / Rute

### Urban / Urbane
| Route | Name | Color | Timetable |
|---|---|---|---|
| U1 | Dănuțeni ⇄ Tineretului | 🟣 `#c90eaa` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ruta-1.pdf |
| U2 | Curculeovca ⇄ Tineretului | 🟠 `#e77817` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ruta-2.pdf |
| U3 | Zagarancea ⇄ Ungheni Deal | 🟢 `#8dc63f` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ruta-3.pdf |
| U4 | Zagarancea ⇄ Ungheni Vale | 🔵 `#1d71b8` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ruta-4.pdf |

### Interurban / Interurbane
| Route | Name | Color | Timetable |
|---|---|---|---|
| Ungheni-Iași | Ungheni ⇄ Iași | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-iasi.pdf |
| Nispor.-Iași | Nisporeni ⇄ Iași | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-nisporeni-iasi.pdf |
| Ung-Chișinău | Ungheni ⇄ Chișinău | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-chisinau.pdf |
| Ungheni-Nisp | Ungheni ⇄ Nisporeni | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-nisporeni.pdf |

### Raional / District
| Route | Name | Color | Timetable |
|---|---|---|---|
| UN-Nisporeni | Ungheni ⇄ Nisporeni (Slavena) | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-nisporeni-slavena.pdf |
| UN-Frăsineş. | Ungheni ⇄ Frăsineşti | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-frasinesti.pdf |
| UN-Unțeşti | Ungheni ⇄ Unţeşti | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-untesti.pdf |
| UN-Costuleni | Ungheni ⇄ Costuleni | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-costuleni.pdf |
| UN-Taxobeni | Ungheni ⇄ Taxobeni | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-taxobeni.pdf |
| UN-Bumbata | Ungheni ⇄ Bumbata | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-bumbata.pdf |
| UN-Rădenii V | Ungheni ⇄ Rădenii Vechi | 🔴 `#e2001a` | https://unghenitransport.md/images/orare/transport-public-ungheni-orar-ungheni-radenii-vechi.pdf |

---

## 🛠 Technical Details / Detalii Tehnice

| Field | Value |
|---|---|
| Format | GTFS Schedule (Fares V1) |
| Location | Ungheni, Moldova |
| Publisher | Transport Public Ungheni |
| Website | https://unghenitransport.md/ |
| Agency ID | 1025609001851 |
| Routes | **15** (4 urban + 4 interurban + 7 raional) |
| Stops | **198** |
| Trips | **1,568** |
| Stop times | **40,387** |
| Shapes points | **47,411** |
| Feed period | **2026-02-15 — 2026-12-31** |
| Feed version | **1.0.5** |
| Languages | Romanian (feed_lang), Russian (default_lang) |
| Timezone | Europe/Chisinau |
| Maintainer | GTFS@unghenitransport.md |
| Contact URL | https://github.com/UngheniTransport/gtfs |

---

## 📋 Files Included / Fișiere Incluse

`ungheni_gtfs.zip`
```text
ungheni_gtfs.zip
├── agency.txt
├── calendar.txt
├── calendar_dates.txt
├── fare_attributes.txt
├── fare_rules.txt
├── feed_info.txt
├── frequencies.txt
├── routes.txt
├── shapes.txt
├── stop_times.txt
├── stops.txt
└── trips.txt
