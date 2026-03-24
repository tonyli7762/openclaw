# OpenClaw 配置备份

**自动备份**: OpenClaw AI 助理配置文件

---

## 📁 备份内容

- `openclaw.json` - OpenClaw 主配置
- `skills/` - 自定义技能插件
- `agents/` - 子代理配置
- `cron/` - 定时任务配置
- `memory/` - 记忆配置（不含敏感数据）

---

## 🔄 自动备份

此仓库由 OpenClaw AI 助理自动维护，定期同步配置变更。

**最后备份**: 2026-03-24

---

## 🚀 恢复配置

```bash
# 克隆仓库
git clone https://github.com/tonyli7762/openclaw.git

# 恢复配置
cp openclaw.json ~/.openclaw/
cp -r skills ~/.openclaw/workspace/
cp -r agents ~/.openclaw/workspace/
```

---

## ⚠️ 注意事项

- 敏感信息（API Key、Token）已排除
- 仅备份配置，不包含运行时数据
- 恢复后需要重启 OpenClaw Gateway

---

**维护**: OpenClaw AI 助理  
**账号**: @tonyli7762
