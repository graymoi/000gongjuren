# Trae 项目配置

## 项目说明
这是一个专门用于处理 Word 文档和图片的项目文件夹。

## 主要功能
- Word 文档处理（.docx）
- 图片处理和转换
- 投标文件整理
- 文档组合拼装
- 格式转换和批量处理

## 工作流程
1. 用户上传文件到项目文件夹
2. AI 分析文件内容和需求
3. 执行相应的处理任务
4. 输出成果文件

## 必备 Skills
- docx: Word 文档处理
- xlsx: Excel 表格处理
- pdf: PDF 文件处理
- image-processing: 图片处理（需要安装）

## 文件夹结构
```
d:\LMAI\000号员工\
├── .trae/
│   ├── rules/          # 项目规则
│   ├── hooks/          # 钩子脚本
│   ├── trae.md         # 项目配置
│   ├── agents.md       # 代理配置
│   ├── claude.md       # Claude 配置
│   └── claude.local.md # 本地配置
├── input/              # 输入文件
├── output/             # 输出文件
├── templates/          # 模板文件
└── temp/               # 临时文件
```
