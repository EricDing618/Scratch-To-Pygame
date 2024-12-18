# Scratch-To-Pygame
![GitHub repo size](https://img.shields.io/github/repo-size/EricDing618/Scratch-To-Pygame)
![GitHub Repo stars](https://img.shields.io/github/stars/EricDing618/Scratch-To-Pygame?style=flat)
![GitHub branch status](https://img.shields.io/github/checks-status/EricDing618/Scratch-To-Pygame/main)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/EricDing618/Scratch-To-Pygame)
![GitHub last commit](https://img.shields.io/github/last-commit/EricDing618/Scratch-To-Pygame)
![GitHub Created At](https://img.shields.io/github/created-at/EricDing618/Scratch-To-Pygame)

## 描述
- Scratch-To-Pygame（STP）是一个用Python实现的将Scratch转换为Pygame的脚本工具，现已支持`.sb3`文件。
## 快速使用
在本仓库目录下使用`cmd`执行：
```bash
python stp.py <你的.sb3文件位置>
```
更多使用方法请执行：`python stp.py -h`。
## 第三方库&软件
库：
- loguru==0.7.2
- cairosvg==2.7.1
- pillow==9.5.0
- pygame==2.5.2
- numpy==1.26.2
- colorama==0.4.6

软件：
- gtk3 3.24.31

若您还没有安装这些第三方库或已经遇到了`ImportError`，请使用`pip install -r requirements.txt`，以及安装`bin`目录下的软件（仅支持Windows x64）。
## 报错解决
- `ImportError`：详见**第三方库**。

若这仍不能解决您的问题，请确保该问题没有在issues被提出并解决，然后创建issue并等待解决。