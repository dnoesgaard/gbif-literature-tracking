# Literature sources

Overview of literature sources and how they are funneled into the literature tracking pipeline:

| Source | Format | Management | Alerts | Status | Last updated |
|---|---|---|---|---|---|
| Taylor & Francis | E-mail | https://www.tandfonline.com/search/saved | ```gbif OR "biodiversity information facility" OR "integrated publishing toolkit" OR "Biodiversity for Development" OR "Biodiversity Information Fund for Asia" OR 10.15468 OR 10.15470 OR 10.15472 OR 10.17031 OR 10.13148 OR 10.18165 OR 10.35000 OR 10.5886 OR 10.60545 OR 10.60798 OR 10.71819``` | Active | 2025-02-20 |
| NCBI Pubmed | E-mail | https://www.ncbi.nlm.nih.gov/sites/myncbi/searches/ | ```"gbif"[All Fields] OR "biodiversity information facility"[All Fields] OR "integrated publishing toolkit"[All Fields] OR "Biodiversity for Development"[All Fields] OR "Biodiversity Information Fund for Asia"[All Fields] OR "10.15468"[All Fields] OR "10.15470"[All Fields] OR "10.15472"[All Fields] OR "10.17031"[All Fields] OR "10.5886"[All Fields] OR "10.17031"[All Fields] OR "10.13148"[All Fields] OR "10.18165"[All Fields] OR "10.35000"[All Fields] OR "10.60545"[All Fields] OR "10.60798"[All Fields] OR "10.71819"[All Fields]``` | Active | 2025-02-20 |
| SpringerNature | RSS |  | `https://link.springer.com/search.rss?query=gbif+OR+%22biodiversity+information+facility%22+OR+%22integrated+publishing+toolkit%22+OR+%22biodiversity+for+development%22+OR+%22biodiversity+information+fund+for+asia%22+OR+10.15468+OR+10.15470+OR+10.15472+OR+10.5886+OR+10.60545+OR+10.60798+OR+10.17031+OR+10.13148+OR+10.18165+OR+10.35000+OR+10.71819&sortOrder=newestFirst` | Active | 2025-02-20 |
| PLOS | E-mail | https://community.plos.org/account/alerts/search-alerts | ```(everything:"GBIF") OR (everything:"biodiversity information facility") OR (everything:"integrated publishing toolkit") OR (everything:"10.15468") OR (everything:"10.15470") OR (everything:"10.15472") OR (everything:"10.17031") OR (everything:"10.13148") OR (everything:"10.18165") OR (everything:"10.35000") OR (everything:"10.5886") OR (everything:"10.60545") OR (everything:"10.60798") OR (everything:"10.71819")``` | Active | 2025-02-20 |
| Crossref event data | JSON |  |  | Active |  |
| Wiley | E-mail | https://onlinelibrary.wiley.com/search/saved | ```gbif OR "biodiversity information facility" OR "integrated publishing toolkit" OR "Biodiversity for Development" OR "Biodiversity Information Fund for Asia" OR "10.15468" OR "10.15470" OR "10.15472" OR "10.17031" OR "10.13148" OR "10.18165" OR "10.35000" OR "10.5886" OR "10.60545" OR "10.60798" OR "10.71819"``` | Active | 2025-02-20 |
| BioRxiv | E-mail | https://www.biorxiv.org/alerts | (seperate alerts for individual text strings as phrases and a combined alert for DOI prefixes) | Active | 2025-02-20 |
| DataCite event data | JSON |  |  | Active |  |
| Google Scholar | E-mail | https://scholar.google.com/scholar_alerts?view_op=list_alerts | (seperate alerts for all strings and DOI prefixes) | Active | 2025-02-20 |
| Overton | E-mail | https://app.overton.io/ui/settings/saved-searches?view=index | ```"Biodiversity Information Fund for Asia" OR "Biodiversity for Development" OR "integrated publishing toolkit" OR "Biodiversity Information Facility" OR (gbif NOT "Government Bank Insurance Fund") OR "10.15468" OR "10.15470" OR "10.15472" OR "10.17031" OR "10.13148" OR "10.18165" OR "10.35000" OR "10.5886" OR "10.60545" OR "10.60798" OR "10.71819"``` and ```excluding_source=gbif``` | Active | 2025-02-20 |
| BASE | RSS |  |  | Active |  |
| Scopus | E-mail | https://www.scopus.com/alert/form/MyAlerts.uri | ```ALL(gbif) OR ALL("biodiversity information facility") OR ALL("integrated publishing toolkit") OR ALL("Biodiversity for Development") OR ALL("Biodiversity Information Fund for Asia") OR ALL({10.15468/}) OR ALL({10.15470/}) OR ALL({10.15472/}) OR ALL({10.17031/}) OR ALL({10.13148/}) OR ALL({10.18165/}) OR ALL({10.35000/}) OR ALL({10.5886/}) OR ALL({10.60545/}) OR ALL({10.60798/}) OR ALL({10.71819/})``` | Active | 2025-02-20 |
| ScienceDirect | E-mail | https://www.sciencedirect.com/user/alerts/search | 1. ```gbif OR "biodiversity information facility" OR "integrated publishing toolkit" OR "Biodiversity for Development" OR "Biodiversity Information Fund for Asia"``` 2. ```10.15468 OR 10.15470 OR 10.15472 OR 10.17031 OR 10.13148 OR 10.18165 OR 10.35000 OR 10.5886 OR 10.60545``` 3. ```10.60798 OR 10.71819``` | Active | 2025-02-24 |
| OpenAlex | E-mail | https://openalex.org/me/searches | ```gbif OR "biodiversity information facility" OR "integrated publishing toolkit" OR "Biodiversity for Development" OR "Biodiversity Information Fund for Asia" OR 10.15468 OR 10.15470 OR 10.15472 OR 10.17031 OR 10.13148 OR 10.18165 OR 10.35000 OR 10.5886 OR 10.60545 OR 10.60798 OR 10.71819``` | Active | 2025-02-24 |
| eLibrary.ru | E-mail |  |  | not functional |  |
| CNKI | manual | see [cnki.md](./cnki.md) |  | manual | 2025-02-25 |

# Keywords used for alerts

## Generic

- "gbif"
- "biodiversity information facility"
- ipt "resource?r"
- "integrated publishing toolkit" -gbif
- "Biodiversity for Development" OR "Biodiversity Information Fund for Asia"

## DOI prefixes

| prefix   | client          | organization                                           |
|----------|-----------------|--------------------------------------------------------|
| 10.15468 | gbif.gbif       | GBIF Secretariat                                       |
| 10.15470 | csic.gbif       | GBIF Spain                                             |
| 10.15472 | gbif.co         | SiB Colombia - GBIF Colombia                           |
| 10.17031 | bl.mba          | Marine Biological Association                          |
| 10.13148 | zbmed.biofresh  | BioFresh                                               |
| 10.18165 | uam.macs        | University of Alberta Museums                          |
| 10.35000 | gbif.gbif       | GBIF Secretariat                                       |
| 10.5886  | umbc.canadensys | Canadensys                                             |
| 10.60545 | gbif.ec         | GBIF Ecuador                                           |
| 10.60798 | gbif.icipe      | International Centre for Insect Physiology and Ecology |
| 10.71819 | gbif.br         | SiBBr - GBIF Brazil                                    |
