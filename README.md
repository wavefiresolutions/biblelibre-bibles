## BibleLibre Bibles

This repository contains Bible translation files in XML, maintained by Wavefire Solutions PH for the [BibleLibre SDK](https://github.com/wavefiresolutions/biblelibre-sdk). These files use a generic BibleLibre XML structure that is different from Zefaniah, OSIS, and USFX source formats.

> [!NOTE]
> The BibleLibre SDK supports reading Zefaniah, OSIS, and USFX. This repository stores a normalized, non-standard XML format intended to make maintenance and peer review easier.

#### Bible Versions Overview

| File Name | Abbrev | Version | License |
| --- | --- | --- | --- |
| ASV.xml | ASV | American Standard Version | Public Domain / CC0 |
| KJV.xml | KJV | King James Version | Public Domain / CC0 |
| TLAB.xml | TLAB | Ang Biblia | Public Domain / CC0 |

#### Formatting Peer Review

This repository accepts peer review reports for formatting and XML conversion issues only.

Scope:
- XML structure and hierarchy issues (testament, book, chapter, verse nesting)
- Verse numbering mismatches or misplaced verse boundaries caused by conversion
- Character encoding and escaped entity issues introduced during formatting
- Missing or malformed attributes relevant to file consistency

Out of scope:
- Translation changes
- Theology-related wording corrections
- Doctrinal interpretation suggestions

Required:
- Short Description of Issue
- Correction
- Linkable sources and references from the same version as the one being peer reviewed

Suggested report format:
1. Version/File: example ASV.xml
2. Location: testament/book/chapter/verse (or exact XML snippet)
3. Issue: what is incorrect in formatting or conversion
4. Proposed correction: exact corrected XML content
5. Sources: links or references that match the same Bible version

#### License
All files in this repository are provided under CC0 1.0 Universal and are intended for public-domain use.

For legal text, see the [LICENSE](LICENSE) file.