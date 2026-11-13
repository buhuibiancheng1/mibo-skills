# 安装 Mibo Skill

从 https://github.com/buhuibiancheng1/mibo-skills 安装完整的 `skills/mibo/` 目录及附带文件。不要只复制 SKILL.md。

在宿主添加名为 `Mibo` 的 HTTP / Streamable HTTP 连接，地址为当前官网同域的 `/mcp`，自定义 Headers 留空；登录和授权由用户本人完成，无需安装客户端。

先只读调用 `mibo_list_projects` 与 `mibo_capabilities` 检查连接，不为检查连接创建项目、采集或生成。空项目列表不代表连接失败。

更新时重新导入技能包并刷新工具。卸载时移除技能与连接，可在账户安全中撤销授权。只读取随包附带的参考文件，缺失时说明具体文件，不能编造。
