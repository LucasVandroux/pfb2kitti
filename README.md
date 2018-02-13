# pfb2kitti
**Jupyter Notebook to create a new dataset for 2D Object Detection in the [KITTI dataset](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=2d) format from the [Playing for Benchmarks dataset](http://playing-for-benchmarks.org/overview/).**

![Examples of uses of PFB2KITTI](https://i.imgur.com/4XnzXw6.png)

## Prerequisites

- [python](https://www.python.org/) ≥ _v3.5.4_
- [imageio](https://pypi.python.org/pypi/imageio) ≥ _v2.2.0_
- [opencv](https://pypi.python.org/pypi/opencv-python) ≥ _v3.3.1_                  
- [tqdm](https://pypi.python.org/pypi/tqdm) ≥ _v4.19.4_

__Optional:__
- [kittipy](https://github.com/LucasVandroux/KittiPy/releases/tag/v1.0) _v1.0_

## Installing

1. Download the [Playing for Benchmarks dataset](http://playing-for-benchmarks.org/download/)
2. _(Optional)_ Download `kittipy.py` and put it in the same folder as the Jupyter Notebook
3. Launch the Jupyter Notebook server
3. Follow the instructions on the notebook
4. Enjoy!

## Miscellaneous
Some images or folders are missing:
 - Folders `train/img/059` and `val/img/019` are both __empty__.
 - Folders `train/img/060`, `train/img/061`, `train/img/062`, `train/img/063`, `train/img/064` and `train/img/065` are __missing__.

## Author

* **Lucas Vandroux (冯凯)** [【Github】](https://github.com/LucasVandroux) [【LinkedIn】](https://www.linkedin.com/in/lucasvandroux/)

I started this project to help me during my Master Thesis at Tsinghua University in China. If you find it useful, don't hesitate to use it and improve it.

---
![Logos Footer](https://i.imgur.com/bCStMxt.png)
