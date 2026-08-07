# md-hunting-calendars

## White-tailed Deer Hunting Calendars — Maryland (2026–2027 season)

**Process last run:** August 7, 2026, ~UTC (this generation)

**Sources used:**
- [Maryland Deer Seasons & Bag Limits](https://www.eregulations.com/maryland/hunting/deer-seasons-bag-limits)
- [Maryland Sunday Deer Hunting](https://www.eregulations.com/maryland/hunting/sunday-deer-hunting)
- [2026–27 DNR Guide to Hunting & Trapping (PDF)](https://www.eregulations.com/assets/docs/guides/26MDHD_LR2.pdf) — used to cross-check the two pages above

### Files generated

| County | File | Events |
|---|---|---|
| Allegany | [white-tailed-deer-allegany.ics](white-tailed-deer-allegany.ics) | 145 |
| Anne Arundel | [white-tailed-deer-anne-arundel.ics](white-tailed-deer-anne-arundel.ics) | 128 |
| Baltimore | [white-tailed-deer-baltimore.ics](white-tailed-deer-baltimore.ics) | 125 |
| Baltimore City | [white-tailed-deer-baltimore-city.ics](white-tailed-deer-baltimore-city.ics) | 141 |
| Calvert | [white-tailed-deer-calvert.ics](white-tailed-deer-calvert.ics) | 145 |
| Caroline | [white-tailed-deer-caroline.ics](white-tailed-deer-caroline.ics) | 145 |
| Carroll | [white-tailed-deer-carroll.ics](white-tailed-deer-carroll.ics) | 140 |
| Cecil | [white-tailed-deer-cecil.ics](white-tailed-deer-cecil.ics) | 145 |
| Charles | [white-tailed-deer-charles.ics](white-tailed-deer-charles.ics) | 145 |
| Dorchester | [white-tailed-deer-dorchester.ics](white-tailed-deer-dorchester.ics) | 145 |
| Frederick | [white-tailed-deer-frederick.ics](white-tailed-deer-frederick.ics) | 140 |
| Garrett | [white-tailed-deer-garrett.ics](white-tailed-deer-garrett.ics) | 145 |
| Harford | [white-tailed-deer-harford.ics](white-tailed-deer-harford.ics) | 134 |
| Howard | [white-tailed-deer-howard.ics](white-tailed-deer-howard.ics) | 125 |
| Kent | [white-tailed-deer-kent.ics](white-tailed-deer-kent.ics) | 144 |
| Montgomery | [white-tailed-deer-montgomery.ics](white-tailed-deer-montgomery.ics) | 145 |
| Prince George's | [white-tailed-deer-prince-georges.ics](white-tailed-deer-prince-georges.ics) | 125 |
| Queen Anne's | [white-tailed-deer-queen-annes.ics](white-tailed-deer-queen-annes.ics) | 145 |
| Somerset | [white-tailed-deer-somerset.ics](white-tailed-deer-somerset.ics) | 145 |
| St. Mary's | [white-tailed-deer-st-marys.ics](white-tailed-deer-st-marys.ics) | 145 |
| Talbot | [white-tailed-deer-talbot.ics](white-tailed-deer-talbot.ics) | 145 |
| Washington | [white-tailed-deer-washington.ics](white-tailed-deer-washington.ics) | 145 |
| Wicomico | [white-tailed-deer-wicomico.ics](white-tailed-deer-wicomico.ics) | 145 |
| Worcester | [white-tailed-deer-worcester.ics](white-tailed-deer-worcester.ics) | 145 |

All events are all-day, `CLASS:PRIVATE`, `TRANSP:TRANSPARENT`, marked FREE for Outlook, and tagged with a dark-green (`#006400`) color extension for Apple/Outlook calendar clients that support it (color support is not universal in the iCalendar spec).

### ⚠️ Important caveat on Sunday hunting dates

The official Sunday chart is a wide table (21 named Sunday dates × 24 counties). The web/PDF text extraction used to build these calendars **preserved the season-date tables perfectly but flattened the Sunday chart's row/column structure**, so for most counties this process had to positionally reconstruct which specific Sundays are open from the count and sequence of "Open" cells rather than reading a clean grid.

**High confidence** (unambiguous from the source text): Allegany, Garrett, Cecil, St. Mary's, Baltimore County, Baltimore City, Howard, Prince George's.

**Reconstructed — please verify against the [official Sunday chart](https://www.eregulations.com/maryland/hunting/sunday-deer-hunting) before hunting**: Anne Arundel, Calvert, Caroline, Carroll, Charles, Dorchester, Frederick, Harford, Kent, Montgomery, Queen Anne's, Somerset, Talbot, Washington, Wicomico, Worcester. Every Sunday event in these files carries a `CAUTION` note in its description flagging this.

Weekday (Monday–Saturday) season dates for every county are drawn directly and unambiguously from the season tables and are not affected by this caveat.

### Note on Washington County

Washington County is split by DNR into Deer Management Region A (west) and Region B (east); the dividing line runs along Rt. 494/57/40/Big Spring Rd./Rt. 56/Charles Mill Rd. Because the county gets a single calendar file, `white-tailed-deer-washington.ics` uses **Region A** season dates and Sunday rules throughout (the broader/more permissive of the two). Hunters in the eastern portion of the county (Region B / Zone 1) should confirm season dates against the Region B tables separately — a note to this effect is included in every event description in that file.

### Note on file location

These files were generated in a cloud workspace and are provided for download; the working directory `D:\Projects\md-hunting-calendars` specified in the source instructions is a local path on your machine and isn't accessible from here. Save the downloaded files into that folder to match the original setup.
