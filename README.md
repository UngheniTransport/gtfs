GTFS Ungheni (Official Feed)

[RO] Acesta este depozitul oficial de date deschise (Open Data) pentru transportul public din Municipiul Ungheni și rutele raionale/interurbane, gestionat de Transport Public Ungheni – Eurohome Construct S.R.L. (via unghenitransport.md).

[EN] This is the official open data repository for public transport in Ungheni Municipality and district/interurban routes, maintained by Transport Public Ungheni – Eurohome Construct S.R.L. (via unghenitransport.md).

Versiunea curentă / Current version: 1.0.19 · Perioada / Feed period: 2026-08-01 — 2027-12-31

📂 Download Data / Descărcare Date

Pentru dezvoltatori și integratori (Google Maps, Apple Maps, Moovit, Transitland), utilizați acest link permanent pentru preluarea automată a datelor:

For developers and integrators, please use this permanent direct link for automated data fetching:

🔗 DOWNLOAD / DESCARCĂ ungheni_gtfs.zip (Direct Link)

https://github.com/UngheniTransport/gtfs/raw/main/ungheni_gtfs.zip

Note for developers: This link always serves the latest production version of the feed.

🚍 Routes / Rute
Urban / Urbane
Route	Name	Color	Timetable
U1	Dănuțeni ⇄ Tineretului	🟣 
#5300EB	PDF
U2	Curculeovca ⇄ Tineretului	🟠 
#DB3E00	PDF
U3	Zagarancea ⇄ Ungheni Deal	🟢 
#008B02	PDF
U4	Zagarancea ⇄ Ungheni Vale	🔵 
#006B76	PDF
U5	Tineretului ⇄ Curculeovca	🟡 
#FCCB00	PDF
U5	Tineretului ⇄ Vile Ciachir	🟡 
#FCCB00	PDF
U5	Tineretului ⇄ Cimitirul „Chetriș"	🟡 
#FCCB00	PDF

U5 este publicată ca trei variante de traseu (_N01, _N02, _N03) sub același route_short_name. U5 is published as three route patterns (_N01, _N02, _N03) sharing one route_short_name.

Internațional / International — 🟥 
#A00E20
Route	Name	Timetable
Ungheni-Iași	Ungheni ⇄ Iaşi	PDF
Nispor.-Iași	Nisporeni ⇄ Iaşi	PDF

Trecere prin punctul vamal Sculeni — sunt posibile întârzieri la frontieră (vezi route_desc). Border crossing at Sculeni — delays are possible (see route_desc).

Interurban / Interurbane — 🟨 
#B59610
Route	Name	Timetable
UN-Balti	Ungheni ⇄ Bălţi	PDF
Ung-Chișinău	Ungheni ⇄ Chișinău	PDF
TA-Chisinau	Taxobeni ⇄ Chişinău	PDF
Ungheni-Nisp	Ungheni ⇄ Nisporeni	PDF
UN-Nisporeni	Ungheni ⇄ Nisporeni (Slavena)	PDF
Raional / District — 🟦 
#002B7F
Route	Name	Timetable
UN-Bumbata	Ungheni ⇄ Bumbata	PDF
UN-Cetireni	Ungheni ⇄ Cetireni	PDF
UN-Chirileni	Ungheni ⇄ Chirileni	PDF
UN-Condrate.	Ungheni ⇄ Condrăteşti	PDF
UN-Cornova	Ungheni ⇄ Cornova	PDF
UN-Costuleni	Ungheni ⇄ Costuleni	PDF
UN-Coseni	Ungheni ⇄ Coşeni	PDF
UN-Floritoa.	Ungheni ⇄ Floriţoaia Veche	PDF
UN-Frăsineş.	Ungheni ⇄ Frăsineşti	PDF
UN-Macaresti	Ungheni ⇄ Măcăreşti	PDF
UN-Manoiles.	Ungheni ⇄ Mănoileşti	PDF
UN-Minzates.	Ungheni ⇄ Mînzăteşti	PDF
UN-Morenii .	Ungheni ⇄ Morenii Noi	PDF
UN-Napadeni	Ungheni ⇄ Năpădeni	PDF
UN-Petrești	Ungheni ⇄ Petrești	PDF
UN-Pirlita	Ungheni ⇄ Pîrliţa #1	PDF
UN-Pirlita	Ungheni ⇄ Pîrliţa #2	PDF
UN-Rădenii V	Ungheni ⇄ Rădenii Vechi	PDF
UN-Rezina	Ungheni ⇄ Rezina	PDF
UN-Semeni	Ungheni ⇄ Semeni	PDF
UN-Sinesti	Ungheni ⇄ Sineşti	PDF
UN-Taxobeni	Ungheni ⇄ Taxobeni	PDF
UN-Tescureni	Ungheni ⇄ Teşcureni	PDF
UN-Todiresti	Ungheni ⇄ Todireşti	PDF
UN-Unțeşti	Ungheni ⇄ Unțeşti	PDF
🎫 Tarife și bilete / Fares & Ticketing

Feed-ul include tarifele complete (GTFS Fares V1) și legături directe către bilete electronice (GTFS Ticketing extension).

The feed ships complete fare data (GTFS Fares V1) plus e-ticketing deep links (GTFS Ticketing extension).

	
Monedă / Currency	MDL
Urban (U1–U5)	6,00 MDL · transfer gratuit 30 min (transfer_duration = 1800)
Raional / Interurban	9,80 – 116,70 MDL (per rută / per route)
Internațional (Iași)	150,00 MDL
Metode de plată / Payment	payment_method=0 la bord / onboard (cash) · payment_method=1 în avans / prepaid (card, app)
Bilete online / E-tickets	https://eungheni-transport.md/app/ticketing/tickets

Tarifele sunt legate de rute prin fare_rules.route_id (fără zone tarifare). ticketing_identifiers.txt mapează 192 de stații către sistemul de bilete e-Ungheni.

Fares are attached to routes via fare_rules.route_id (no fare zones). ticketing_identifiers.txt maps 192 stops to the e-Ungheni ticketing system.

🛠 Technical Details / Detalii Tehnice
Field	Value
Format	GTFS Schedule (Fares V1 + Ticketing extension)
Location	Ungheni, Moldova
Publisher	Transport Public Ungheni
Website	https://unghenitransport.md/
Agency ID	1025609001851
Agency phone	+373 67 330 330
Routes	39 (7 urban + 5 interurban + 2 international + 25 raional)
Stops	382
Trips	726
Stop times	15 116
Shapes	74 (74 742 points)
Services (calendar)	8
Fare products	66 (fare_attributes), 78 rules
Feed period	2026-08-01 — 2027-12-31
Feed version	1.0.19
Languages	Romanian (feed_lang), Russian (default_lang)
Timezone	Europe/Chisinau
Accessibility	wheelchair_boarding / wheelchair_accessible populate
Maintainer	GTFS@unghenitransport.md
Contact URL	https://github.com/UngheniTransport/gtfs
📋 Files Included / Fișiere Incluse
ungheni_gtfs.zip
├── agency.txt
├── calendar.txt
├── calendar_dates.txt          # gol / empty (doar antet / header only)
├── fare_attributes.txt
├── fare_rules.txt
├── feed_info.txt
├── frequencies.txt             # gol / empty (doar antet / header only)
├── routes.txt
├── shapes.txt
├── stop_times.txt
├── stops.txt
├── ticketing_deep_links.txt    # nou / new
├── ticketing_identifiers.txt   # nou / new
└── trips.txt
