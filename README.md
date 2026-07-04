# 🚀 Linux、Python 与 Git 基础训练项目
## 📂 项目结构（Directory Structure）

```text
first/
├── main.py          # 主程序脚本（包含 NumPy 矩阵平方测试）
├── requirements.txt # 
└── README.md        # 本说明文档
```
## 🛠️ 环境配置说明（Environment Setup）
为了确保代码能够顺利运行并具有良好的可复现性，请在 Linux 系统中使用 Conda 部署独立的虚拟环境：

1. 创建并激活 Conda 环境
打开 Linux 终端，依次运行以下命令：
    ```bash
    # 创建一个名为 lab_base 的干净 Python 3.10 环境
    conda create -n lab_base python=3.10 -y
    ```

    ```bash
    # 激活并进入该环境
    conda activate lab_base
    ```
2. 安装项目依赖库
在激活的 lab_base 环境下，运行以下命令安装核心计算库：
    ```bash
    pip install numpy

## 💻 如何运行项目（Usage）
环境配置完成后，每次运行项目只需简单三步：

1. 进入项目根目录：
    ```bash
    cd ~/first
    ```
2. 激活虚拟环境：
    ```bash
    conda activate lab_base
    ```
3. 使用当前环境运行主程序：
    ```bash
    python main.py
    ```
