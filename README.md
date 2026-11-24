# HPC in the Cloud · 2023 Literature Survey

Completed 2023 research artifact on running HPC workloads on cloud infrastructure. This archive preserves the report, source, and reading list.

## Survey report

- [Read the full survey report (PDF, 14 pages)](report/main.pdf)
- [Browse the full bibliography (47 entries)](BIBLIOGRAPHY.md)
- [LaTeX source](report/main.tex) and [BibTeX bibliography](report/references2.bib)

The archived PDF is titled *HPC in the Cloud: ana overview of the issues in transitioning and the reasons to overcome them*. The LaTeX source is titled *Bridging HPC and Cloud: Issues and Incentives*.

## Zotero collections

- [HPC Cloud Lit Review](https://www.zotero.org/germanfak/collections/U7333JNT)
- [HPC Cloud Thesis](https://www.zotero.org/germanfak/collections/ZCJHRN5K), which includes references for the Snellius study on HPC containerization and interconnect performance.

Both collections require Zotero sign-in and library access.

To build the report, install TeX Live with the ACM bibliography style and the LaTeX packages used in the source, plus Inkscape for the SVG figures. From the `report` directory, run `latexmk -pdf -shell-escape main.tex`.
