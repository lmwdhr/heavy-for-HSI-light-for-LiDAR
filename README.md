# heavy-for-HSI-light-for-LiDAR

***MMRS*** is a python tool to perform deep learning experiments on multi-modal remote sensing data.

This repository is developed on the top of [MMRS](https://github.com/likyoo/Multimodal-Remote-Sensing-Toolkit) . 

## Intro
本仓库为论文 《非对称结构的高光谱（HSI）与激光雷达（LiDAR）图像分类模型》 的官方开源实现。
该论文已发表于 《浙江大学学报（工学版）》，欢迎同行交流与审阅。
如果您在运行代码的过程中遇到任何问题，欢迎随时与我们联系。

## Usage

1. Start a Visdom server:
    python -m visdom.server
Then open your browser and navigate to
    http://localhost:8097
 to monitor training visualizations.
2. Run the main script:
    python main.py
For additional features and extended functionalities, please refer to [DeepHyperX](https://github.com/nshaud/DeepHyperX).

