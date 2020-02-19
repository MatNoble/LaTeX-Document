# LaTeX-Document 中英文科技文档模板

<img src="https://latex.codecogs.com/svg.latex?\LaTeX" title="LaTeX" alt="ＬaTeX" />自用中英文文档模板(数学).

为文章增加红, 蓝, 黄, 绿四色(Google 配色), 使文章不再单调. 定理部分借鉴[这里](https://github.com/kalxd/morelull)

<img src="https://imgkr.cn-bj.ufileos.com/c4bef68f-6157-4981-b1d7-629e991ee838.png" width="400">

模板源代码有适当注释, 简单易懂, 易上手, 易自定义.

有任何问题, 欢迎提交[Issues](https://github.com/MatNoble/LaTeX-Document/issues)!

## 预览

### 在线预览
[点击这里](https://cn.overleaf.com/read/qcpjwfmmtnvr)

### 英文预览

<img src="https://raw.githack.com/MatNoble/LaTeX-Document/master/Images/Document-EN.svg" title="英文首页预览" alt="数系家园LaTeX英文文档" width="500">

### 中文预览

<img src="https://raw.githack.com/MatNoble/LaTeX-Document/master/Images/Document-CN.svg" title="中文首页预览" alt="数系家园LaTeX中文文档" width="500">

## 使用说明

`git clone git@github.com:MatNoble/LaTeX-Document.git` 到本地即可使用.

### 公式字体
以下二选一
```
% \usepackage{mathptmx} % 打印
\usepackage{charter} % 屏读
```

### 中文字体
中文版需要下载安装字体[在这里](https://github.com/MatNoble/Fonts)

思源宋体

思源黑体

Adobe kaiti

Adobe Fangsong

### 代码环境
[Minted](https://www.overleaf.com/learn/latex/Code_Highlighting_with_minted) 是 Latex 上非常好用的代码高亮工具, 可以借助 Python 包 Pygement 根据不同的语法高亮.
需要安装 python, 然后使用工具安装 pygments. 这里假设你已经安装了 pip 和相关 Python.

1. `pip install Pygments`;
2. 使用 xelatex 编译的时候需要加上参数 `–shell-escape`.

效果如下:

<img src="https://imgkr.cn-bj.ufileos.com/653a65d0-2cce-4909-8498-aa2301f9843f.png" title="代码环境" width="300">

若不使用代码环境, 在对应的 `.sty` 文件中把对应代码注释掉即可.

```
% 代码高亮
% \RequirePackage{minted}
% \usemintedstyle{emacs}
```

### Using Emacs as LaTeX editor

#### Table


## 关注我吧

<img src="https://raw.githubusercontent.com/MatNoble/Picture/master/wechat.gif" title="公众号: 数系家园" alt="公众号: 数系家园" width="300">

## 授权情况
本模板代码按[LPPL v1.3c 协议](https://github.com/MatNoble/LaTeX-Document/blob/master/LICENSE)授权

## 联系方式
Mail: [hustmatnoble@gmail.com](mailto:hustmatnoble@gmail.com)
