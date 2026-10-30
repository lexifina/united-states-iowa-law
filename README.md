# Iowa: law history in git

The statute law of Iowa as a git repository: one file per section, committed with the Iowa Legislative Services Agency as its publisher. It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law).

**What is in it now**

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `constitution/` | Constitution of the State of Iowa (codified, including Amendment 49 of 2022) | 1 | Oldest version available |
| `ch-701/` to `ch-723a/` | Iowa Code, Title XVI chapters 701 to 723A (the Criminal Code) | 1 each | Oldest version available |
| `ch-490/` | Iowa Code chapter 490 (Business Corporations) | 1 | Oldest version available |

That is all the law this repository holds today. Property and contracts chapters, other titles, session laws and regulations are not in it.

## Where the text comes from

- Iowa Code 2026: per-chapter XML published by the Legislature (`www.legis.iowa.gov/docs/publications/ICC/2026/attachments/<chapter>_slim.xml`). Section text and each section's source note ("history") are kept; the Legislature's footnotes are left out.
- Constitution: the Legislature's codified PDF, read with the page layout. Footnotes and amendment cross-references are left out.

## Dates

Iowa publishes no dated history of the Code online in machine-readable form. Each act is one version, dated by the edition: 2025-10-20 for the Code (the latest timestamp in the chapter files) and 2024-12-09 for the Constitution (the PDF's creation date). These are edition dates, not the days the words took effect. Adding earlier editions (Iowa publishes PDFs from 2004) and Acts-based amendment commits is the next step.
