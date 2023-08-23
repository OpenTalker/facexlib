# ![icon](assets/icon_small.png) FaceXLib x OpenTalker

## :wrench: Dependencies and Installation

- Python >= 3.7 (Recommend to use [Anaconda](https://www.anaconda.com/download/#linux) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- [PyTorch >= 1.7](https://pytorch.org/)
- Option: NVIDIA GPU + [CUDA](https://developer.nvidia.com/cuda-downloads)

### Installation

```bash
pip install git+https://github.com/OpenTalker/facexlib.git
```

### Pre-trained models

It will **automatically** download pre-trained models at the first inference. <br>
If your network is not stable, you can download in advance (may with other download tools), and put them in the folder: `PACKAGE_ROOT_PATH/facexlib/weights`.

## :scroll: License and Acknowledgement

This project is released under the MIT license. <br>

## Acknowledgement

Please visit https://github.com/xinntao/facexlib for the original code.
