# 机械设计课程设计说明书

带式运输机传动装置设计，使用 LaTeX 排版。

## 项目结构

```
├── HebutThesis_example.tex  # 主文件
├── hebutthesis.cls          # 文档类
├── bibliography.bib         # 参考文献
├── fzxbsjt.ttf              # 仿宋字体
├── document/                # 各章节 tex 文件
│   ├── cover.tex            # 封面
│   ├── chap01.tex           # 设计任务书
│   ├── chap02.tex           # 电动机选择
│   ├── chap03.tex           # 传动比分配
│   ├── chap04.tex           # 动力学参数
│   ├── chap05.tex           # 齿轮传动设计
│   ├── chap06.tex           # 开式齿轮传动
│   ├── chap07.tex           # 轴的设计与校核
│   ├── chap08.tex           # 轴承校核
│   ├── chap09.tex           # 键联接与联轴器
│   ├── chap10.tex           # 润滑密封
│   ├── chap11.tex           # 箱体结构
│   └── bibliography.tex     # 参考文献设置
├── dwg/                     # AutoCAD 工程图
├── figures/                 # 图片与插图
└── HebutThesis_example.pdf  # 编译输出
```

## 编译

```bash
xelatex HebutThesis_example
biber HebutThesis_example
xelatex HebutThesis_example
xelatex HebutThesis_example
```

或使用 latexmk：

```bash
latexmk -xelatex HebutThesis_example
```

## 许可证

本项目基于 [GPL v2.0 License](./LICENSE) 开源发布。
