# Disagreement Examples — tgarrio1 & aamphone

## Example 1 — [peal/vole](https://github.com/peal/vole) (HasRecovered)

**Author:** N/A (artifact gap) (`aamphone`)  
**Validator:** Yes (`tgarrio1`)  
**Reason:** The 67-month gap comes from a website commit with a 2014 author date and a 2021 committer date. After removing that timestamp issue, the longest actual gap is December 2023–July 2024. I marked Yes because dependency work resumed on August 27, 2024 after that gap.  
**My view:** Yes (ValidatorKept).  
**Resolution:** Pending discussion.

## Example 2 — [WinVector/vtreat](https://github.com/WinVector/vtreat) (HasRecovered)

**Author:** No (only sporadic upkeep) (`aamphone`)  
**Validator:** Yes (`tgarrio1`)  
**Reason:** Work resumed on August 19, 2023 with “rebuild and recheck” after the February 2022–July 2023 gap. More package, example and documentation changes followed in 2024–2025. I counted this as recovery because maintenance is still project activity, and the coding guide does not require a certain number of commits. The project can recover and later become inactive again.  
**My view:** Yes (ValidatorKept).  
**Resolution:** Pending discussion.

## Example 3 — [isl-org/MiDaS](https://github.com/isl-org/MiDaS) (ActivityPattern)

**Author:** irregular (`tgarrio1`)  
**Validator:** stopped (`aamphone`)  
**Reason:** I originally marked irregular, but the official repository had no commits after August 23, 2024 and was archived on August 25, 2025. The later activity in WoC came from forks. Since the coding guide includes stopped, I think Aidan's label fits the official repository better.  
**My view:** stopped (ValidatorKept).  
**Resolution:** Pending discussion.

## Example 4 — [covid-projections/covid-data-model](https://github.com/covid-projections/covid-data-model) (ActivityPattern)

**Author:** declining (`tgarrio1`)  
**Validator:** stopped (`aamphone`)  
**Reason:** I marked declining because commit counts dropped over several years. Aidan marked stopped because dataset updates ended in July 2024 and January 2025 changes closed registration and reduced automation. I think stopped makes sense given those shutdown changes. They also occurred before the September 2025 cutoff, so the February 2026 README is not needed to support this answer.  
**My view:** stopped (ValidatorKept).  
**Resolution:** Pending discussion.

## Example 5 — [HIVE-ResearchGroup/volumetric-data-interaction](https://github.com/HIVE-ResearchGroup/volumetric-data-interaction) (ActivityPattern)

**Author:** irregular (`tgarrio1`)  
**Validator:** stopped (`aamphone`)  
**Reason:** I marked irregular because the time series has large, uneven bursts. There were no commits after October 1, 2024, so it was Inactive at the September 2025 cutoff. Aidan's two-year gap uses October 2026. I would lean toward keeping irregular for the historical pattern, since being a thesis project does not by itself show that development permanently ended. This is one I still need to discuss with Aidan.  
**My view:** irregular (AuthorKept), pending discussion of how to apply stopped.  
**Resolution:** Pending discussion.

## Example 6 — [movsim/movsim](https://github.com/movsim/movsim) (RecentThemes)

**Author:** Dependency updates:Feature development (`tgarrio1`)  
**Validator:** Dependency updates:Automated bot contributions (`aamphone`)  
**Reason:** We both listed dependency updates first. I listed feature development second, while Aidan listed automated bot contributions. There are multiple Dependabot updates in the recent commits, and the coding guide specifically includes those as bot contributions. I would use Aidan's pair, but we should check that we are counting the same ten commits and handling overlapping themes the same way.  
**My view:** Dependency updates:Automated bot contributions (ValidatorKept).  
**Resolution:** Pending discussion.

## Example 7 — [oscaribv/pyaneti](https://github.com/oscaribv/pyaneti) (RecentThemes)

**Author:** Bug fixes:Feature development (`tgarrio1`)  
**Validator:** Bug fixes:Documentation updates (`aamphone`)  
**Reason:** We both listed bug fixes first. I counted the added examples as feature development, while Aidan counted them as documentation. Since these commits add example inputs and data under `inpy/` without adding new functionality, I think documentation is the better fit.  
**My view:** Bug fixes:Documentation updates (ValidatorKept).  
**Resolution:** Pending discussion.
