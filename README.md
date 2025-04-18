# Transformer数学推导与实践

[Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

本项目实现Transformer核心组件的数学推导与可视化，包含：
- 位置编码的波形分析
- 注意力矩阵梯度推导
- 国产化适配（昇腾NPU）

快速开始
bash
git clone https://github.com/XiaoyuYang001/Transformer-Math-Derivation.git
pip install -r requirements.txt
python src/positional_encoding.py  # 生成位置编码可视化


数学原理
位置编码公式：
$$
PE_{(pos,2i)} = \sin\left(\frac{pos}{10000^{2i/d_{model}}}\right)
$$
编码热力图：figs/pe_comparison.png
