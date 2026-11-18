# UT Austin Campus Heat Mapping, Shade & Walkability

[Published campus field results](https://robert-z-lehr.github.io/UT-Campus-Heat-Mapping-Shade-and-Walkability---Notebook-Analyses/)

This repository contains the fall field report, map, four analysis plots, session summaries, and the [analysis notebook](fall-2026-kestrel-analysis.ipynb) without saved execution outputs.

## Reproduce the fall analysis

1. Obtain the original fall CSV archive through the project team. It is not distributed in this repository.
2. Create a Python environment and install the dependencies in `requirements.txt`.
3. Set `KESTREL_CSV_ZIP` to the archive path, or place a copy named `CSV.zip` in the notebook working directory.
4. Run the notebook from top to bottom. Expect 36 source files, 50 original sessions, 5,933 original readings, 47 retained sessions, 5,563 retained readings, and 45 mapped sessions.

The website is a static snapshot. Running the notebook does not regenerate the website. Exposure labels are provisional. The existing notes classifier can mark “no shade” as Mixed. Review and regenerate all affected summaries before publishing any corrected classifications. These records do not establish a causal shade effect or validate SOLWEIG.
