# AI Prompt 智能提示词工具

> 🤖 选择模型，获取精准提示词，让 AI 更懂你

## 功能特性

- 🎯 **多模型支持** — ChatGPT、Claude、Gemini、Midjourney、Stable Diffusion
- 🏷️ **分类筛选** — 写作、编程、营销、设计、分析、教育
- 🔍 **智能搜索** — 关键词实时搜索
- ⭐ **收藏功能** — 本地收藏，随时查阅
- 📋 **一键复制** — 快速复制提示词到剪贴板
- 📱 **响应式设计** — 完美适配桌面和移动端

## 快速开始

```bash
# 直接打开 index.html 即可使用
cd ai-prompts-search
open index.html
```

无需安装任何依赖，纯前端实现。

## 项目结构

```
ai-prompts-search/
├── index.html    # 主页面
├── style.css     # 样式文件
├── script.js     # 交互逻辑
└── data.js       # 提示词数据库
```

## 提示词分类

| 分类 | 说明 |
|------|------|
| ✍️ 写作 | 文章、论文、PRD、文案 |
| 💻 编程 | 代码审查、重构、全栈开发 |
| 📢 营销 | 小红书、社交媒体、邮件营销 |
| 🎨 设计 | AI绘画、Logo、角色设计 |
| 📊 分析 | 数据分析、竞品分析、商业计划 |
| 📚 教育 | 课程设计、面试准备 |

## 自定义提示词

编辑 `data.js` 文件，按照以下格式添加：

```javascript
{
  id: 21,
  title: "提示词标题",
  model: "chatgpt",  // chatgpt/claude/gemini/midjourney/stable-diffusion
  category: "writing",  // writing/coding/marketing/design/analysis/education
  prompt: "提示词内容..."
}
```

## License

MIT
