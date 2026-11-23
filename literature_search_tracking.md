# Literature search tracking sheet (SWR, Chapter 3 method)

Searches run by the author on 22 November 2026. The numbers below are the
real counts shown by the databases, and they match the "Literature Search
Protocol" subsection in main.tex.

## 1. Search questions

- Which studies evaluate ML-based network intrusion detection on CIC-IDS2017
  or on attacks that were not seen during training?
- Which dataset-quality problems of CIC-IDS2017 have been reported?

## 2. Search strings

S1 (generalization):
("intrusion detection" AND "machine learning" AND (CICIDS2017 OR "CIC-IDS2017")
 AND ("unseen attack" OR "unknown attack" OR "zero-day" OR "novel attack" OR generalization))

S2 (data quality):
("intrusion detection" AND (CICIDS2017 OR "CIC-IDS2017")
 AND ("label error" OR "labelling errors" OR "dataset errors" OR "data quality" OR flaws))

## 3. Criteria

- Inclusion (IC): IC1 peer-reviewed journal, conference paper or book;
  IC2 English; IC3 about ML-based network intrusion detection;
  IC4 last ten years, plus seminal works.
- Exclusion (EC): EC1 duplicates; EC2 preprints and technical reports;
  EC3 no described evaluation.

## 4. Search log (real numbers, 22 November 2026)

| String | Database | Results | Screened (title + abstract) | Notes |
|---|---|---|---|---|
| S1 | IEEE Xplore | 175 (153 conf., 20 journals, 1 book, 1 early access) | first 25 | sorted by relevance |
| S1 | Google Scholar | about 14,700 | first 10 | sorted by relevance |
| S2 | IEEE Xplore | 19 (16 conf., 2 journals, 1 early access) | all 19 | |
| S2 | Google Scholar | about 5,030 | first 10 | sorted by relevance |

Found through these searches and added to the reference list:
cantone2024, dhooge2020, tran2022.

Already in the reference list and confirmed to appear in the results:
maseer2021 (S1, Google Scholar), engelen2021 and lanvin2023 (S2, Google Scholar).

Excluded examples: results from academia.edu and ResearchGate copies and
arXiv preprints (EC2); papers about software vulnerabilities rather than
network intrusion detection (IC3).

## 5. Included papers (17)

For each: confirm authors, venue, year, pages and DOI on the publisher page,
and read the abstract.

| Key | Type | Opened the publisher page | Read abstract | Notes |
|---|---|---|---|---|
| sharafaldin2018 | conference | | | the dataset paper |
| engelen2021 | conference | | | |
| liu2022 | conference | | | check page numbers |
| lanvin2023 | conference | | | |
| rosay2022 | conference | | | |
| tran2022 | journal | | | no DOI in the file |
| ring2019 | journal | | | |
| maseer2021 | journal | | | no DOI in the file |
| sommer2010 | conference | | | seminal |
| arp2022 | conference | | | |
| verkerken2022 | journal | | | |
| hindy2020 | journal | | | |
| dhooge2020 | journal | | | |
| cantone2024 | journal | | | confirm the page range |
| breiman2001 | journal | | | seminal |
| chen2016 | conference | | | seminal |
| pedregosa2011 | journal | | | software reference |

Rule from the course: AI tools can invent references, so a reference only
stays in the list after you opened it yourself.
