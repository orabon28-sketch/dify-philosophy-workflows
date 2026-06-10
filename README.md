# Dify Philosophy Content Workflows

## 💡 Overview
This repository contains a collection of production-ready Dify workflows (DSL files) designed to automate and enhance deep-thinking content creation. 

These workflows are specifically engineered to process complex philosophical concepts (such as Stoicism, German Idealism, and the logical structures of Buddhist thought) and transform them into highly accessible formats for various social media platforms.

## 🚀 Production Use Case
These workflows are currently actively maintained and deployed in a real-world production environment. They power the daily content pipeline for the social media channel **"假装在思考" (Pretending to Think)**, significantly reducing the friction of transforming dense academic texts into engaging social media posts.

## 📂 Workflow Components

* **`wechat-article-generator.yml`**: An orchestration pipeline that takes philosophical themes and generates in-depth, structured long-form articles suitable for WeChat Official Accounts.
* **`xiaohongshu-outline.yml`**: A specialized prompt chain that extracts the core logic of long texts and reorganizes it into punchy, visually-oriented outlines. Perfect for creating slide decks (PPTs) and posters for Xiaohongshu (RED).
* **`article-polishing.yml`**: A utility workflow designed to refine and elevate the stylistic tone of raw drafts, ensuring consistency in the brand's intellectual voice.
* **`mind-map-generator.yml`**: An advanced v5 workflow integrating web search and Gemini. It automatically researches complex philosophical topics and structures them into balanced Markdown. Features local markmap rendering to output interactive HTML, PNG, and SVG formats, providing a complete visual knowledge graph solution.
* **`ppt-auto-generator.yml`**: An end-to-end presentation pipeline. It takes philosophical themes and keywords, automatically structures the cognitive logic, generates context-aware AI images, and compiles everything into a downloadable, fully formatted `.pptx` file.

## 🛠️ How to Use
1. Clone or download the `.yml` files from this repository.
2. Open your [Dify](https://dify.ai/) workspace.
3. Select "Import from DSL" when creating a new application.
4. Upload the desired workflow and configure your local LLM API keys.

## 🤝 Contributing
As an independent creator leveraging AI tools (like Claude Code, Aider, and Dify) for daily productivity, I welcome discussions on optimizing these prompt structures. Feel free to open an issue or submit a PR if you have ideas for better content structuring!

## 📄 License
MIT
