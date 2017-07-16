# Contributing to ShirtsToGit.com
The term "Contribution", "Contributing" encompasses new submissions and modifications to existing catalog.

# License
All designs are licensed under [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) . In short this means:

- You have the legal right to grant this license to the work as creator or owner.
- You will allow others to use and modify this work, requiring only attribution.

**See [LICENSE](LICENSE.md) for the full legal text of this license and ensure you understand and agree. The submission of any contribution is considered full agreement to these terms.**


## Basic Structure
Every catalog item has a few basic required files.
```
.
├── meta.json # The ley to describe attribution and styles
├── description.md # Markdown formatted file of shirt used in store front
├── design.svg # Raw SVG describing shirt front
└── sample.png # Web portable image format showing svg rendered on shirt
```

Additionally some designs may add optional files.
```
.
├── design-back.png # If shirt should include additional graphics on back
└── sample-back.png # Web portable image format showing svg rendered on shirt
```
