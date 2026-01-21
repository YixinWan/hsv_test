# HSV 色彩空间测试与可视化

本项目用于测试和可视化 HSV 色彩空间相关算法。

## 环境配置

### 方法一：使用 Conda (推荐)

```powershell
# 创建并激活 conda 环境
conda env create -f environment.yml
conda activate hsv_test
```

### 方法二：使用 pip

```powershell
pip install -r requirements.txt
```

## 使用方法

1. 激活 conda 环境:
   ```powershell
   conda activate hsv_test
   ```

2. 启动 Jupyter Notebook:
   ```powershell
   jupyter notebook
   ```

3. 打开 `hsv_visualization.ipynb` 文件

4. 按顺序运行各个单元格

## 功能特性

- ✅ RGB 与 HSV 颜色空间转换
- ✅ HSV 圆柱体 3D 可视化
- ✅ HSV 色调色轮可视化
- ✅ 基于 HSV 的颜色分割
- ✅ HSV 各通道分析
- ✅ 交互式测试环境

## 主要库

- **OpenCV**: 图像处理和颜色空间转换
- **NumPy**: 数值计算
- **Matplotlib**: 数据可视化
- **Jupyter**: 交互式开发环境

## 项目结构

```
hsv_test/
├── hsv_visualization.ipynb  # 主要的可视化和测试 Notebook
├── environment.yml          # Conda 环境配置文件
├── requirements.txt         # pip 依赖文件
└── README.md               # 项目说明
```

## 环境管理

```powershell
# 更新环境
conda env update -f environment.yml

# 删除环境
conda deactivate
conda env remove -n hsv_test
```
