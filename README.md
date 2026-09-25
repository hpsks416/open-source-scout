# open-source-scout

Search GitHub and other open-source platforms for existing projects that match a stated need, then distill alternatives into a comparison covering license, maintenance, and fit. Use for "find an open-source project / 有没有类似的开源项目 / open-source alternative" requests; not for general web search or non-software research.

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/open-source-scout.git "$env:USERPROFILE\.dsh\skills\open-source-scout"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/open-source-scout.git "$env:USERPROFILE\.dsh\skills\open-source-scout"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\open-source-scout" pull

## 目录结构

    open-source-scout/
    ├── SKILL.md    技能入口与工作流
    ├── agents\openai.yaml
    ├── references\platform-recipes.md
    ├── scripts\search_github.py

## 依赖

脚本以 Python 3 标准库为主，无第三方依赖（个别脚本如需额外依赖，见文件头注释）。

## License

MIT License. See [LICENSE](LICENSE).
