<div align="center">

# 🤖 AI Prompt 智能提示词工具

**选择模型，获取精准提示词，让 AI 更懂你**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)]()

</div>

---

## ✨ 功能特性

| 功能 | 说明 |
|:---:|------|
| 🎯 **多模型支持** | ChatGPT、Claude、Gemini、Midjourney、Stable Diffusion |
| 🏷️ **分类筛选** | 写作、编程、营销、设计、分析、教育 |
| 🔍 **智能搜索** | 关键词实时搜索，毫秒级响应 |
| ⭐ **收藏功能** | 本地收藏，随时查阅 |
| 📋 **一键复制** | 快速复制提示词到剪贴板 |
| 📱 **响应式设计** | 完美适配桌面和移动端 |

## 💡 为什么选择这个项目

- ✅ **零依赖** — 纯前端实现，打开即用，无需安装任何环境
- ✅ **多模型覆盖** — 一个工具搞定 5 大主流 AI 模型的提示词
- ✅ **分类体系完善** — 6 大场景分类，快速定位你需要的提示词
- ✅ **开箱即用** — 内置精选提示词数据库，也可自由扩展

## 📸 效果预览

> 截图占位 — 欢迎贡献实际使用截图

| 桌面端 | 移动端 |
|:---:|:---:|
| ![桌面端截图](./screenshots/desktop.png) | ![移动端截图](./screenshots/mobile.png) |

## 🚀 快速开始

```bash
# 克隆项目
git clone https://github.com/GitHub-0219/AI-prompt.git
cd AI-prompt

# 直接打开即可使用（无需任何依赖）
open index.html        # macOS
# 或
xdg-open index.html    # Linux
# 或
start index.html       # Windows
```

> 💡 **提示**：也可以直接双击 `index.html` 文件在浏览器中打开。

## 📂 项目结构

```
AI-prompt/
├── index.html    # 🏠 主页面
├── style.css     # 🎨 样式文件
├── script.js     # ⚙️ 交互逻辑
└── data.js       # 📦 提示词数据库
```

## 🏷️ 提示词分类

| 分类 | 说明 | 适用场景 |
|:---:|------|---------|
| ✍️ 写作 | 文章、论文、PRD、文案 | 内容创作者、市场营销 |
| 💻 编程 | 代码审查、重构、全栈开发 | 开发者、技术团队 |
| 📢 营销 | 小红书、社交媒体、邮件营销 | 运营、品牌推广 |
| 🎨 设计 | AI 绘画、Logo、角色设计 | 设计师、创意工作者 |
| 📊 分析 | 数据分析、竞品分析、商业计划 | 产品经理、分析师 |
| 📚 教育 | 课程设计、面试准备 | 教师、求职者 |

## 📖 使用示例

### 添加自定义提示词

编辑 `data.js` 文件，按照以下格式添加：

```javascript
{
  id: 21,
  title: "提示词标题",
  model: "chatgpt",      // chatgpt / claude / gemini / midjourney / stable-diffusion
  category: "writing",   // writing / coding / marketing / design / analysis / education
  prompt: "提示词内容..."
}
```

### 支持的模型标识

| 模型 | 标识 | 典型用途 |
|------|------|---------|
| ChatGPT | `chatgpt` | 通用对话、写作、编程 |
| Claude | `claude` | 长文分析、代码生成 |
| Gemini | `gemini` | 多模态理解、搜索增强 |
| Midjourney | `midjourney` | AI 绘画、图像生成 |
| Stable Diffusion | `stable-diffusion` | 本地图像生成 |

## 🤝 贡献指南

欢迎贡献优质提示词！🎉

1. **Fork** 本仓库
2. 创建功能分支：`git checkout -b feature/add-prompts`
3. 在 `data.js` 中添加提示词（遵循格式规范）
4. 提交更改：`git commit -m 'feat: add new prompts for xxx'`
5. 推送到分支：`git push origin feature/add-prompts`
6. 创建 **Pull Request**

### 贡献规范

- ✅ 提示词内容原创或注明来源
- ✅ 每个提示词需有清晰的标题和分类
- ✅ 测试确认提示词在对应模型上效果良好
- ❌ 不提交重复或低质量内容

## 📄 License

[MIT License](./LICENSE) — 自由使用、修改和分发

---

<div align="center">

**⭐ 如果觉得有用，请给个 Star 支持一下！⭐**

</div>
