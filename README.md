[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Rye](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/rye/main/artwork/badge.json)](https://rye.astral.sh)

# Motion Planning

## Dependency

- [python](https://www.python.org/)
  - version 3.10 or higher is recommended.

- [rye](https://rye.astral.sh/)
  - seting up python environment easily and safely.
  - `notebook`, `numpy`, `matplotlib` are needed to run all scripts in this repository.

- [ffmpeg](https://ffmpeg.org/)
  - mp4 movie writer
  - <details>
    <summary>installation details</summary>

    - For Ubuntu Users
        - `sudo apt-get update`
        - `sudo apt-get -y install ffmpeg`
    - For Windows Users
        - Install [scoop](https://scoop.sh/)
        - `scoop install ffmpeg`
    - For macOS Users
        - Install [homebrew](https://brew.sh/)
        - `brew install ffmpeg`
    - Check the official website if necessary
        - https://ffmpeg.org/

    </details>

## Setup
```sh
git clone https://github.com/MizuhoAOKI/motion_planning.git
cd motion_planning
rye sync
```

## Usage

### [Ex. 1] Dijkstra's Algorithm
<!--
```sh
cd motion_planning
rye run jupyter notebook notebooks/dijkstra.ipynb
```
-->

### [Ex. 2] A* Algorithm
<!--
```sh
cd motion_planning
rye run jupyter notebook notebooks/a_star.ipynb
```
-->

## References
- [Dijkstra, Edsger W, "A note on two problems in connexion with graphs", 1959](https://link.springer.com/article/10.1007/BF01386390)
- [Peter E. Hart; Nils J. Nilsson; Bertram Raphael, "A Formal Basis for the Heuristic Determination of Minimum Cost Paths", 1968](https://ai.stanford.edu/~nilsson/OnlinePubs-Nils/PublishedPapers/astar.pdf)
