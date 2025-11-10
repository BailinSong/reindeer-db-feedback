# 贡献指南

感谢你对 Reindeer DB 的关注！这个仓库专门用于收集用户反馈、bug 报告和功能建议。

## 📋 如何贡献

### 🐛 报告 Bug

1. 搜索 [已有 Issues](../../issues) 确保问题未被报告
2. 点击 [New Issue](../../issues/new/choose)
3. 选择 "Bug Report" 模板
4. 填写以下信息：
   - 清晰的 bug 描述
   - 详细的复现步骤
   - 预期行为和实际行为
   - 环境信息（版本、操作系统、编辑器等）
   - 错误日志（如有）
   - 截图（如适用）

### 💡 提出功能建议

1. 搜索 [已有 Issues](../../issues) 确保建议未被提出
2. 点击 [New Issue](../../issues/new/choose)
3. 选择 "Feature Request" 模板
4. 填写以下信息：
   - 功能描述
   - 使用场景
   - 期望的解决方案
   - 替代方案（如有考虑）
   - 优先级评估

### ❓ 提问

1. 先查阅 [文档](https://github.com/songbailin/Reindeer-DB/tree/main/docs)
2. 搜索 [已有 Issues](../../issues) 确保问题未被提问
3. 点击 [New Issue](../../issues/new/choose)
4. 选择 "Question" 模板
5. 提供详细的问题描述和环境信息

## 🏷️ Issue 标签说明

- 🐛 `bug` - 需要修复的问题
- ✨ `enhancement` - 功能增强或新功能
- 📝 `documentation` - 文档相关
- ❓ `question` - 使用问题或疑问
- 🔥 `priority: high` - 高优先级
- ⏰ `priority: medium` - 中优先级
- 🧊 `priority: low` - 低优先级
- 🎯 `good first issue` - 适合新手贡献者
- 🚫 `wontfix` - 不会修复
- ♻️ `duplicate` - 重复的 Issue
- ✅ `fixed` - 已修复
- 🚧 `in progress` - 处理中

## 📊 Issue 处理流程

1. **新提交** (New)
   - 我们会在 24-48 小时内回复
   - 初步评估问题

2. **确认** (Confirmed)
   - 验证问题或需求
   - 添加相应标签
   - 评估优先级

3. **处理中** (In Progress)
   - 开始修复 bug 或实现功能
   - 更新 Issue 状态

4. **已解决** (Resolved)
   - Bug 已修复或功能已实现
   - 在新版本中发布
   - 关闭 Issue

5. **已验证** (Verified)
   - 用户确认问题已解决
   - 添加 `fixed` 标签

## ✅ Issue 质量指南

### 好的 Bug 报告示例

```markdown
**Bug 描述**：
在连接 MySQL 数据库时，如果表名包含中文字符，查询结果显示乱码。

**复现步骤**：
1. 连接到 MySQL 数据库
2. 创建包含中文列名的表
3. 执行查询 `SELECT * FROM 用户表`
4. 查看结果面板

**预期行为**：
应该正确显示中文字符

**实际行为**：
显示为 `???` 或乱码

**环境信息**：
- Reindeer DB: v0.2.0
- VS Code: 1.85.0
- MySQL: 8.0.33
- macOS: 14.1

**错误日志**：
```
[Error] UnsupportedEncodingException: UTF-8
```

**截图**：
[附上截图]
```

### 好的功能建议示例

```markdown
**功能描述**：
支持导出查询结果为 CSV 文件

**使用场景**：
作为数据分析师，我经常需要将查询结果导出到 Excel 进行进一步分析。
目前只能手动复制粘贴，效率较低。

**期望的解决方案**：
1. 在查询结果面板添加"导出"按钮
2. 点击后弹出文件保存对话框
3. 支持 CSV 和 JSON 两种格式
4. 保持数据格式和编码正确

**替代方案**：
- 可以先实现右键菜单的导出功能
- 或者提供命令面板命令

**优先级**：中
```

## 🤝 行为准则

- **友善和尊重**：以友善和建设性的方式交流
- **清晰表达**：提供清晰、详细的信息
- **耐心等待**：我们会尽快回复，但可能需要一些时间
- **积极反馈**：问题解决后请确认并关闭 Issue

## 📞 联系方式

- **Issues**：[提交 Issue](../../issues/new/choose)
- **Discussions**：[参与讨论](https://github.com/songbailin/Reindeer-DB/discussions)
- **主仓库**：[Reindeer DB](https://github.com/songbailin/Reindeer-DB)

## 📄 许可证

通过提交 Issue，你同意你的贡献遵循 MIT 许可证。

---

**再次感谢你的贡献！** 🦌✨
