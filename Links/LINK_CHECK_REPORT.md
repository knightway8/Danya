# Link check report

Checked September 4, 2026. This is a dated snapshot of the repository's external resource links, not a guarantee of future availability.

The initial audit covered 151 destinations. A later search on the same date added 11 destinations, checked separately. The totals below combine those two batches.

| Check | Result |
| --- | --- |
| URL entries in the directory | 163 |
| Distinct HTTP destinations, excluding fragments | 162 |
| HTTP 200 responses | 161 |
| Ordinary page or PDF responses | 132 |
| YouTube page responses; playback unverified | 29 |
| Direct automated requests returning HTTP 403 | 1 |
| Confirmed HTTP 404 or 410 failures | 0 |
| Other HTTP failures or connection errors | 0 |

**No removed page was confirmed.** The 2010 US Chess interview ([L161](./README.md#l161)) returned HTTP 403 to the direct automated request, while its text was retrievable through the web reader. Treat it as **access varies**, not as a proven broken link. All six newly examined PDF downloads completed successfully.

YouTube playback, membership access, and remote page fragments remain unverified. An HTTP 200 response does not prove every page feature works.

The 99 article destinations were previously checked against their catalog titles and the official archive's dates on the same day. The 22 older article slugs still serve the matching articles; they were not classified as broken merely because the archive uses different addresses.

The US Chess digital archive and New York Times chess-puzzle landing pages responded to this direct HTTP check, although the earlier browser/search-tool fetches were blocked. Those earlier access errors were not evidence that the links were broken. Individual answer pages and New York Times articles have not been reviewed.

## Rechecking or correcting an entry

Open the relevant entry in the [online directory](./README.md). If it stops working, check the original publisher or creator for a replacement and keep the previous address in the history. Record the check date and distinguish a removed page from a login prompt, a temporary outage, or an automated-access block. Do not substitute a different person's material under Danya's name.

The original 151 results are recorded in [link_checks_2026-09-04.json](./link_checks_2026-09-04.json). The 11 supplementary checks, with PDF identity and review details, are recorded in [additional_source_checks_2026-09-04.json](./additional_source_checks_2026-09-04.json). The directory's identifiers are recorded in [resources.json](./resources.json).
