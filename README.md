# Noise-Augmented Argoverse 2 Dataset

## Overview

This repository provides a noise-augmented version of the [Argoverse 2 (AV2) Motion Forecasting Dataset](https://argoverse.github.io/user-guide/argoverse_2.html).

To support research on robust trajectory prediction, we extend the original AV2 dataset by introducing realistic object state estimation uncertainties arising from sensing and Vehicle-to-Everything (V2X) communications.

Specifically, we model distance-dependent sensing noise affecting objects detected by the ego vehicle's onboard sensors, as well as additional positioning uncertainties caused by localization errors at V2X transmitters. These noise sources are applied to the objects' state estimates (position, speed, and heading) to better reflect real-world operating conditions.

The resulting dataset supports the training and evaluation of trajectory prediction models under sensing and V2X noise conditions.

For further details on the dataset generation methodology and noise models, please refer to our associated paper (reference will be added upon publication).

## Dataset Availability

The **Noise-Augmented Argoverse 2 Dataset** is publicly available on Zenodo.

**Download the dataset:** [Zenodo – Noise-Augmented Argoverse 2 Dataset](https://zenodo.org/records/24080078)


## License
This modified dataset is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0), in accordance with the original Argoverse 2 dataset terms. See the `LICENSE` file for more details.
