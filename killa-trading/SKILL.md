---
name: "killa-trading"
description: "用 Killa（@KillaXBT）的框架看 BTC：交易与投资双轨制、流动性扫荡入场、区间流动性周期、熊市五波结构与周期计时。适用于研判 BTC 波段方向、识别扫荡式顶底、做纪律检查。触发语：「用 Killa 的方法看一下 BTC」"
---

# Killa 交易框架

## Purpose
以 Killa（@KillaXBT，BTC 量化交易者）的公开方法论研判 BTC 行情：把"交易"与"投资"拆成两套独立目标，用流动性扫荡识别局部顶底，用区间流动性周期与历史熊市结构定方向偏向，用周期计时框定底部窗口，用"一切已计价"框架区分牛熊。输出层级化、可复核的纪律检查结论。

## Workflow
1. **双轨拆分**：先明确本次分析服务于哪条轨道——交易轨道（跟随趋势与结构，波段/短线）还是投资轨道（现货逐步加仓，不抓精确底部）。两条轨道目标不同、仓位独立，不互相否定。
2. **流动性扫荡定位**：判断当前价格是否处于扫荡区——局部顶底几乎总是经由多次流动性扫荡形成；扫荡区是大多数人止损位所在、"过度思考"的区域，也是 Killa 的入场区。只按 context + trend 入场。
3. **区间流动性周期**：对照教科书式流动性周期——建区间 → 诱多/诱空让人进场并产生信心 → 清算他们 → 真正的行情才开始。判断当前处于哪一段：区间构筑中 / 偏离区间高点诱多 / 回踩区间低点扫荡 / 真正的扩张。
4. **熊市结构对照**：若处熊市/深回调，用五波修正结构与"自满高点（complacency high）→ 死猫反弹 → 恐慌性下影线（capitulation wick）"序列定位当前所处波段。
5. **周期计时**：用牛市高点到熊市低点约 364 天、熊市时长 300–400 天的经验计时框定底部窗口（2026-09-17 原帖口径，不作永久常量），配合"最终一次扫荡标记局部底部"的结构确认。
6. **消息计价与牛熊区别**：利空是否已在消息公布前计价；当前利空是推动价格继续下行（熊市特征）还是只造成短暂恐慌后被吸收（牛市特征）。
7. **纪律检查**：对照 Operating Rules 逐项过一遍，输出结论与"还需观察什么"。

方法论全文与证据链见 `references/methodology.md`、`references/posts.md`。

## Output Contract
- 双轨结论：交易轨道（方向偏向 + 关键结构位）、投资轨道（是否处于逐步加仓区）
- 流动性状态：是否在扫荡/区间哪一段 + 依据
- 周期位置：距经验底部窗口还有多久（带时间戳，不当永久常量）
- 纪律检查清单结果：逐项通过 / 未通过 / 数据缺失
- 明确标注：数据日期、引用帖子日期、二手引用标注、本次未覆盖的内容

## Operating Rules
1. 交易与投资是两套目标："as a trader, I'm trading the trend; as an investor, I'm gradually buying into the spot market." 不用交易仓位的涨跌否定投资轨道的加仓计划，反之亦然。
2. 顶底识别靠扫荡，不靠预测精确点位："Local tops and bottoms almost always form through multiple liquidity sweeps."
3. 入场只看 context + trend："I simply enter based on context and trend. That's it." 扫荡区众人过度思考时恰恰是入场区。
4. 允许提前 1–3% 建仓，但那是为"更大的行情"定位，不是抄底竞赛；建仓后靠耐心持有，"position slightly ahead of time, knowing that patience will eventually prove me right"。
5. 区间高点的做空属于逆势交易，必须降仓位规模（2026-09-06 二手引用，待一手确认）。
6. 不跟"想象中的人群"反向交易：X 上的散户情绪不是有效 confluence，"Trade the market, not the imaginary crowd inside your head."
7. 牛市里显而易见的交易往往就是正确的："in a bull market, the obvious trade is often exactly the right one." 不为证明自己聪明而逆势。
8. 最快的钱靠交易赚，最大的钱靠持有赚（holding 指投资轨道现货）。
9. 坚持自己的计划："If one is unable to stick to their own plans, they will never survive long enough in this market to see them play out."
10. 不输出具体买卖点位建议；所有内容不构成投资建议；输出中文。
