# t-slim

> t-slim 快速将当前目录(及其子孙目录)的
> `javascript`文件压缩并将语法转译为 es5
> `css`文件压缩并添加游览器前缀

## 安装

```
npm install -g t-slim
```

## 参数

> 可根据提供的参数，对指定文件，或文件夹，进行处理；
> 并提供 覆盖原文件，或生成以 .min 为后缀新文件
> 默认配置为 执行当前目录，将处理后的内容 生成 .min 后缀的文件

### -y --yes

执行默认配置

### -s --sub-folder

是否处理子孙目录(是:同时处理子孙目录中的 js，css 文件 否:仅处理当前目录文件)

### -c --cover

是否覆盖原文件(是:覆盖原文件 否:新内容以.min 的新文件生成)

### -f --files

指定待处理的文件(多个文件请用空格隔开)

### -d --dir

指定待处理的文件夹(仅支持单个指定)

### -h --help

显示帮助信息
