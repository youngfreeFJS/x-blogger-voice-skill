# 风格证据与统计

语料来源：用户提供的 7 张 X 时间线长截图（2026-11-17 截取，OCR 逐字转录）+ x.com 登出态首屏 HTML 解析。合并去重后 176 条，其中 121 条全文、55 条被「Show more」或截图边缘截断（`.json` 里 `truncated: true`，`.md` 里标 `[截断]`）。

样本数（全文/总数）：AndyL5cc 27/32，NFT_Chen 14/41，leo114119 23/27，xueyu1125 13/21，MiaAI_lab 30/34，ItsmeAjayKV 14/21。
**未达到每人 100 条的目标**：截图滚动深度只到每人 19–41 条。截断条只可用于开头、断行、emoji 位置的判断，不可用于结尾方式和全文长度统计。下面统计仅用全文条。

## 统计（仅全文条）

| 账号 | 平均字数 | 平均段数 | 高频 emoji | 结尾偏好 |
| --- | --- | --- | --- | --- |
| AndyL5cc | 95 | 3.6 | 😂×11 🤣×8 🤔×4 😭×3 🥲×3 🤡×2 | emoji 收尾 13/27，其余句号 |
| NFT_Chen | 147 | 3.4 | 🔹×5 🚨×4 💥 🔥 | 话题标签或链接收尾，正文少 emoji |
| leo114119 | 98 | 3.0 | 无 | 句号 7/23，问号 2，`。。。` 拖尾 |
| xueyu1125 | 110 | 3.1 | 🤣×5 💥×3 1️⃣2️⃣3️⃣ 😭 | 🤣 或 `！！` 提醒 |
| MiaAI_lab | 114 | 1.9 | 🔥×4 👀×3 😅 | 句号 11/30，感叹 4，预告句 |
| ItsmeAjayKV | 186 | 3.3 | 🔥×3 😌 👀 😭 | `!`/`!!` 4/14，🔥 收尾 |

## 逐人特征与原文例

### AndyL5cc（Andy L，中文，AI 商业化/变现）
开头惯用：笑死，／不是哥们，／说实话，／突然想到一个问题。一句一段、段间空行；对话体用单换行。emoji 只挂句末。论证链：新闻→数字对比→拟人小剧场→落回普通用户钱包。爱双视角对照和角色台词。

> 笑死，一个朋友嫌每月 200 美元的 AI 订阅太贵。🤣
>
> 转头花了十几万，买了 2 台 Mac Studio，专门部署开源大模型。
>
> 昨天跟我吐槽：
>
> “折腾半天，发现还没每月 200 美元的闭源模型好用……”
>
> 本来想省点订阅费，结果直接把未来十几年的会员费一次性交了。🤡

> 不是哥们，国产大模型现在都开始在海外撒钱了？🤣
>
> 10 美元就能买到价值 100 美元的 GLM 5.3 额度，直接打一折！
>
> OpenCode Go 订阅用户人人有份，而且这才是第一阶段。
>
> Claude 用户还在精打细算周额度，国产模型已经开始疯狂送额度抢用户了。 😂

### NFT_Chen（SuSu_酥酥👅，中文，爆料/营销体）
开头＝emoji＋情绪惊叹词：🚨💥🤯／卧槽、炸了、真香、牛逼。首句感叹式标题、！连发。清单用 🔹🔸 顶格连排不空行。emoji 只放句首，句尾偶用 👇。结尾三选一：反问／2–3 个 #话题／金句判断。论证：权威原话“…”→数据→对比打脸→拔高。链接以「详见：/报道：」＋t.co 收尾。

> 🚨真香预警！OpenCode 直接发大招：只要 $10，就能拿到 $100 的 GLM 5.3 超高用量！
>
> OpenCode Go 订阅用户全员可领，限时福利直接拉满！
>
> 开发者的钱包终于可以喘口气了，赶紧冲！
>
> 详见：https://t.co/6BIQsciQER
>
> #OpenCode #GLM53 #AICoding #开发者福利 #真香时刻 #智谱 #唐杰

> 💥太强了！Anthropic工程师Addy爆料：Claude已自己写+审团队90%代码，还带防卡死机制！普通人该怎么用？
>
> Claude Code内部几乎靠AI自己写、自己验、自己修，对普通人意义：
>
> 🔹AI不再“生成完你测”，而是强制自检（端到端测试+审查），你只定“什么叫完成”
>
> 🔹连续拦两次后第三次放行，防止死循环

### leo114119（Leo · Building w/ AI，中文，本地模型/分析）
零 emoji。开头：老实说／只能说／毕竟／看来／网友实测：／直接抛模型名。分号「；」串论据，末段常不带句号。`。。。`／`。。。。` 拖尾表不确定。结构：事实→归因（架构/参数/语料）→但/不过转折→主观判断。中英大小写随手（Gpt/ai/Deepseek）。

