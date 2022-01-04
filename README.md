## 说明

一个使用 Python 语言编写的小工具，用于将 Kindle 笔记导出为网页文件.fork 自 [kindleNote](https://github.com/cyang812/kindleNote)，重写生成 html 样式为 [书伴网 Clippings Fere 工具](https://bookfere.com/tools#ClippingsFere)，使之适配移动端

## 使用

- 从 kindle 中拷贝出标注文件，重命名为 source.txt
- 下载本项目源码，使用你的 source.txt 进行替换
- 在 Python3 环境下执行 `python kindle.py` 指令，等待生成网页文件
（如果报错`TypeError: 'encoding' is an invalid keyword argument for this function`,需要执行 `python3 kindle.py` 指令）
