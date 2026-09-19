# 3.1.2 — 2026-09-19

新增 `16-产品相邻性与阻断分流_v1.md` 和 `related_supplement` 产品角色。推荐产品与主任务不匹配时，流程现在先完成五项相邻性判定：可证明的后续需求可进入 `ultra_tip` 或 `related_supplement`；无法证明时使用 `scoped_exclusion` 并继续主文章。只有用户明确强制不被实时证据支持的产品露出时，才进入 `blocked_waiting_for_user`。发布检查器验证相邻模块的结构化适配记录，并允许非强制推荐产品在官方复核后的范围内排除。

# 3.1.1 — 2026-09-15

在既有上游研究包与两个独立 Skill 的基础上，新增英文 How-to 的 `Quick Answer` / `Conclusion` 发布硬闸门。两者必须在 Markdown 与 Word 中作为独立 H2 出现，并保持 `Introduction → Quick Answer → … → FAQ → Conclusion → Sources` 的顺序。检查器识别 `English`、`en`、`en-US` 与 `US / English` 等常见语言字段形式。

# 3.1.0 — 2026-09-07

统一新文章/旧文路由；类型化产品与配图契约；跨平台 Python 发布检查；完整正文/表格文字/链接核对；阶段状态与渲染证据。

详细兼容说明见 RELEASE_NOTES.md。
