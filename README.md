# phelology
从MODIS影像中提取物候期的Python脚本，包括
- SG 滤波
- double logistic 拟合
- 物候期提取（SOS、EOS、LOS）

## 依赖项
本脚本为Python编写，需要安装 Anaconda 环境，下载地址：[Windows 64位](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-2020.11-Windows-x86_64.exe) [Windows 32位](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-2020.11-Windows-x86.exe)

需要额外安装的 Python 包有：
```python
conda install rasterio
conda install gdal
pip install ad
```
