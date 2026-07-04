
---

# 🛠️ 环境要求

本项目需要以下环境支持：
* **操作系统**：Ubuntu Linux 虚拟机
* **Python 版本**：3.10
* **核心依赖库**：NumPy

---

# 💻 如何运行代码

1. 进入代码所在的文件夹：
   ```bash
   cd ~/first
2. 激活环境：
   ```bash
   conda activate lab_base
3. 运行代码：
   ```bash
   python main.py

```markdown
---

## 🛠️ 环境配置说明（Environment Setup）

为了保证代码能顺利运行，请使用 Conda 创建独立的虚拟环境，避免与其他项目冲突。

### 1. 创建并激活环境
打开 Linux 终端，依次运行以下命令：
```bash
# 创建一个名为 lab_base 的干净 Python 3.10 环境
conda create -n lab_base python=3.10 -y

# 激活并进入该环境
conda activate lab_base
```

### 2. 安装依赖库
在激活的 `lab_base` 环境下，运行以下命令安装核心计算库：
```bash
pip install numpy
```
```

粘贴进去后，按下 `Ctrl + S` 保存。

---