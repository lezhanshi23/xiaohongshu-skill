# June 2026 XHS Data Calibration

Source workbook: `C:/Users/zhanshi/Desktop/台球数据/其他/xhs/截至0630笔记列表明细表 (3).xlsx`

Analyzed rows: 22 published 小红书 notes from June 2026. Columns include title, first publish time, format, body, exposure, views, cover CTR, likes, comments, saves, follows, shares, average watch time, and danmaku.

## Baseline Metrics

- Median exposure: 2,137.
- Median views: 306.5.
- Median cover CTR: 0.143.
- Median total interaction: 25.5, using likes + comments + saves + follows + shares.
- Median saves: 8.5.
- Top quartile exposure starts around 4,502.
- The data is heavily skewed by one very large winner, so use bands and relative judgment rather than exact predictions.

## Strongest Posts

1. `Boss直聘是可以傻瓜式教你赚钱的地方`
   - Exposure 535,343, views 88,684, CTR 0.166, interactions 9,321, saves 4,054, follows 354, shares 931.
   - This is the strongest reference pattern: a familiar platform plus "傻瓜式" plus money desire plus the promise that the platform already exposes demand.

2. `Boss直聘是傻瓜式教你赚钱的地方`
   - Exposure 47,711, views 8,806, CTR 0.186, interactions 1,115, saves 507.
   - Same core pattern as the winner. Treat this as a repeat signal, not a one-off fluke.

3. `裸辞2年，年入百万💰我的真实经历❗`
   - Exposure 4,767, views 792, CTR 0.171, interactions 71, saves 34.
   - Personal transformation plus extreme outcome works when it has real-life proof.

4. `赚100w和赚1块钱的本质是一模一样的`
   - Exposure 3,708, views 501, CTR 0.170, interactions 61, saves 27.
   - Strong abstraction with a sharp contrast can work when the benefit is huge and simple.

5. `豆包是可以傻瓜式教你赚钱的地方`
   - Exposure 1,977, views 315, CTR 0.149, interactions 61, saves 33.
   - Not a high exposure winner, but save rate was very strong, suggesting "tool/platform + easy money logic" drives collection.

## Weak or Risky Signals

- Generic "红利" alone was weak: `未来3年仍有红利的 10个赛道` only had 604 exposure despite a high CTR of 0.182.
- Unfamiliar platform plus broad claim was weak: `Fable5是普通人赚钱的最大红利` had 642 exposure and low CTR 0.064.
- Pure framework titles can underperform if the user cannot instantly feel the payoff: `年入百万绕不过去的一关：极简化` had 1,744 exposure.
- Tutorial/list signals are risky or soft: `如何`, `10个赛道`, `SOP`, `实操版`, `做对这3题`, `手把手` can make content feel like a course or checklist.
- The same-day June 30 post had 0 exposure in the export. Treat it as immature data, not proof that the title pattern failed.

## Added Feedback: Business Model Postmortem

The draft titled `年入百万靠的不是努力，而是选对商业模式` was previously scored as `普通` to `可发`, but the actual result was about 300 exposure and 40 reads. That is a read rate of roughly 13.3%, close to the June median cover CTR/read-rate proxy of 14.3%.

Do not diagnose this type of result as simply "封面差" or "标题点不动". When read rate is near median but exposure is very low, the more likely issue is that the note did not pass the next traffic-pool test after the first small distribution.

Specific lessons from this miss:

- `商业模式` is a correct concept but a weak 小红书 click doorway. It feels like a lesson, not an immediate life/business conflict.
- A "备忘录" cover can leak the answer too early. If it lists `非标 / 高客单 / 个人IP`, users may feel they already got the framework and do not need to click or continue.
- `第一/第二/第三`, `三个条件`, `教大家一个简单计算方法`, and `成功率自动提升30%` shift the note from观点 to创业教程.
- Dense proof numbers such as `50w工作`, `1300w阅读`, `一天5w`, `60w学费`, and `年入50w` create credibility, but when stacked together they can feel like income proof plus instruction.
- The body also needs a new takeaway. `非标 / 高客单 / 个人IP` is directionally right, but if presented as three known conditions, it can feel like old entrepreneurship advice. The note needs a fresher mechanism, such as "为什么普通人必须避开标准化市场" or "为什么流量大反而可能困住一个人的收入".
- If a note has near-median read rate but only a few hundred exposures, diagnose "首轮后没有继续推" before rewriting only the cover.

## Practical Lessons

- Strongest pattern: `熟悉平台/工具/场景 + 傻瓜式 + 赚钱/年入百万欲望 + 反常识解释`.
- "年入百万", "红利", "改命", "暴利", and "白手起家" are amplifiers, not the premise. They need a concrete cognitive doorway.
- "Boss直聘" worked because it is a familiar place where demand and willingness to pay are visible. Future titles should hunt for similar "需求已经摆出来" platforms.
- Simple operation beats detailed operation. The user should feel "I can understand this now", not "I am being assigned homework".
- Use personal cases to create live-human credibility, but keep the middle as商业认知, not exact execution.
- The body must provide 获得感. Prefer a new, repeatable judgment over familiar advice. A reader should leave with one sentence they did not already know, such as "流量不是生意，只有能把单位时间卖贵的流量才是生意".
- To lower risk, replace "教你赚钱" with phrases such as "看懂赚钱逻辑", "看懂商业需求", "看懂生意线索", "看懂普通人改命的入口" when the body is close to tutorial territory.
- When actual data contradicts a preflight score, recalibrate the rule. The observed result outranks the prior prediction.

## Added Feedback: Viral Route Taxonomy

The user now frames 小红书爆款 as three viable routes plus one anti-route:

1. `日常事物 + 反差独特商业认知`
   - Writing difficulty: hard.
   - Why it works: familiar object lowers entry cost, surprising commercial interpretation creates curiosity and saves.
   - Example shape: "别人把 Boss 直聘当招聘软件，我把它当需求数据库."
   - Score highly only if the business insight is genuinely non-obvious.

2. `赚钱方面的单纯信息差`
   - Writing difficulty: easy.
   - Why it works: direct desire and concrete novelty.
   - Risk: easily becomes money tutorial or project promotion. Keep it as information discovery, demand observation, or认知差, not exact execution.

3. `以小博大 / 快速见效`
   - Writing difficulty: medium.
   - Signals include `3分钟`, `24小时`, `一条笔记`, `一个动作`, `小改动`, `马上见效`.
   - Why it works: tiny input plus large outcome produces curiosity.
   - Risk: fake certainty and platform-sensitive promise. Prefer "看懂/验证/发现" over "保证/速赚/照做".

Anti-route:

4. `简单认知`
   - Examples: `年入百万，先学定价`, `创业要高客单`, `要做个人IP`, `选择大于努力`.
   - Why it fails: no contrast, no curiosity, no new information. Correct but not click-worthy.
   - Use this as a cap/penalty unless the draft adds a fresh mechanism or surprising doorway.
