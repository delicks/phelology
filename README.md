# Phenology

物候期提取的Python脚本，包括：

- [x] SG滤波
- [x] double logistic 拟合
- [ ] 物候期提取（SOS、EOS、LOS）

## 依赖项
需要安装 Anaconda3，下载地址 [Windows 64位](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-2020.11-Windows-x86_64.exe) [Windows 32位](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-2020.11-Windows-x86.exe)

另外，还需要额外安装以下包：

```bash
conda install gdal
conda install -c conda-forge rasterio
pip install ad
```