# Quentyx

**Des moteurs logiciels qui se parlent.**

Quentyx construit une suite de moteurs. Chacun fait une seule chose et s’installe seul. Tous reposent sur le même principe : ce qui s’est passé fait foi, et ce qu’on affiche en est déduit. Un moteur ne porte aucune interface : il en sert plusieurs, par une API HTTP stable, que des personnes comme des modèles de langage peuvent utiliser.

Certains moteurs sont en service chez nous, d’autres sont en construction.

| Moteur | Rôle |
|---|---|
| **[Factur-X](https://github.com/Quentyx/quentyx-facturx)** | Factures électroniques françaises (EN 16931, PDF/A-3) : produire, lire, valider, serveur MCP, envoi par une plateforme agréée. **Public.** |
| **Switch** | Une seule porte pour tout ce qui sort : intelligence artificielle, courriel, SMS, appels, publication. |
| **RCO** | Relation client observée : la relation est constatée, jamais saisie. |
| **Calendrier** | Agendas partagés et prise de rendez-vous. |
| **Tel** | Téléphonie, branchable sur n’importe quel opérateur. |
| **Chat** | Messagerie d’équipe. |
| **Scrib** | Base de données, en construction. |
| **Vera** | Contrôle de la qualité des pages web, selon un profil. |
| **NCG** | Documentation lisible sur place, par les humains et par les modèles. |

Ils sont écrits en Node.js, pour la plupart sans aucune dépendance externe.

**Un moteur est public : [quentyx-facturx](https://github.com/Quentyx/quentyx-facturx)**, sous LGPL-3.0, avec un palier Pro sous licence commerciale ([npm](https://www.npmjs.com/package/quentyx-facturx)). Les autres dépôts de cette organisation sont privés, tous droits réservés.

**Contact :** contact@quentyx.fr

---

# Quentyx (English)

**Software engines that talk to each other.**

Quentyx builds a suite of engines. Each one does a single thing and installs on its own. They all rest on the same principle: what happened is the source of truth, and what you see is derived from it. An engine carries no interface of its own: it serves several, through a stable HTTP API that people and language models can both use.

Some engines are in service with us, others are under construction.

| Engine | Role |
|---|---|
| **[Factur-X](https://github.com/Quentyx/quentyx-facturx)** | French e-invoices (EN 16931, PDF/A-3): produce, read, validate, MCP server, sending through a certified platform. **Public.** |
| **Switch** | A single gateway for everything that goes out: artificial intelligence, email, SMS, calls, publishing. |
| **RCO** | Observed customer relationship: the relationship is observed, never typed in. |
| **Calendar** | Shared calendars and appointment booking. |
| **Tel** | Telephony, pluggable into any carrier. |
| **Chat** | Team messaging. |
| **Scrib** | Database, under construction. |
| **Vera** | Web page quality checks, by profile. |
| **NCG** | Documentation read in place, by humans and by models. |

They are written in Node.js, most of them with no external dependency at all.

**One engine is public: [quentyx-facturx](https://github.com/Quentyx/quentyx-facturx)**, under the LGPL-3.0, with a Pro tier under a commercial licence ([npm](https://www.npmjs.com/package/quentyx-facturx)). The other repositories of this organization are private, all rights reserved.

**Contact:** contact@quentyx.fr
