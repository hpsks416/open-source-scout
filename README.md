# open-source-scout

检索 GitHub 等开源平台，找到匹配需求的现成项目，并提炼成含许可、维护度、适配度的对比清单。

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 需要找现成开源项目替代方案的开发者

## 目录结构

    open-source-scout/
    ├── SKILL.md    技能入口与工作流
    ├── agents\openai.yaml
    ├── references\platform-recipes.md
    ├── scripts\search_github.py

## 安装

    # GitHub
    git clone https://github.com/hpsks416/open-source-scout.git "$env:USERPROFILE\.dsh\skills\open-source-scout"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/open-source-scout.git "$env:USERPROFILE\.dsh\skills\open-source-scout"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
