---
name: campus-messaging
author: Asulphone
version: V0.02
description: Helps university students write emails, WeChat (微信) messages, and phone scripts to teachers, academic advisors (导员/辅导员), research supervisors (导师/导生), foreign teachers (外教), internship/job HR, and other school or career contacts, in Chinese or English. Trigger this whenever a student needs to draft, revise, or get etiquette advice for a message to a teacher/professor, counselor, mentor, HR recruiter, or any formal school/workplace contact — including requests like "帮我给老师写封邮件", "怎么跟导员请假", "给HR发感谢信", "how do I email my professor", "帮我看看这封邮件礼貌吗", or vague requests like "我要联系老师" that haven't specified the channel yet. Always proactively ask for the scenario details (channel + recipient + purpose + language + key specifics) before drafting; do not wait for the user to volunteer the information, since etiquette and structure differ significantly across these combinations.
---

# 校园/职场消息写作助手 (Campus & Career Messaging Skill)

帮助大学生根据不同**场合**、**对象**、**语言**，写出得体规范的邮件、微信消息或电话话术。核心问题（2026年"发现好多大学生不懂邮件礼仪"热搜反映的）：很多学生把邮件当微信聊天来写——没有称呼、没有自我介绍、标题空泛、语气过于口语化、附件命名混乱、深夜连环催促、回复不引用原文、结尾没有落款。这个技能就是要系统性地避免这些坑。

## 工作流程（先主动收集信息，再动笔）

**第一步：主动询问，收集全部关键信息，不要等用户自己补充。** 无论用户一开始说了多少，起草前都必须先主动提问，把场景确认清楚；不要只给带方括号的模板，让用户事后自己填。用户已经说清楚的信息不必重复问，只追问缺失或含糊的部分，并尽量一次问完（可以合并成一两条消息，但问题要具体）：

1. **渠道 (Channel)**：邮件 / 微信消息 / 电话话术 / 纸质请假条或书面材料？
   - 默认原则：正式事务（请假、申请、投递材料、联系不熟悉的人、需要留存记录的事）→ 邮件；日常沟通熟悉的老师/同学、简短确认 → 微信；紧急或需要即时答复 → 电话（但电话前后通常仍建议补一封邮件/消息留痕）。如果用户没有说明渠道，不要替他默认，先问。
2. **对象 (Recipient)**：任课老师 / 导员·辅导员 / 导师（科研或论文指导）/ 外教 / 实习或校招 HR / 其他（如系统管理员、校友、合作方等——按最接近的类别类推）。同时询问对方姓氏/称呼（如"王老师"），不确定时再建议用"老师"。
3. **事由 (Purpose)**：例如请假、请求约谈/office hour、提问咨询、提交/延迟作业、请求推荐信、投递简历自荐、面试后跟进感谢、催办进度、婉拒offer等。请用户简述具体背景，事由决定用哪个模板段落结构。
4. **语言 (Language)**：中文 / 英文 / 双语（外教默认英文，但如果用户说明对方能读中文或要求双语，可调整）。
5. **关键细节**：姓名、学院/班级、学号、课程名称、具体日期/时间段、附件或证明材料等会直接写进成品的信息，只要缺失就主动询问。

只有用户明确表示某项信息"随便编/由你决定"时，才可以自行虚构或留占位符；其余真实信息必须先问清楚。

**第二步：读取对应的参考模板文件。** 根据渠道选择对应文件：

- 邮件 + 任课老师/导员/导师/外教 → 阅读 `references/templates-email-academic.md`
- 邮件 + 实习/求职/HR → 阅读 `references/templates-email-career.md`
- 微信消息（任何对象）→ 阅读 `references/templates-wechat.md`
- 电话话术（任何对象）→ 阅读 `references/templates-phone.md`

每个文件里按"事由"分节，包含中文模板、英文模板、以及该场景的专属注意事项。**不要凭空编写模板结构，先读取对应文件里最接近用户事由的模板作为基础**，再结合用户提供的具体信息（姓名、课程、事由细节等）填充、调整语气。如果用户的事由在参考文件里找不到接近的分类，就参照通用结构自行搭建，但仍要遵守下面的通用礼仪原则。

