---
hide:
  - side_toc
---

# Wayland AI Docs

> 一个面向产品说明、接口文档与部署手册的终端风格文档站模板。

<div class="hero-grid" markdown="1">

<div class="hero-card" markdown="1">

## 为什么用它

- `mkdocs-terminal` 开箱即用
- 适合技术文档、CLI 手册、内部知识库
- 内置搜索，导航结构清晰
- 后续可直接接入 CI 自动发布

</div>

<div class="hero-card" markdown="1">

## 模板内置内容

- 首页展示区
- 快速开始分组
- API 文档占位结构
- 关于页与项目结构说明

</div>

</div>

## 启动方式

```bash
pip install -r requirements.txt
mkdocs serve
```

默认访问地址为 `http://127.0.0.1:8000`。

## 下一步建议

1. 替换 `mkdocs.yml` 中的站点名、仓库地址与导航。
2. 按业务模块扩展 `docs/guides/` 和 `docs/api/`。
3. 接入 GitHub Pages、Netlify 或自建静态托管。
