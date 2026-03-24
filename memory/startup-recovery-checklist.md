# 启动恢复检查清单

**每次会话开始时自动执行**（尤其是重启/崩溃后）

---

## ✅ 必做检查（每次启动）

- [ ] 读取 `SOUL.md` - 确认角色和身份
- [ ] 读取 `USER.md` - 确认用户信息
- [ ] 读取 `memory/YYYY-MM-DD.md` - 今天和昨天的日志
- [ ] 读取 `MEMORY.md` - 长期记忆（仅限主会话）
- [ ] 读取 `HEARTBEAT.md` - 检查待办任务
- [ ] 读取 `TOOLS.md` - 本地工具和配置笔记

## ✅ 向量记忆召回

```
memory_recall(query="最近配置变更", limit=3)
memory_recall(query="待办任务", limit=3)
memory_recall(query="对话上下文", limit=5)
```

## ✅ 检查未完成的任务

- [ ] 查看 `memory/YYYY-MM-DD.md` 中的 `[ ]` 未勾选项
- [ ] 查看 `.learnings/` 中的 pending 项目
- [ ] 查看是否有定时任务到期（如今晚 18:00 的检测任务）

## ✅ 检查错误日志

- [ ] `.learnings/ERRORS.md` - 是否有导致崩溃的错误
- [ ] 检查是否有需要修复的问题

---

## 恢复后告诉用户

模板：
> "我刚重启，已恢复记忆：
> - 正在进行：XXX
> - 待办任务：XXX
> - 最近配置：XXX"

---

**最后更新**: 2026-03-18 05:36
