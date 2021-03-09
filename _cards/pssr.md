---
layout: card
name: Deep learning-based point-scanning super-resolution imaging
image: pssr.jpg
image_href: https://www.nature.com/articles/s41592-021-01080-z
header: Deep learning-based point-scanning super-resolution imaging
tags:
  - publication
  - airyscan
  - confocal
  - deeplearning
  - sem
item_sort: 30
---
Point-scanning imaging systems are among the most widely used tools for high-resolution cellular and tissue imaging, benefiting from arbitrarily defined pixel sizes. The resolution, speed, sample preservation and signal-to-noise ratio (SNR) of point-scanning systems are difficult to optimize simultaneously. We show these limitations can be mitigated via the use of deep learning-based supersampling of undersampled images acquired on a point-scanning system, which we term point-scanning super-resolution (PSSR) imaging. We designed a ‘crappifier’ that computationally degrades high SNR, high-pixel resolution ground truth images to simulate low SNR, low-resolution counterparts for training PSSR models that can restore real-world undersampled images. For high spatiotemporal resolution fluorescence time-lapse data, we developed a ‘multi-frame’ PSSR approach that uses information in adjacent frames to improve model predictions. PSSR facilitates point-scanning image acquisition with otherwise unattainable resolution, speed and sensitivity. All the training data, models and code for PSSR are publicly available at 3DEM.org.