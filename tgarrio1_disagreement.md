# Disagreement Examples — tgarrio1 & aamphone

**Participants:** Tyler Garriott (`tgarrio1`) and Aidan Amphonephong (`aamphone`).

## Example 1 — [peal/vole](https://github.com/peal/vole) (HasRecovered)

**Author:** N/A (artifact gap) (`aamphone`)  
**Validator:** Yes (`tgarrio1`)  
**Reason:** The 67-month gap comes from a website commit with a 2014 author date and a 2021 committer date. After removing that timestamp issue, the longest actual gap is December 2023–July 2024. I marked Yes because dependency work resumed on August 27, 2024 after that gap.  
**Resolution:** Yes (ValidatorKept). Aidan agreed that recovery should be judged after the corrected gap.

## Example 2 — [HIVE-ResearchGroup/volumetric-data-interaction](https://github.com/HIVE-ResearchGroup/volumetric-data-interaction) (ActivityPattern)

**Author:** irregular (`tgarrio1`)  
**Validator:** stopped (`aamphone`)  
**Reason:** I marked irregular because the time series has large, uneven bursts. Aidan rechecked the September 30, 2025 cutoff and found 11 months without commits after October 1, 2024, compared with a longest earlier gap of only two months. There were also no pull requests after #9. That makes the final gap different from the shorter pauses during development.  
**Resolution:** stopped (ValidatorKept). I accepted Aidan's answer. We agreed to use stopped when a project is Inactive at the cutoff and either has an explicit end signal or has been silent longer than its own longest earlier gap.

## Example 3 — [oscaribv/pyaneti](https://github.com/oscaribv/pyaneti) (RecentThemes)

**Author:** Bug fixes:Feature development (`tgarrio1`)  
**Validator:** Bug fixes:Documentation updates (`aamphone`)  
**Reason:** We both listed bug fixes first. I counted the added examples as feature development, while Aidan counted them as documentation. These commits add example inputs and data under `inpy/` without adding new functionality.  
**Resolution:** Bug fixes:Documentation updates (ValidatorKept). We agreed that usage examples count as documentation when they do not add new functionality.
