# KT-NeRF

## 1. Download datasets

You can download the data  [here](https://drive.google.com/file/d/1XqX0JAXbhMZbSOW_3qSr_G5jVz85wuYY/view?usp=drive_link).

For the scenes of Deblur-NeRF (*cozy2room*, *factory* etc.), the folder `images` only includes blurry images and the folder `images_1` additionally includes novel view images. But for the scenes of BAD-NeRF (*room-low* and *room-high* ), there are no novel view images.

## 2. Acknowledgment

The overall framework, metrics computing and camera transformation are derived from [nerf-pytorch](https://github.com/yenchenlin/nerf-pytorch/), [Deblur-NeRF](https://github.com/limacv/Deblur-NeRF) and [BAD-NeRF](https://wangpeng000.github.io/BAD-NeRF) respectively. We appreciate the effort of the contributors to these repositories.
