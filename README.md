[![Compile LaTeX](https://github.com/Kkobarii/bachelor-thesis/actions/workflows/compile.yml/badge.svg)](https://github.com/Kkobarii/bachelor-thesis/actions/workflows/compile.yml)
# My Bachelor Thesis

This repo hosts the code and documentation for my bachelor thesis.

## Assignment

The assignment of the thesis is to create an elaborate narrative evolutionary game that would combine both physically playable components and a virtual environment, which would serve as a manual for setting up and evolving game situations, recording players, tournaments, and game teams.

This thesis was written in a team of four members, each member focusing on a different aspect of the game development. My focus was on creating the game model and defining the rules for user behavior within the game.

The whole thesis is written in Czech, so I'm sorry to disappoint my non-Czech visitors to this repo. However, if you are interested in the result of our labour, you can find it on our organization page, [Trails Through Shadows](https://github.com/Trails-Through-Shadows).

If you do want to read through the thesis itself, or just looks at the pretty pictures, you can find it on my [thesis page](https://thesis.kkobari.eu).

## How to Build

Not gonna lie, the build process is quite a pain. My setup process consists of opening the repo in VS Code with the LaTeX Workshop extension installed, compiling it through that, and fixing any issues that come up.

Some notes that might help you build it locally:

- Make sure you have a reasonably complete TeX distribution (TeX Live or MikTeX) because the project uses many packages. You can install them through your distribution's package manager or use the package manager that comes with your TeX distribution.
- Some things to have:
    - `biber` (for bibliography processing).
    - `inkscape` and a Java runtime (required for PlantUML/diagram generation).
    - Czech localization files for LaTeX (`texlive-lang-czech`).

Good luck out there!

## Continuous Integration

This repository has a very neat and very useless GitHub Actions workflow (`.github/workflows/compile.yml`) that builds the PDF on push and pull requests and uploads the compiled `bachelor.pdf` as an artifact. The output file is then uploaded to my [thesis repo](https://github.com/Kkobarii/thesis), so you can always find the latest version there.

## Contributing

If you find any typos or mistakes in the thesis, feel free to open an issue or a pull request.

> Originally written January - April 2024