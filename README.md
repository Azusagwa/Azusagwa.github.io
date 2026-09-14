# 刘家浩的个人博客

这是我的个人静态博客，主要记录 AI Agent、RAG 应用开发、大模型工程化等内容。

- 站点地址：<https://Azusagwa.github.io/>
- GitHub：<https://github.com/Azusagwa>
- 邮箱：<2018106340@qq.com>

## 技术栈

- Python
- AI Agent / Agentic Workflow
- RAG / 知识库
- LLM 应用开发
- 静态页面：HTML、CSS、JavaScript

## 本地预览

仓库中的页面使用了以 `/` 开头的路径，推荐通过本地静态服务器预览，而不是直接双击 `index.html`。

在项目根目录执行：

```powershell
py -m http.server 8000
```

然后打开：

```text
http://127.0.0.1:8000/
```

## 部署

站点部署在 GitHub Pages 上，仓库使用 `main` 分支作为发布分支。

修改内容后执行：

```powershell
git add .
git commit -m "更新博客内容"
git push
```

推送完成后，GitHub Pages 会自动重新部署。
