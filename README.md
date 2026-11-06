# Noise-Augmented Argoverse 2 Dataset

## Overview

This repository hosts a noise-augmented version of the [Argoverse 2 (AV2) Motion Forecasting Dataset](https://argoverse.github.io/user-guide/argoverse_2.html).

To support research in robust trajectory prediction, we have extended the original AV2 dataset by introducing realistic object state estimation uncertainties arising from sensing and Vehicle-to-Everything (V2X) communications.

Specifically, we model distance-dependent sensing noise affecting objects detected by the ego-vehicle's onboard sensors, as well as additional positioning uncertainties arising from localization errors at V2X transmitters. These noise sources are applied to the objects' state estimates (position, speed, and heading) to better reflect real-world operating conditions.

The noise-augmented dataset is designed to support the training and evaluation of trajectory prediction models under realistic sensing and V2X noise conditions.

For further details on the dataset generation methodology and noise models, please refer to our paper (reference will be added upon publication).


## License
This modified dataset is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0), in accordance with the original Argoverse 2 dataset terms. See the `LICENSE` file for more details.
