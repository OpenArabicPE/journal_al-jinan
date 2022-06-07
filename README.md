---
title: "journal_al-jinan: read me"
author: Till Grallert
date: 2018-11-03
---

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1167878.svg)](https://doi.org/10.5281/zenodo.1167878)

This repository contains bibliographic metadata for the journal *al-Jinān* published by Buṭrus al-Bustānī in in Beirut between 1875 and 1885. Digital facsimiles of the copies held at the Princeton University Library are available from HathiTrust. 

# current state

- 2018-11-03: added TEI files for each issue of *al-Jinān*. These are place-holder files that contain bibliographic metadata and the relevant number of page breaks (`<pb>`) for future linking to digital facsimiles.
- 2018-02-06: released complete metadata as TEI and MODS XML

# some technical details

This repository contains a single [TEI XML][source] file containing one `<biblStruct>` for each issue. This file is produced through automatic iteration making use of [this code](https://www.github.com/OpenArabicPE/generate_metadata-through-iteration) and manual validation against the digital facsimiles.
The TEI is then [automatically converted](https://www.github.com/OpenArabicPE/convert_tei-to-mods) to [MODS XML][mods] for integration into reference management software etc (such as Zotero). 
Metadata on the issue level has been integrated into the [OpenArabicPE Zotero group][zotero].


[source]: tei/al-jinan.TEIP5.xml
[mods]: metadata/al-jinan.MODS.xml
[zotero]: https://www.zotero.org/groups/904125/openarabicpe/collections/XZ6Y3L7X