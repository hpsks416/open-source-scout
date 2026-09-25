> ⚠️ **本仓库已废弃**：内容已并入 [agent-deploy](https://github.com/hpsks416/agent-deploy) 的 skills/open-source-scout/ 子目录，请以 agent-deploy 为准。本仓库保留仅供历史归档。

# open-source-scout

检索 GitHub 等开源平台，找到匹配需求的现成项目，并提炼成含许可、维护度、适配度的对比清单。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

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

