# Conda 环境说明

2025/12/25

本项目使用 Conda 来管理 Python 环境和依赖包,请遵循以下步骤配置 Conda 环境：

```bash
conda create -n wave_analyst python=3.12
conda activate wave_analyst

conda install -c conda-forge numpy scipy matplotlib pandas

conda install -c conda-forge pyqt=5 pyside6

```
