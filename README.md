# On Revisiting Entropy for Identifying Mislabeled Images

This repository contains the official implementation of **On Revisiting Entropy for Identifying Mislabeled Images**, accepted by ICML 2026.

<p align="center">
  <img src="./liuchengtu.png" width="900" alt="Framework of On Revisiting Entropy for Identifying Mislabeled Images">
</p>

## Environment

The code was tested with the following key packages:

```text
torch == 2.0.0
torchvision == 0.15.1
torchaudio == 2.0.1
numpy == 1.24.1
scipy == 1.15.2
scikit-learn == 1.6.1
pandas == 2.2.3
pillow == 11.1.0
opencv-contrib-python == 3.4.18.65
matplotlib == 3.10.1
tqdm == 4.67.1
transformers == 4.46.1
timm == 1.0.15
open_clip_torch == 2.32.0
pytorch-lightning == 1.5.0
```

## Training

Run the following command for training:

```bash
bash train.sh
```

## Inference

Run the following command for inference:

```bash
python nld_test.py
```

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{li2026revisiting,
  title={On Revisiting Entropy for Identifying Mislabeled Images},
  author={Li, Chunlei and Zheng, Zixuan and Shi, Yilei and Dong, Guanglu and Li, Pengfei and Hu, Jingliang and Zhu, Xiao Xiang and Mou, Lichao},
  booktitle={International Conference on Machine Learning},
  year={2026}
}
```
