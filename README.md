# Pyreneeën 2026 – Reisstatus

Dit repo bevat alleen het live reisveiligheidsrapport voor de zomervakantie 2026
(Gouda → Normandië → Île de Ré → San Sebastián → Pyreneeën → Auvergne → Fontainebleau →
Pairi Daiza → Gouda). Het wordt automatisch bijgewerkt door een geplande cloud-agent, rond
elke verplaatsdag — zie het hoofdproject
[pyrenees-2026](https://github.com/frankheemelaar-prv/pyrenees-2026) voor de vakantie-app
zelf (privé) en het volledige plan.

- **`report.json`** — het meest recente rapport. Wordt door de vakantie-app rechtstreeks
  opgehaald via de publieke raw-URL. Bevat bewust geen adressen of andere persoonlijke
  reisdetails — alleen route-, brand- en wegstatus.
- **`report-history/`** — kopie van elk eerder rapport (audit trail / dedup-referentie voor
  de agent zelf).

Dit repo bestaat bewust los van de (privé) hoofd-repo, zodat de app zonder inloggen kan
lezen terwijl de rest van de reisgegevens privé blijft.
