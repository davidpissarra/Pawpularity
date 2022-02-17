# Pawpularity

Kaggle Competition Bronze Medal :3rd_place_medal: (205th out of 3537 teams)

Machine Learning 2021/2022 @ Tsinghua University, final project

## Authors
[Armando Fortes](https://github.com/atfortes) & [David Pissarra](https://github.com/davidpissarra)

## Overview

Nowadays, millions of stray animals are alone on the streets or living in shelters, waiting for a new home. With the aim of better understanding the impact of pet photos and their features, [*PetFinder.my*](https://www.petfinder.my/) - Malaysia's leading animal welfare platform - designed a metric which measures pet photo popularity - *Pawpularity* - and hosted a related [Kaggle competition](https://www.kaggle.com/c/petfinder-pawpularity-score/overview).

Follows the architecture of our best performing solution for the competition:

![arch](/docs/figs/arch_readme.png)

## Built With

- [Swin Transformer](https://arxiv.org/pdf/2103.14030.pdf) (Images)
- [XGBoost](https://arxiv.org/pdf/1603.02754v3.pdf) (Metadata)
- [Optuna](https://optuna.org/) (Ensemble Model tuning)

Further details on our solution may be found in the [report](https://github.com/atfortes/Pawpularity/blob/main/docs/report.pdf).