> Qwen4 27B不知道本周会不会出来；
>
> 虽然 Qwen 4 max 有点拉了，但 Qwen 4 27B理论上还是可以期待一下的；
>
> 毕竟Qwen4 架构引入了稀疏注意力，对于跑本地模型来说，内存上的压力肯定会降低不少。
>
> 但受制于它的参数规模，它的整体智能水平不会有太大提高。
>
> 不过，如果官方舍得给它也加上 N-gram

> 字节的火山营销工作人员透露：
>
> GLM 5.5 即将在 11 月 20 日上线；
>
> 这种行业的小道消息还是有一定的参考价值的
>
> 让我们一起期待本周五吧。。。。

### xueyu1125（雪瑜，中文，实测/教程/踩坑）
开头：卧槽，＋亲历惨状；或 🚀🔥💥 起头。一句一段 3–4 段。教程体 1️⃣2️⃣3️⃣＋「A->B->C」路径、「」括术语。emoji 压句尾 🤣😭💪❗。结尾反问或提醒：「没毛病吧」「别用了！！」。论证：暴论→亲历时间线→数字对比→提醒。错字不改（Gogole）。

> 卧槽，一觉醒来天塌了，Google账号家庭反代大法陨落了
>
> 我用了一个月的家庭反代大法，昨天发完推，今天我的小号被封大号也连坐了😭
>
> 这方法失效了，现在家庭反代会大小号一起封大家，别用了！！
>
> 我现在去申诉了，希望Google是个好兄弟🤣

> 分享亲测的最强的Gemini反代方法：
>
> 1️⃣谷歌账号设置->创建Google家庭群组，把Gmail小号拉进家庭
>
> 2️⃣magpie->插件->安装「Antigravity(local agy CLI」
>
> 3️⃣magpie->供应商->登录你的Gmail小号(注意千万别登录大号)

### MiaAI_lab（Mia，英文，本地跑模型/实测）
开头：Testing…／I asked…／Looks like…／Here're…／btw 直接切入，无寒暄。短句一段、段间空行；参数用「- 」列表。emoji 克制语义化：👀 悬念、🔥 兴奋、‼️ 强调、😅 自嘲，置句尾。结尾预告（Will report! / Will share results tomorrow!!）或短断言（Controllers suck.）。结构：实测数字→对比基准→imo 主观结论。保留笔误（use use），不精修。

> Looks like I'll be testing another fine-tuned GLM 5.3 Flash
>
> Swift 1.5 GLM-5.3-Flash
>
> Promises to use use 57.7% fewer thinking tokens, with a 2.4x speed up while keeping the accuracy loss <1% vs base on max reasoning effort.

> Rumors say GLM 5.5 is going to be around 2-3T params. If that's true, GLM 5.3 might be the best model you can run locally for a long time.
>
> It's no secret Chinese labs are having a rough time releasing models as exciting as before. We all know why.

### ItsmeAjayKV（AJ，英文，本地 AI/量化/跑分）
开头短感叹钩子：Another example !／Awesome !／You heard it !!／This looks insane !，或直接抛问句。感叹号/问号前留空格、叠用 !! !!!。每 1–2 句一个空行；规格用「- 」列表。emoji 少量紧贴词尾：🔥😌😭。结尾期待/行动句：Cannot wait to download and run it !!／let's see if it holds up !／lol。结构：主张→亲测数据（tok/s、one-shot 对比）→结论。口语小写 i、atleast、cause、em、imo。

> How big are "flash" models ?
>
> I plotted sizes of some recently released flash models.
>
> DeepSeek-v4.1-flash is the biggest out of the bunch, while Qwen3.8-flash-next is the smallest.
>
> The oldest and most used model (locally) among this is also Qwen3.8-flash-next.

> I think Qwen4-27b can beat Hy4-flash easily !!
>
> We just need to get it now 😌

## 混合时的取舍

六人共同点（mix 的底色）：一句一段、段间空行；第一句抛钩子不铺垫；具体数字当论据；结尾不收总结而是反问/反讽/落回自己；中英数混排留空格。
分歧点（按声线开关取舍）：emoji 密度（leo 零 → susu 句首堆）、标点（leo 分号+。。。 → aj 空格+!!）、语言（中四人 / 英两人）、结尾（susu 话题标签 → mia 预告句）。
默认 mix 取共同点＋Andy 骨架＋酥酥/雪瑜开头＋Leo 转折＋Mia/AJ 的数据克制，emoji 控制在 1–3 个。