# NovaRetail – API simulat (date fictive)

Răspunsuri JSON statice care simulează API-urile serviciilor SaaS ale companiei fictive NovaRetail,
folosite în prototipul Cloud BI din Microsoft Fabric (proiect universitar SIIA, ASE București).

| Resursă | Sursă simulată | Fișier |
|---|---|---|
| Clienți | CRM | `v1/clienti.json` |
| Comenzi online (linii) | Platformă e-commerce | `v1/comenzi.json` |

Structura răspunsului: `{ "sursa", "resursa", "generat_la", "numar_inregistrari", "data": [ ... ] }`.
Toate datele sunt generate sintetic; numele, adresele de e-mail și numerele de telefon sunt fictive.
