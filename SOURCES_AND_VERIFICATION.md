# Sources and verification

Checked **September 4, 2026**. This record distinguishes source identity and bibliographic checks from verification of every chess claim. The collection remains an independent tribute. The original PDFs and Chess.com ZIP were preserved without modification.

## Existing files

All four local PDFs were compared byte for byte, using SHA-256, with fresh responses from their publisher-hosted URLs. All four matched. The page counts below were also checked locally.

| File | PDF pages | Verified source |
| --- | --- | --- |
| `The_Practical_Endgame_2014-2020.pdf` | 140 | [US Chess collection](./Links/README.md#l001), also linked by the [Charlotte foundation archive](./Links/README.md#l007) |
| `9313.pdf` | 25 | [New In Chess sample](./Links/README.md#l008) |
| `9315.pdf` | 15 | [New In Chess sample](./Links/README.md#l009) |
| `9317.pdf` | 18 | [New In Chess sample](./Links/README.md#l010) |

The [machine-readable record](./data/verification_2026-09-04.json) contains the hashes and article checks. Matching bytes verifies file identity; it does not establish that every historical variation is correct or that republication permission has been granted.

## Books and editions

- [Mastering Positional Chess](./Links/README.md#l011): the local sample identifies the revised and updated 2026 edition. Jacob Aagaard's publisher foreword, printed p. 5 / PDF p. 3, explains the later updating of the analysis. Attribute that foreword to Aagaard.
- [Mastering Complex Endgames](./Links/README.md#l012): the sample title page identifies the revised and updated 2026 edition; its contents distinguishes Sam Shankland's 2026 foreword from Yasser Seirawan's 2012 foreword. These are separate contributors' texts.
- [Mastering Practical Endgames](./Links/README.md#l013): a 2026 posthumous collection, not a newly completed manuscript by Danya. Peter Boel's publisher foreword, printed pp. 5-6 / PDF pp. 3-4, explains that the editors arranged Chess Life and Chess.com articles by theme. Attribute the editorial selection and foreword accordingly.

All three numbered PDFs are **samples**, not complete books. Publication year is taken from the samples' title pages; no exact regional release date, price, or stock availability is asserted.

## The existing Chess.com ZIP

- The ZIP passed its internal integrity check. Its CSV contains **113 rows**: 99 articles, 6 lesson links, 7 broadcast/highlight entries, and 1 archive hub.
- Its **113 Windows shortcuts** match the CSV's URL list, including repeated destinations. There are **110 distinct URL strings**: four championship entries share the archive's broadcasts section, as the package explains.
- All **99 article URLs returned HTTP 200**, and their main titles matched the catalog after normalizing punctuation and capitalization. The corresponding 99 titles were matched in order to the [official archive](./Links/README.md#l005).
- All **99 catalog article dates** matched the dates in the official archive's table. All 113 catalog URL strings were also found in the package's bookmarks, searchable HTML, and workbook XML; this checks the link data, not the workbook's appearance.
- **22 stored article addresses differ from the archive's current addresses.** The stored addresses still serve the matching titled pages and declare themselves canonical. They were not treated as broken or replaced merely for having different slugs.
- The [lesson-series page](./Links/README.md#l014) confirms five lessons, the displayed 12/14/16/15/12-minute durations, 69 minutes total, and the December 9, 2019 release date. The sixth lesson entry is the series hub.

The catalog is an aid to finding sources, not an exhaustive archive of Danya's output. Article dates in the official archive can differ from the destination page's later “Updated” date. For example, the archive dates The Chess Investigator to January 24, 2020; the article currently displays an update on June 3, 2025. Those are different metadata fields, not evidence of two different articles.

Full broadcast playback, every destination's access requirements, and the catalog workbook's visual layout were not revalidated. No guarantee of permanent availability is made.

## New teaching material and navigation

The [study guide](./STUDY_GUIDE.md) links each paraphrased teaching to Danya's original writing. The King Activity quotation was checked in the description on his own upload. The [video guide](./VIDEO_LESSONS.md) uses his channel's public playlist metadata; all 18 endgame entries name his channel. No automatic transcript was treated as a verified spoken quotation.

The [70-column index](./PRACTICAL_ENDGAME_INDEX.md) covers June 2014-March 2020. All rendered column headings and the issue months were checked. It is not an engine audit or a new edition of the analysis. Some exercises refer to solution pages in the original magazines, outside their two-page column extracts. The first digital-archive check was blocked, but the later direct HTTP check reached the landing page. Individual answer pages remain unchecked.

The [Perpetual Chess interview](./Links/README.md#l015) was checked through the host's dated episode page and show notes. Its approximate timestamps are credited to those notes; the audio was not independently transcribed.

## Memorial image and further research

`canvas.png` depicts the December 2025 Chess Life cover. The cover identification is supported by its visible text and [US Chess's own use and caption](./Links/README.md#l004). The README now credits the publication. The individual cover artist and any separate reuse permission were not established by this review; no license has been invented.

The [foundation archive](./Links/README.md#l007) links a [New York Times chess-puzzle collection](./Links/README.md#l016), and the later direct HTTP check reached its landing page. Individual columns have not been reviewed or cataloged here.

The [US Chess memorial resource page](./Links/README.md#l017) is included as a publisher-controlled route to its PDF and PGN. Its contributors' annotations are not relabeled as Danya's. The new files add no claims about the circumstances of his death or other private matters.

## Limits of this review

The new editorial text, attribution, links, file identity, and index metadata were checked as described above. The existing hundreds of chess variations, all biographical statements inside source publications, and complete videos have **not** undergone independent verification. A source can be authentic and still contain an error. Record future corrections separately, following [CONTRIBUTING.md](./CONTRIBUTING.md).


## Preservation and link organization update

The [PDF library](./PDF_LIBRARY.md) now separates locally saved writing, publisher samples, and the US Chess memorial PDF. The [online resource directory](./Links/README.md) holds the human-readable external links. A fresh check of 151 distinct HTTP destinations found no HTTP failures; 29 YouTube destinations require playback verification. See the [dated report](./Links/LINK_CHECK_REPORT.md).

## Additional teaching-source search

The [follow-up guide](./ADDITIONAL_TEACHINGS.md) records six additional official-hosted PDFs containing his own writing. All six were downloaded into a separate research working folder, parsed, hashed, and visually checked at the cited pages. They were not added as mirrored files to this repository. The review found no explicit open license or general redistribution permission for them.

Three important attribution checks: the February 2008 Srbis-game notes are his, while the surrounding story is Aviv Friedman's; the 2013 and 2014 game annotations are his within Brian Jerauld's features; and the three new forewords belong to books by Kalinin, Giannatos, and Tillis. The guide also records the Giannatos sample's edition mismatch with its current product page and the Palm Beach PDF's incorrect contents-page pointer.

The original 151-destination audit and the 11-source follow-up are separate batches from the same date. Their combined totals and the older interview's HTTP 403 access issue are shown in the [link report](./Links/LINK_CHECK_REPORT.md). The later Chess.com journal article was checked as a published source; its reported family request against publishing the full journal is retained in the guide. No unpublished journal was sought or copied.
