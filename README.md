# Seminar Roulette

![Django Pipeline](https://github.com/olliegardner/seminar-roulette/actions/workflows/django.yml/badge.svg)
![Node.js Pipeline](https://github.com/olliegardner/seminar-roulette/actions/workflows/node.yml/badge.svg)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![GitHub contributors](https://img.shields.io/github/contributors/olliegardner/seminar-roulette.svg)](https://github.com/olliegardner/seminar-roulette/graphs/contributors/)


## Requirements

- Python 3.7 or later
- Python packages: listed in [requirements.txt](seminar-roulette/requirements.txt)
- Node.js 12.16.1 or later
- npm packages: listed in [package.json](seminar-roulette/frontend/package.json)
- PostgreSQL 10.7 or later

See [manual.md](manual.md) for build instructions.

## File Structure

This repository contains all of the submitted project files and also the application's source code. The project has been structured as follows.

    .
    ├── data                    # Data acquired during the project.
    ├── dissertation            # LaTeX source for dissertation.
    ├── images                  # Images of the application.
    ├── meetings                # Records of supervisor meetings.
    ├── presentation            # Prerecorded video presentation.
    ├── seminar-roulette        # Source code for the project.
    ├── status-reports          # Weekly reports sent to supervisor.
    ├── LICENSE                 # License for the project.
    ├── manual.md               # Guide for how to setup the codebase.
    ├── plan.md                 # Week-by-week plan for project.
    ├── README.md               # README file.
    └── timelog.md              # Time log for the whole project.

## Screenshots

| ![Homepage](images/homepage.png) | ![Expanded Seminar](images/seminar.png) |
| :------------------------------: | :-------------------------------------: |
|             Homepage             |          Expanded Seminar Tile          |

| ![Search Page](images/search.png) | ![Dark Theme](images/dark-theme.png) |
| :-------------------------------: | :----------------------------------: |
|            Search Page            |              Dark Theme              |

## User Manual

A manual has been created to explain how to run and setup Seminar Roulette. See [manual.md](manual.md) for more details.

## Acknowledgements

The code found in the [shibboleth folder](seminar-roulette/shibboleth/) is reponsible for integrating the University's single sign-on to Seminar Roulette. Full credit for the code contained in this folder goes to the authors of [django-shibboleth-remoteuser](https://github.com/Brown-University-Library/django-shibboleth-remoteuser). This project has been licensed under the MIT License.

The recommender system code found within [recommender.py](seminar-roulette/recommender.py) was partially implemented using a tutorial. Partial credit for this code goes to Nick Becker for his [Matrix Factorisation for Movie Recommendations in Python](https://beckernick.github.io/matrix-factorization-recommender/) tutorial.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) file for more details.

---

