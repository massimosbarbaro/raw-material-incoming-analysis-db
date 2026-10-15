# Materie prime: incoming inspection of raw materials

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23398815.svg)](https://doi.org/10.5281/zenodo.23398815)

*Analisi delle materie prime in arrivo*

**db** · 1998–1999 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Materie prime records the incoming inspection of the raw materials delivered to a plastics plant: trade name, origin, delivery date, analysis number, lorry plate, lot, number of bags, particle size, sieving, contaminants, the checks performed, the laboratory analyses and the destination silo. The analyses can be searched by name, origin, lot, plate, silo and dispatch.

I designed and programmed this application in 1998–1999. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Entry and modification of the incoming analysis (`SImmissioneDati`, `SModificaDati`).
- Searches by trade name, origin, lot, plate, silo, dispatch and notes (`SRDenominazione`, `SRProvenienza`, `SRLotto`, `SRTarga`, `SRSilo`, `SRInvio`, `SRNote`).
- Printed table of the analyses (`RTabella`).

## Data

Tables `Analisi materie prime` and `ANalmag`.

## Technology

db, 97 format (.mdb), forms, report and macros.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The database application, emptied of all data. |
| `source/queries/` | SQL of the saved queries. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: every table has been emptied, the file compacted and the unused space inside its pages overwritten with zeros, so no record of the original data survives. Logos of the organisations for which the program was built have been blanked inside the forms, and the names of organisations, people and places in captions and code have been replaced with neutral text of the same length; the application is otherwise the original file. The file is in the 1997 db format: it opens with the 1997–2010 versions of the database software; later versions must first convert it with an intermediate version.

## Related repositories

- [laboratory-quality-control-reports-db](https://github.com/massimosbarbaro/laboratory-quality-control-reports-db)
- [laboratory-test-requests-db](https://github.com/massimosbarbaro/laboratory-test-requests-db)
- [compound-formulas-archive-db](https://github.com/massimosbarbaro/compound-formulas-archive-db)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23398815](https://doi.org/10.5281/zenodo.23398815).

> Sbarbaro, Massimo. 1999. *Materie prime: incoming inspection of raw materials*. Software (db, 1998–1999), version 1.0. Zenodo. https://doi.org/10.5281/zenodo.23398815.

## License

Released under the [MIT License](LICENSE). © 1998 Massimo Sbarbaro.
