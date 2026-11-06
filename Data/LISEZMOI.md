# Les données des TD

Source : Banque mondiale, World Development Indicators (https://data.worldbank.org), téléchargées en novembre 2026. Licence CC BY 4.0 : citer la Banque mondiale en cas de réutilisation.

Couverture : 19 pays (Allemagne, Autriche, Belgique, Chine, Corée du Sud, Danemark, Espagne, États-Unis, Finlande, France, Israël, Italie, Japon, Pays-Bas, Pologne, Portugal, Royaume-Uni, Suède, Tchéquie), de 2000 à 2023.

Unité d'observation : un pays une année donnée (456 lignes par fichier). Une case vide signifie que la source ne fournit pas la valeur. Ce n'est pas un zéro.

## rd-pays-2000-2023.csv (TD 1 et 2)

| Variable | Définition | Unité | Code Banque mondiale |
|---|---|---|---|
| `pays` | nom du pays en français | | |
| `code` | code du pays (ISO 3166, trois lettres) | | |
| `annee` | année | | |
| `rd_pib` | dépenses intérieures de recherche et développement | % du PIB | GB.XPD.RSDV.GD.ZS |
| `chercheurs_par_million` | chercheur.ses en R&D | pour un million d'habitant.es | SP.POP.SCIE.RD.P6 |
| `pib_par_habitant` | PIB par habitant en parité de pouvoir d'achat | dollars internationaux constants de 2021 | NY.GDP.PCAP.PP.KD |

## brevets-pays-2000-2023.csv (TD 2)

| Variable | Définition | Unité | Code Banque mondiale |
|---|---|---|---|
| `code`, `annee` | clé de la table (pays et année) | | |
| `brevets_residents` | demandes de brevets déposées par des résident.es du pays | nombre | IP.PAT.RESD |
| `population` | population totale | nombre | SP.POP.TOTL |
| `export_haute_techno` | exportations de produits de haute technologie | % des exportations de produits manufacturés | TX.VAL.TECH.MF.ZS |

## base-innovation-pays-2000-2023.csv (TD 3 et 4)

Réunion des deux fichiers précédents par pays et par année, avec deux variables ajoutées :

| Variable | Définition | Unité |
|---|---|---|
| `zone` | Europe (14 pays) ou Hors Europe (5 pays) | |
| `brevets_par_million` | `brevets_residents` / `population` x 1 000 000 | brevets pour un million d'habitant.es |

## Limites à garder en tête

- L'intensité de R&D mesure un effort et non un résultat.
- Les demandes de brevets dépendent des pratiques de dépôt, qui varient selon les pays et les secteurs.
- Les séries de la Banque mondiale peuvent être révisées. Une valeur peut différer de celle d'Eurostat ou de l'OCDE.
