# Literature sources

Overview of literature sources and how they are funneled into the literature tracking pipeline:

| Source              | Format | Management                               | Alerts                                                                                                                                                                                                                                                                                          | Status                |
|---------------------|--------|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
| Taylor & Francis    | E-mail | https://www.tandfonline.com/search/saved | gbif OR "biodiversity information facility" OR "integrated publishing toolkit" OR "Biodiversity for Development" OR "Biodiversity Information Fund for Asia" OR 10.15468 OR 10.15470 OR 10.15472 OR 10.17031 OR 10.13148 OR 10.18165 OR 10.35000 OR 10.5886 OR 10.60545 OR 10.60798 OR 10.71819 | Active                |
| NCBI Pubmed         | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| SpringerNature      | RSS    |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| PLOS                | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| Crossref event data | JSON   |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| Wiley               | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| BioRxiv             | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| DataCite event data | JSON   |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| Google Scholar      | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| Overton             | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| BASE                | RSS    |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| Scopus              | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| ScienceDirect       | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Active                |
| OpenAlex            | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | Pending webhook setup |
| eLibrary.ru         | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | not functional        |
| CNKI                | E-mail |                                          |                                                                                                                                                                                                                                                                                                 | not functional        |

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
