<h1 align="center">xiabai2008 · 柒迷狄依</h1>

<p align="center"><b>网络空间安全专业在读 · 安全工具开发者</b></p>

<p align="center">
  做垂直场景的安全工具：检测要准，工程要实，AI 要用在刀刃上。<br/>
  所有发布自带完整 CI / 测试 / 供应链校验；坚持三态判定，拒绝误报。
</p>

---

## 精选项目

<table>
<tr>
<td width="50%" valign="top">

### [ruoyi-scan](https://github.com/xiabai2008/ruoyi-scan)

若依（RuoYi）专项漏洞扫描器

- 插件化架构 · 52 个 POC · 三态判定
- WAF 绕过 · 漏洞利用链 · nuclei 兼容
- AI 生成 POC（LLM 自验证回灌）
- PyPI 一键安装：`pip install ruoyi-scan`
- ![PyPI](https://img.shields.io/pypi/v/ruoyi-scan?style=flat&label=PyPI)

</td>
<td width="50%" valign="top">

### [rayscan](https://github.com/xiabai2008/rayscan)

OA / 国产中间件专项 Web 检测器

- 12 种 OA 系统专项 · 8 种 SQLi + 6 种 XSS
- 规则级证据 · 低误报 · 376 个自动化测试
- Nuclei 12.5 万模板兜底 · MCP Server 接入 AI 客户端

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [poxiao](https://github.com/xiabai2008/poxiao)

SRC 安全工具链

- 先识别技术栈，再匹配 CVE（257 条指纹）
- 三层降噪，消除假阳性

</td>
<td width="50%" valign="top">

### [chameleon](https://github.com/xiabai2008/chameleon)

AI Agent 反爬爬虫

- 6 级反爬自动升级 · 三引擎架构
- MCP Server + REST + CLI + SDK 四形态
- 229 个自动化测试 · mypy strict

</td>
</tr>
</table>

## 工程原则

- **三态判定**：网络异常永远返回 UNKNOWN，绝不冒充 SAFE——误报是扫描器的原罪
- **冒烟门禁**：每次发布先把产物装进干净环境验证，装不上就发不出去
- **供应链安全**：SHA256 校验 + Ed25519 签名 + OIDC 免凭证发布
- **AI 落地**：AI 负责 POC 生成与误报复核，判定永远留给确定性规则

## 技术栈

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

## GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=xiabai2008&show_icons=true&hide_border=true&count_private=true" alt="stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xiabai2008&layout=compact&hide_border=true&langs_count=8" alt="langs" />
</p>

---

<p align="center">
  <a href="mailto:1185259706@qq.com">1185259706@qq.com</a> · 欢迎交流安全工具开发与若依/OA 生态漏洞研究
</p>
