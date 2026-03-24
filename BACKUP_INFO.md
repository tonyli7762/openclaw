# OpenClaw 配置备份说明

**备份时间**: 2026-03-24 11:20 (北京时间)  
**备份工具**: GitHub Integration Skill

---

## 📦 备份内容

### 1. 主配置
- `openclaw.json` - OpenClaw 主配置文件

### 2. 技能插件（53 个）
- find-skills
- clawhub-cli
- tavily-web-search
- summarize
- marketingskills (26 个技能)
- baoyu-skills (15 个技能)
- github-integration
- skill-creator
- 原有技能 (10 个)

### 3. 子代理配置
- 风口情报官
- 总控助理
- 自媒体运营总监
- 编程主管
- 财务总监

### 4. 定时任务
- cron.json - Cron 任务配置
- jobs.json - 详细任务列表

---

## 🔒 排除内容

以下敏感信息**不会**备份：
- API Keys
- Tokens
- 密码
- 个人隐私数据

---

## 📊 备份统计

| 类型 | 数量 | 大小 |
|------|------|------|
| 配置文件 | 4 个 | ~50KB |
| 技能插件 | 53 个 | ~5MB |
| 子代理配置 | 5 个 | ~100KB |
| **总计** | **62 个文件** | **~5.15MB** |

---

**备份人**: OpenClaw AI 助理  
**GitHub**: @tonyli7762
