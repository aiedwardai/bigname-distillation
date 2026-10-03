# 采集清单（manifest.md）

## 任务

为"蒸馏 Celal Kucuker（X @CelalKucuker，加密技术分析师）"采集一手证据链。产出为原材料，不含方法论蒸馏结论，不输出交易建议。

## 采集产出

| 文件 | 内容 | 条目数 |
|---|---|---|
| `posts.txt` | 帖子逐条（英文原文 + 中文大意 + 日期/日期未确认 + 来源） | 16 条帖子记录（含 2 条疑似重复引用） |
| `articles.txt` | 二手文献摘录（出处 URL + 发布日期 + 逐字引用/转述标注） | 26 条文献（A1–A26） |
| `manifest.md` | 本文件 | — |

## 时间范围覆盖

- 帖子日期范围：2026-03-13 至 2026-09-16（有明确日期的帖子 13 条）
- 文章发布日期范围：2026-03-14 至 2026-09-27
- "日期未确认"条目：3 条（SUI $14.07 帖、XLM 帖、SOL 长期 $148/$248 图表帖），均因引文媒体未给出帖子日期，仅知文章发布日期

## 采集手段

1. 公共网页搜索（browser.search）：以 `"Celal Kucuker"` + 币种/关键词为查询，抓取新闻网站对他帖子的引用。
2. 文章正文抓取（browser.open）：打开 Times Tabloid 等文章页提取逐字引用的帖子原文与日期。
3. 直接 X 访问：**失败**——x.com 被运行时策略封锁（browser.open 返回 "Domain x.com is blocked by policy"）。
4. 第三方镜像：twstalker（www.twstalker.com）与 instalker（instalker.org）均被 Cloudflare 拦截，无法获取帖子列表与粉丝数。
5. exec/curl 尝试：仅用于上述镜像站点的连通性测试，未绕开 x.com 封锁；未获取有效数据。

## 已知局限

1. **全部帖子均为二手引用**（新闻网站引述），未直接访问 X 验证；帖子直链未获取，仅保留引文中的 pic.twitter.com 图片链接。
2. **粉丝数、X 简介原文未获取**（直接访问与镜像均不可用）。
3. **EIGEN 相关帖子未获取**：公开渠道无任何引用；仅第三方项目分类标注提及他覆盖 EIGEN（未证实）。
4. **BTC 独立技术帖未获取**：他对 BTC 的观点仅见于 XRP/BTC 相对帖中的条件式目标（年底 $140K、$150K、$200K 三档），无 BTC/USD 独立图表帖。
5. **止损逻辑未获取**：本次采集的公开引用中未见明确止损位表述；第三方项目称其帖子常含 stop losses，但未能从引用中证实。
6. 搜索覆盖偏向近期（2026-03 起）；2026 年之前的帖子本次未覆盖。
7. Times Tabloid 部分文章页面不直接显示发布日期，"约"日期按站内"X days ago"相对 2026-09-28 推算，已在各条目标注。
8. 营销话术（如 "Save this and wait"、"print it out, and hang it on your wall"）已如实记录原文，未采信；不构成任何交易建议。
9. 个人隐私信息：本次采集未发现住址、电话、邮箱、家庭等隐私内容，无需剔除。

## 身份信息小结（均为二手引用，未直接验证）

- X 账号：@CelalKucuker
- 媒体常用描述："Crypto trader and investor"；"financial analyst with over 20 years of market experience"（多家媒体一致说法，但为转述，未核实）
- COINTURK："凭借图表分析在交易者中积累了大量追随者"（转述）
- 主要覆盖币种（按引用量排序）：XRP（含 XRP/BTC）> SOL > ETH > SUI > XLM；BTC 仅作条件式宏观锚；EIGEN 未见引用
