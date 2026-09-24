# 刺猬星球 Skill

AI 图片与视频提示词 Skill，当前版本 **v1.0**。

## 安装

在 PowerShell 中运行：

```powershell
git clone https://github.com/1M-AIstudio/ciwei-xingqiu.git "$env:USERPROFILE\.codex\skills\ciwei-xingqiu"
```

重启 Codex 后，可直接说：

```text
使用刺猬星球skill，帮我写……
```

## 更新

```powershell
git -C "$env:USERPROFILE\.codex\skills\ciwei-xingqiu" pull --ff-only
```

更新只拉取变更，不需要重复安装。执行后重启 Codex 或新建任务即可加载最新版。

