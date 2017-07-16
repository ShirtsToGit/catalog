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

## General Guidelines and Process
All contributions must be performed as a Pull Request. [Pull Request Etiquette](https://gist.github.com/mikepea/863f63d6e37281e329f8) is a great general guide, though portions are specific to github and/or software, the general princples are well laid out.

1. Read and understand the [LICENSE](LICENSE.md), as any pull request is considered acknowledgement and acceptence of those terms. 
2. Fork the codebase into your own repo (some prefer a named branch, not required)
2. Modify the repository until satisfied, use clear commit messages for every change.
3. Rebase the forked repository to ensure you have the latest from master, and check your work if anything is merged.
4. Create a Pull Request using clear title and sumamry.

** ShirtsToGit, its creator, and other contributors are not liable for your contribution. It is important to understand that we take intelectual property rights seriously, and will vigorously aid anyone pursuing injunctions, lawsuits or any other attempt to address infringement of intellectual property rights. **


## Contributing a new work
TO contribute a new work, please follow the steps above. For any new work you are accepting full liability should the work later be revealed to be based in whole or part from another's and/or infringe on any intellectual property rights. In order to contribute a work you are claiming full legal ownership of the work, claiming right to license the work, and agree to license defined in [LICENSE](LICENSE.md).

## Contribting a modification
To modify an existing work, please follow the steps under **General Guidelines**. For all modifications you are accepting full liability should the alteration later be revealed to be based in whole or part from another's work outside the original piece, and/or infringe on any intellectual property rights. 

For instance, if you modify a shirt called "Simple Bunnies" by submitting a duplicate called "Bugs Bunny" you would be infringing on the property and rights of Warner Bros. Entertainment Inc. and liabale for any damages they wished to charge.  Should this someone get through a Pull Request Review and published, you would be liable for all damages sought by Warner Brothers or any future owner of that property.

