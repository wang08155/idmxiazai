# AGENTS.md

## 项目概览
IDM下载器官网 - 提供Internet Download Manager中文版免费下载的单页网站，通过网盘链接分发安装包。

## 技术栈
- 原生HTML + CSS + JavaScript
- 无构建步骤，静态文件服务
- Python SimpleHTTPServer 提供开发服务

## 项目结构
```
/workspace/projects/
├── index.html          # 主页面（含完整SEO和结构化数据）
├── styles/
│   └── main.css        # 全局样式
├── .coze               # 部署配置
└── AGENTS.md           # 本文件
```

## 构建和运行
- 开发：`python -m http.server 5000 --bind 0.0.0.0`
- 无构建步骤，修改文件后刷新即可

## 代码风格
- HTML5语义化标签
- CSS自定义属性管理设计Token
- 原生JavaScript，无框架依赖
- 中文注释

## SEO要点
- title/description/keywords已覆盖IDM相关30+关键词
- JSON-LD结构化数据（SoftwareApplication + FAQPage + BreadcrumbList）
- FAQ内容覆盖百度下拉词
- 百度自动推送脚本已集成

## 注意事项
- 网盘下载链接为占位符(#download)，需替换为真实网盘链接
- 百度站长验证码需替换
- canonical URL需替换为实际域名
