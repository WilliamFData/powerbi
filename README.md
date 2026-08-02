# Power BI Showcase

A demo Power BI project built to showcase data modeling, DAX, and Power BI development practices.

📖 **Start here → [Project Wiki](https://github.com/WilliamFData/powerbi/wiki)**

The wiki covers the full build: data dictionary, DAX and SQL libraries, filtering patterns, versioning, and deep dives into specific problems solved along the way (e.g. [SDLY vs SPLY](https://github.com/WilliamFData/powerbi/wiki/SDLY-vs-SPLY)).

## What's in this repo

- `PBI Showcase.pbix` — the Power BI report file
- `SQL/` — supporting SQL used to build the underlying data model

## A note on .pbix vs .pbip

This project uses the `.pbix` format rather than `.pbip`, even though `.pbip` is the better choice for version control — it splits the report into readable, diffable text files (JSON/TMDL) instead of one opaque binary, so changes can be tracked properly in Git.

I've stuck with `.pbix` here because this repo is a portfolio showcase rather than a collaborative production project, and `.pbix` is still the format most people expect to open and click through directly. For real-world projects with a team and ongoing change history, `.pbip` is the format I'd use and recommend.

## Getting started

Clone the repo and open `PBI Showcase.pbix` in Power BI Desktop, or browse the [wiki](https://github.com/WilliamFData/powerbi/wiki) to see the design decisions without opening the file.