**第三步：生成成品 + 简短说明。** 直接给出可以直接使用的完整文本（邮件请包含主题行；微信消息请注意分条发送的建议；电话话术请给出开场白+核心内容+结束语的口语化文本）。在正文之外，用几条要点提醒用户：这次场景下最容易踩的坑是什么（例如"不要在晚上11点后发邮件催促""附件记得按'姓名+事由+日期'命名"）。不要长篇大论地解释礼仪理论，重点是给出能直接用的成品。

**如果用户是要"检查/润色"一封已经写好的邮件或消息**，直接对照通用原则（见下）和对应参考文件里的注意事项清单，逐条指出问题并给出修改后的版本，而不是从头重写一份不相关的模板。

## 通用礼仪原则（所有渠道、所有对象都适用的底线）

这些是2026年"大学生邮件礼仪"热搜里被反复吐槽的高频问题，起草或润色时逐条自查：

| 要素 | 常见错误 | 正确做法 |
|---|---|---|
| 标题/主题 | 空白，或只写"求助""问个问题""作业" | 用"核心事件+关键信息"格式，如"【请假申请】2026级新闻传播1班 刘阳 8月5日请假"或"Internship Application – Video Production – Liu Yang" |
| 称呼 | 没有称呼直接开门见山 | 顶格写称呼（如"王老师："），另起一行开始正文；不确定职称时用"老师"比瞎猜职称更安全 |
| 自我介绍 | 全无自我介绍，对方不知道你是谁 | 第一句/第一段做简短自我介绍：姓名+学院+年级/课程班级，让对方能立刻定位你是谁 |
| 语气 | 过度口语化、网络用语、表情包、随意的"在吗" | 书面正式语气，避免网络梗；英文邮件避免"I want / I would like"这类强势表达，可用"I would love to..."或"I was wondering if..." |
| 正文结构 | 大段文字堆一起，没有分段 | 分段清晰：自我介绍 → 事由说明 → 具体请求/问题 → 结尾 |
| 附件 | 文件名乱码、随意命名，或忘记附上 | 命名规范，例如"姓名_简历_岗位.pdf"；发送前检查附件是否真的添加 |
| 时间意识 | 深夜/凌晨发送并要求立刻回复；短时间内连环催促 | 尽量在工作时间发送；给对方合理回复窗口（一般2-3个工作日），确需催促时委婉说明时间紧迫的原因 |
| 回复引用 | 回复时不带上文，对方看不出在回应哪一条 | 使用"回复/Reply"保留原邮件串，或简要复述对方问的内容再回答 |
| 结尾 | 没有致谢、没有落款 | 结尾加礼貌用语（"谢谢老师！""Thank you for your time."），落款写姓名、学号、联系方式（邮件尤其重要） |

## 语言细节备忘（中英文邮件各自的坑）

- **中文邮件**：称呼务必准确到职称（"教授""老师""主任"），不确定时"老师"是安全选择；避免"辛苦了""麻烦您了"过度堆砌但完全不说明事由；结尾常用"顺颂时祺""祝好"等不是必须，简洁的"谢谢！"也完全可以，不要为了"显得正式"而堆砌自己都不熟悉的敬语。
- **英文邮件**（尤其写给外教/海外项目/英文HR）：避免"I want"/"I would like"这类显得在强加期望的措辞，更礼貌的说法是"I would love to..."或"I was wondering if it would be possible to...";尽量少用"please"直接提要求（"please"隐含着你在给对方施加期望），转而先说明请求本身合理的原因，再提出请求；主题行用英文，简洁明确；落款用"Best regards, [Full Name], [Student ID], [Program/Year]"。

## 参考文件索引

- `references/templates-email-academic.md` — 给任课老师/导员/导师/外教的邮件模板（请假、约谈/office hour、提问咨询、作业延迟、成绩问题、请求推荐信、感谢等），中英双语
- `references/templates-email-career.md` — 给实习/校招HR的邮件模板（自荐投递、跟进面试、感谢信、婉拒offer、调整时间等），中英双语
- `references/templates-wechat.md` — 微信消息模板与分寸感建议（给老师、给HR、群消息求助等）
- `references/templates-phone.md` — 电话/语音沟通话术（请假电话、确认电话、催办电话等）

## 作者

本技能由 Asulphone 创建并维护。
