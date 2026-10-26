# Coding Plan · 有依据地选择

与[交互式网站](https://codingplan.91786767.xyz)使用同一份 v2 快照。

更新时间：2026-10-26T12:45:27.176Z · 数据版本：`374b10d92d3837eb1eb4331e8c2bfd4525c4ab26e8fbf590feccd457a1fe1df1`

## 推荐结论

质量门槛优先；内部权重：编程能力 40 / 稳定性 30 / 响应体验 15 / 同口径成本 15。优惠幅度和模型数量不加分。

当前证据不足，暂无通过质量门槛的主推荐。不按低价或历史大额度补位。

## 套餐比较

| 平台 / 套餐 | 结论 | 原币月费 | 折算元/月 | 主要模型 | 说明 |
| --- | --- | --- | --- | --- | --- |
| OpenAI / ChatGPT Plus | 条件推荐 | USD 20 | 133.3952 | GPT-6.1 Sol | 条件推荐：适合需要多步骤编码与 Codex 工具链的用户；近期存在已解决的降级事件，额度随任务变化，不承诺连续高强度使用。 |
| OpenCode / OpenCode Go | 条件推荐 | USD 10 | 66.6976 | GLM 5.3 | 条件推荐：适合需要开放模型接入的用户；官方近期记录了 Go 池错误与慢响应，关键工作建议保留备用渠道。 |
| OpenCode / OpenCode Go Plus | 条件推荐 | USD 40 | 266.7904 | GLM 5.3 | 条件推荐：适合需要开放模型接入的用户；官方近期记录了 Go 池错误与慢响应，关键工作建议保留备用渠道。 |
| 字节方舟 / Lite | 待核验 | CNY 40 | 40 | 待核验 | 历史额度缺少原始计算依据；旧记录含慢速劝退备注，先列待核验。社区个案不能直接推导故障率。 |
| 字节方舟 / Pro | 待核验 | CNY 200 | 200 | 待核验 | 历史额度缺少原始计算依据；旧记录含慢速劝退备注，先列待核验。社区个案不能直接推导故障率。 |
| Claude / Max 20× | 待核验 | USD 200 | 1333.952 | 待核验 | 多产品共享使用额度，公开相对倍数不等于月 token；近期状态记录包含已解决的模型错误。 |
| Claude / Max 5× | 待核验 | USD 100 | 666.976 | 待核验 | 多产品共享使用额度，公开相对倍数不等于月 token；近期状态记录包含已解决的模型错误。 |
| Claude / Pro | 待核验 | USD 20 | 133.3952 | 待核验 | 多产品共享使用额度，公开相对倍数不等于月 token；近期状态记录包含已解决的模型错误。 |
| CommandCode / CommandCode GOAT | 待核验 | USD 10 | 66.6976 | 待核验 | 每月请求数依赖厂商定义的典型请求；另有 processing fee，不能只比较订阅底价。 |
| GitHub Copilot / Max | 待核验 | USD 100 | 666.976 | 待核验 | 按当前 AI credits 计费规则核对，不将旧 premium requests 当作当前余额。 |
| GitHub Copilot / Pro | 待核验 | USD 10 | 66.6976 | 待核验 | 按当前 AI credits 计费规则核对，不将旧 premium requests 当作当前余额。 |
| GitHub Copilot / Pro+ | 待核验 | USD 39 | 260.1206 | 待核验 | 按当前 AI credits 计费规则核对，不将旧 premium requests 当作当前余额。 |
| Cursor / Pro | 待核验 | USD 20 | 133.3952 | 待核验 | Pro、Pro+、旧 Ultra 属于 legacy；当前 X Subscription 共享 Grok/Cursor 周池，第三方模型需另付费。 |
| Cursor / Pro+ | 待核验 | USD 60 | 400.1856 | 待核验 | Pro、Pro+、旧 Ultra 属于 legacy；当前 X Subscription 共享 Grok/Cursor 周池，第三方模型需另付费。 |
| Cursor / Ultra | 待核验 | USD 200 | 1333.952 | 待核验 | Pro、Pro+、旧 Ultra 属于 legacy；当前 X Subscription 共享 Grok/Cursor 周池，第三方模型需另付费。 |
| Devin（原 Windsurf） / Max | 待核验 | USD 200 | 1333.952 | 待核验 | 云端任务与桌面模型额度的计费单位不同，应分别核对。 |
| Devin（原 Windsurf） / Pro | 待核验 | USD 20 | 133.3952 | 待核验 | 云端任务与桌面模型额度的计费单位不同，应分别核对。 |
| Gemini Code Assist / Enterprise | 待核验 | USD 54 | 360.167 | 待核验 | 区分个人、Standard 与 Enterprise，按席位或承诺期限的价格不可混用。 |
| Gemini Code Assist / Standard | 待核验 | USD 22.8 | 152.0705 | 待核验 | 区分个人、Standard 与 Enterprise，按席位或承诺期限的价格不可混用。 |
| Grok（xAI） / SuperGrok | 待核验 | USD 30 | 200.0928 | 待核验 | 当前 X Subscription 将 Grok、Cursor 与 API 使用纳入共享规则；第三方模型另计费，旧 SuperGrok 档不能直接映射。 |
| Grok（xAI） / SuperGrok Plus | 待核验 | USD 100 | 666.976 | 待核验 | 当前 X Subscription 将 Grok、Cursor 与 API 使用纳入共享规则；第三方模型另计费，旧 SuperGrok 档不能直接映射。 |
| Kimi（月之暗面） / Allegretto | 待核验 | CNY 199 | 199 | 待核验 | 新旧会员规则并存：新档取消周窗口但保留月额度和 5 小时窗口；旧 Andante 等档不自动迁移，不能混用额度。 |
| Kimi（月之暗面） / Allegro | 待核验 | CNY 699 | 699 | 待核验 | 新旧会员规则并存：新档取消周窗口但保留月额度和 5 小时窗口；旧 Andante 等档不自动迁移，不能混用额度。 |
| Kimi（月之暗面） / Andante | 待核验 | CNY 49 | 49 | 待核验 | 新旧会员规则并存：新档取消周窗口但保留月额度和 5 小时窗口；旧 Andante 等档不自动迁移，不能混用额度。 |
| Kimi（月之暗面） / Moderato | 待核验 | CNY 99 | 99 | 待核验 | 新旧会员规则并存：新档取消周窗口但保留月额度和 5 小时窗口；旧 Andante 等档不自动迁移，不能混用额度。 |
| MiniMax / Max | 待核验 | CNY 119 | 119 | 待核验 | 当前 M Plan 与旧套餐名称、相对额度不能直接对应，旧数值保留在历史记录。 |
| MiniMax / Plus | 待核验 | CNY 49 | 49 | 待核验 | 当前 M Plan 与旧套餐名称、相对额度不能直接对应，旧数值保留在历史记录。 |
| MiniMax / Ultra | 待核验 | CNY 469 | 469 | 待核验 | 当前 M Plan 与旧套餐名称、相对额度不能直接对应，旧数值保留在历史记录。 |
| OpenAI / ChatGPT Pro 5× | 待核验 | USD 100 | 666.976 | 待核验 | 不同模型消耗不同，共享额度会随任务、推理和工具使用变化；旧 Pro 档不能套用 Business 列。 |
| 通义 Qwen Code / Coding Plan | 待核验 | CNY 200 | 200 | 待核验 | 请求数并非固定 token 保证，需同时核对短周期限额和支持的工具。 |
| R4Coder / R4Coder Mini | 待核验 | USD 5 | 33.3488 | 待核验 | 工具更新与模型供应情况需分别核对，历史 token 额度不作为当前保证。 |
| Trae / Pro | 待核验 | USD 20 | 133.3952 | 待核验 | 区分内置模型额度与外部服务订阅，外部限流不能归因于 IDE 本身。 |
| Trae / Pro+ | 待核验 | USD 60 | 400.1856 | 待核验 | 区分内置模型额度与外部服务订阅，外部限流不能归因于 IDE 本身。 |
| Trae / Ultra | 待核验 | USD 200 | 1333.952 | 待核验 | 区分内置模型额度与外部服务订阅，外部限流不能归因于 IDE 本身。 |
| 智谱AI / Lite | 待核验 | CNY 118 | 118 | 待核验 | 5 小时与周积分同时限制；模型和缓存倍率、峰谷时段会改变可用量。需确认所购地区套餐适用相同规则。 |
| 智谱AI / Max | 待核验 | CNY 1078 | 1078 | 待核验 | 5 小时与周积分同时限制；模型和缓存倍率、峰谷时段会改变可用量。需确认所购地区套餐适用相同规则。 |
| 智谱AI / Pro | 待核验 | CNY 538 | 538 | 待核验 | 5 小时与周积分同时限制；模型和缓存倍率、峰谷时段会改变可用量。需确认所购地区套餐适用相同规则。 |

## 额度与证据

统一 token 比价以 regular / daily 画像为默认：8k 新输入、24k 缓存读取、2k 输出；22 个活跃日、每日两个窗口，从新订阅周期开始。≈ 为情景推算；历史、社区及预算假设不作为厂商保证额度，也不参与默认推荐成本加分。共享池不求和。

| 套餐 / 模型 | 情景月 token | CNY/亿 token | 估算依据 / 置信度 | 原始限额 | 依据日期 |
| --- | --- | --- | --- | --- | --- |
| OpenAI ChatGPT Plus / GPT-5.6 Sol（历史收录，型号待核验） | ≈ 14960000 | ≈ 891.68 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenAI ChatGPT Plus / GPT-5.6 Terra（历史收录，型号待核验） | ≈ 37400000 | ≈ 356.67 | historical / low | 未核验 | 未知 |
| OpenAI ChatGPT Plus / GPT-5.6 Luna（历史收录，型号待核验） | ≈ 374000000 | ≈ 35.67 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenAI ChatGPT Plus / GPT-6.1 Sol | ≈ 22440000 | ≈ 594.45 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenAI ChatGPT Plus / GPT-6 Astra | ≈ 7480000 | ≈ 1783.36 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenAI ChatGPT Plus / GPT-6 Sol | ≈ 22440000 | ≈ 594.45 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenAI ChatGPT Plus / GPT-6 Luna | ≈ 523600000 | ≈ 25.48 | partial-rules / low | 未核验 | 2026-10-26 |
| OpenCode OpenCode Go / Claude Haiku 5.5 | ≈ 49980000 | ≈ 133.45 | partial-rules / low | 3 usd/5h (claude-haiku-5.5; unknown); 7.5 usd/168h (claude-haiku-5.5; unknown); 15 usd/720h (claude-haiku-5.5; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Muse Spark 1.3（历史收录，型号待核验） | ≈ 8500000000 | ≈ 0.78 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / DeepSeek V4.1 Flash | ≈ 550154000 | ≈ 12.12 | partial-rules / low | 16 usd/5h (deepseek-v4.1-flash; unknown); 40 usd/168h (deepseek-v4.1-flash; unknown); 80 usd/720h (deepseek-v4.1-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / GLM-5.3-Flash | ≈ 698598000 | ≈ 9.55 | partial-rules / low | 12 usd/5h (glm-5.3-flash; unknown); 30 usd/168h (glm-5.3-flash; unknown); 60 usd/720h (glm-5.3-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / GLM 5.3 | ≈ 19414000 | ≈ 343.55 | partial-rules / low | 3 usd/5h (glm-5.3; unknown); 7.5 usd/168h (glm-5.3; unknown); 15 usd/720h (glm-5.3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / GLM 5.2 | ≈ 77724000 | ≈ 85.81 | partial-rules / low | 12 usd/5h (glm-5.2; unknown); 30 usd/168h (glm-5.2; unknown); 60 usd/720h (glm-5.2; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / GLM 5.1（历史收录，型号待核验） | ≈ 150892000 | ≈ 44.20 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Kimi K3 | ≈ 8330000 | ≈ 800.69 | partial-rules / low | 3 usd/5h (kimi-k3; unknown); 7.5 usd/168h (kimi-k3; unknown); 15 usd/720h (kimi-k3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Kimi K2.7 Code | ≈ 101184000 | ≈ 65.92 | partial-rules / low | 12 usd/5h (kimi-k2.7-code; unknown); 30 usd/168h (kimi-k2.7-code; unknown); 60 usd/720h (kimi-k2.7-code; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Kimi K2.6（历史收录，型号待核验） | ≈ 214064000 | ≈ 31.16 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / LongCat 2.0 | ≈ 412590000 | ≈ 16.17 | partial-rules / low | 12 usd/5h (longcat-2.0; unknown); 30 usd/168h (longcat-2.0; unknown); 60 usd/720h (longcat-2.0; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiMo V2.5 | ≈ 1167560000 | ≈ 5.71 | partial-rules / low | 12 usd/5h (mimo-v2.5; unknown); 30 usd/168h (mimo-v2.5; unknown); 60 usd/720h (mimo-v2.5; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiMo V2.5 Pro | ≈ 96084000 | ≈ 69.42 | partial-rules / low | 3 usd/5h (mimo-v2.5-pro; unknown); 7.5 usd/168h (mimo-v2.5-pro; unknown); 15 usd/720h (mimo-v2.5-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiniMax M3 | ≈ 326910000 | ≈ 20.40 | partial-rules / low | 12 usd/5h (minimax-m3; unknown); 30 usd/168h (minimax-m3; unknown); 60 usd/720h (minimax-m3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiniMax M2.7（历史收录，型号待核验） | ≈ 625668000 | ≈ 10.66 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Muse Spark 1.2 Contributor | ≈ 1634584000 | ≈ 4.08 | partial-rules / low | 12 usd/5h (muse-spark-1.2-contributor; unknown); 30 usd/168h (muse-spark-1.2-contributor; unknown); 60 usd/720h (muse-spark-1.2-contributor; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Qwen3.8 Max | ≈ 14994000 | ≈ 444.83 | partial-rules / low | 3 usd/5h (qwen3.8-max; unknown); 7.5 usd/168h (qwen3.8-max; unknown); 15 usd/720h (qwen3.8-max; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Qwen3.8 Flash | ≈ 404090000 | ≈ 16.51 | partial-rules / low | 6 usd/5h (qwen3.8-flash; unknown); 15 usd/168h (qwen3.8-flash; unknown); 30 usd/720h (qwen3.8-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Qwen3.7 Max（历史收录，型号待核验） | ≈ 37128000 | ≈ 179.64 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Qwen3.7 Plus | ≈ 92378000 | ≈ 72.20 | partial-rules / low | 12 usd/5h (qwen3.7-plus; unknown); 30 usd/168h (qwen3.7-plus; unknown); 60 usd/720h (qwen3.7-plus; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Qwen3.6 Plus（历史收录，型号待核验） | ≈ 624444000 | ≈ 10.68 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / DeepSeek V4 Pro | ≈ 26078000 | ≈ 255.76 | partial-rules / low | 3 usd/5h (deepseek-v4-pro; unknown); 7.5 usd/168h (deepseek-v4-pro; unknown); 15 usd/720h (deepseek-v4-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / DeepSeek V4 Flash（历史收录，型号待核验） | ≈ 3108654000 | ≈ 2.15 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / DeepSeek V4 Flash Vision Exp（历史收录，型号待核验） | ≈ 1554310000 | ≈ 4.29 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Hy4 Preview | ≈ 80410000 | ≈ 82.95 | partial-rules / low | 6 usd/5h (hy4-preview; unknown); 15 usd/168h (hy4-preview; unknown); 30 usd/720h (hy4-preview; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Hy3 | ≈ 653820000 | ≈ 10.20 | partial-rules / low | 12 usd/5h (hy3; unknown); 30 usd/168h (hy3; unknown); 60 usd/720h (hy3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Grok 4.6（历史收录，型号待核验） | ≈ 18496000 | ≈ 360.61 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / GPT 5.6 Luna | ≈ 65688000 | ≈ 101.54 | partial-rules / low | 3 usd/5h (gpt-5.6-luna; unknown); 7.5 usd/168h (gpt-5.6-luna; unknown); 15 usd/720h (gpt-5.6-luna; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiMo V2.6 Flash | ≈ 1167560000 | ≈ 5.71 | partial-rules / low | 12 usd/5h (mimo-v2.6-flash; unknown); 30 usd/168h (mimo-v2.6-flash; unknown); 60 usd/720h (mimo-v2.6-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiMo V2.6 Pro | ≈ 96084000 | ≈ 69.42 | partial-rules / low | 3 usd/5h (mimo-v2.6-pro; unknown); 7.5 usd/168h (mimo-v2.6-pro; unknown); 15 usd/720h (mimo-v2.6-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Grok 4.7 | ≈ 6358000 | ≈ 1049.03 | partial-rules / low | 3 usd/5h (grok-4.7; unknown); 7.5 usd/168h (grok-4.7; unknown); 15 usd/720h (grok-4.7; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / GPT 6 Luna | ≈ 142426000 | ≈ 46.83 | partial-rules / low | 3 usd/5h (gpt-6-luna; unknown); 7.5 usd/168h (gpt-6-luna; unknown); 15 usd/720h (gpt-6-luna; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Gemini 4 Argon | ≈ 56644000 | ≈ 117.75 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Step 5 Preview | ≈ 32266000 | ≈ 206.71 | partial-rules / low | 3 usd/5h (step-5-preview; unknown); 7.5 usd/168h (step-5-preview; unknown); 15 usd/720h (step-5-preview; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / MiniMax M3.1 Flash | ≈ 246364000 | ≈ 27.07 | partial-rules / low | 4 usd/5h (minimax-m3.1-flash; unknown); 10 usd/168h (minimax-m3.1-flash; unknown); 20 usd/720h (minimax-m3.1-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Kimi K3.1 Pro | ≈ 12478000 | ≈ 534.52 | partial-rules / low | 3 usd/5h (kimi-k3.1-pro; unknown); 7.5 usd/168h (kimi-k3.1-pro; unknown); 15 usd/720h (kimi-k3.1-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go / Beam Free | ≈ 149600000 | ≈ 44.58 | workload-proxy / low | 未核验 | 未知 |
| OpenCode OpenCode Go / Muse Spark 1.3 Contributor | ≈ 1634584000 | ≈ 4.08 | partial-rules / low | 12 usd/5h (muse-spark-1.3-contributor; unknown); 30 usd/168h (muse-spark-1.3-contributor; unknown); 60 usd/720h (muse-spark-1.3-contributor; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiMo V2.5 | ≈ 2335154000 | ≈ 11.42 | partial-rules / low | 24 usd/5h (mimo-v2.5; unknown); 60 usd/168h (mimo-v2.5; unknown); 120 usd/720h (mimo-v2.5; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiniMax M3 | ≈ 980764000 | ≈ 27.20 | partial-rules / low | 36 usd/5h (minimax-m3; unknown); 90 usd/168h (minimax-m3; unknown); 180 usd/720h (minimax-m3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / GLM 5.2 | ≈ 233206000 | ≈ 114.40 | partial-rules / low | 36 usd/5h (glm-5.2; unknown); 90 usd/168h (glm-5.2; unknown); 180 usd/720h (glm-5.2; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Claude Haiku 5.5 | ≈ 199988000 | ≈ 133.40 | partial-rules / low | 12 usd/5h (claude-haiku-5.5; unknown); 30 usd/168h (claude-haiku-5.5; unknown); 60 usd/720h (claude-haiku-5.5; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Gemini 4 Argon | ≈ 226644000 | ≈ 117.71 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go Plus / Hy4 Preview | ≈ 321708000 | ≈ 82.93 | partial-rules / low | 24 usd/5h (hy4-preview; unknown); 60 usd/168h (hy4-preview; unknown); 120 usd/720h (hy4-preview; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiMo V2.5 Pro | ≈ 384370000 | ≈ 69.41 | partial-rules / low | 12 usd/5h (mimo-v2.5-pro; unknown); 30 usd/168h (mimo-v2.5-pro; unknown); 60 usd/720h (mimo-v2.5-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Muse Spark 1.2 Contributor | ≈ 3269202000 | ≈ 8.16 | partial-rules / low | 24 usd/5h (muse-spark-1.2-contributor; unknown); 60 usd/168h (muse-spark-1.2-contributor; unknown); 120 usd/720h (muse-spark-1.2-contributor; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Grok 4.7 | ≈ 25500000 | ≈ 1046.24 | partial-rules / low | 12 usd/5h (grok-4.7; unknown); 30 usd/168h (grok-4.7; unknown); 60 usd/720h (grok-4.7; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Qwen3.7 Plus | ≈ 277168000 | ≈ 96.26 | partial-rules / low | 36 usd/5h (qwen3.7-plus; unknown); 90 usd/168h (qwen3.7-plus; unknown); 180 usd/720h (qwen3.7-plus; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiMo V2.6 Pro | ≈ 384370000 | ≈ 69.41 | partial-rules / low | 12 usd/5h (mimo-v2.6-pro; unknown); 30 usd/168h (mimo-v2.6-pro; unknown); 60 usd/720h (mimo-v2.6-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / DeepSeek V4.1 Flash | ≈ 1100308000 | ≈ 24.25 | partial-rules / low | 32 usd/5h (deepseek-v4.1-flash; unknown); 80 usd/168h (deepseek-v4.1-flash; unknown); 160 usd/720h (deepseek-v4.1-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Qwen3.8 Max | ≈ 59976000 | ≈ 444.83 | partial-rules / low | 12 usd/5h (qwen3.8-max; unknown); 30 usd/168h (qwen3.8-max; unknown); 60 usd/720h (qwen3.8-max; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Hy3 | ≈ 2615382000 | ≈ 10.20 | partial-rules / low | 48 usd/5h (hy3; unknown); 120 usd/168h (hy3; unknown); 240 usd/720h (hy3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / GPT 5.6 Luna | ≈ 262854000 | ≈ 101.50 | partial-rules / low | 12 usd/5h (gpt-5.6-luna; unknown); 30 usd/168h (gpt-5.6-luna; unknown); 60 usd/720h (gpt-5.6-luna; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / LongCat 2.0 | ≈ 1650462000 | ≈ 16.16 | partial-rules / low | 48 usd/5h (longcat-2.0; unknown); 120 usd/168h (longcat-2.0; unknown); 240 usd/720h (longcat-2.0; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Muse Spark 1.3（历史收录，型号待核验） | ≈ 17000000000 | ≈ 1.57 | historical / low | 未核验 | 未知 |
| OpenCode OpenCode Go Plus / Step 5 Preview | ≈ 129098000 | ≈ 206.66 | partial-rules / low | 12 usd/5h (step-5-preview; unknown); 30 usd/168h (step-5-preview; unknown); 60 usd/720h (step-5-preview; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Kimi K2.7 Code | ≈ 303552000 | ≈ 87.89 | partial-rules / low | 36 usd/5h (kimi-k2.7-code; unknown); 90 usd/168h (kimi-k2.7-code; unknown); 180 usd/720h (kimi-k2.7-code; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiniMax M3.1 Flash | ≈ 985490000 | ≈ 27.07 | partial-rules / low | 16 usd/5h (minimax-m3.1-flash; unknown); 40 usd/168h (minimax-m3.1-flash; unknown); 80 usd/720h (minimax-m3.1-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Kimi K3.1 Pro | ≈ 49980000 | ≈ 533.79 | partial-rules / low | 12 usd/5h (kimi-k3.1-pro; unknown); 30 usd/168h (kimi-k3.1-pro; unknown); 60 usd/720h (kimi-k3.1-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / GLM 5.3 | ≈ 155482000 | ≈ 171.59 | partial-rules / low | 24 usd/5h (glm-5.3; unknown); 60 usd/168h (glm-5.3; unknown); 120 usd/720h (glm-5.3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / GPT 6 Luna | ≈ 569806000 | ≈ 46.82 | partial-rules / low | 12 usd/5h (gpt-6-luna; unknown); 30 usd/168h (gpt-6-luna; unknown); 60 usd/720h (gpt-6-luna; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / DeepSeek V4 Pro | ≈ 104414000 | ≈ 255.51 | partial-rules / low | 12 usd/5h (deepseek-v4-pro; unknown); 30 usd/168h (deepseek-v4-pro; unknown); 60 usd/720h (deepseek-v4-pro; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / MiMo V2.6 Flash | ≈ 2335154000 | ≈ 11.42 | partial-rules / low | 24 usd/5h (mimo-v2.6-flash; unknown); 60 usd/168h (mimo-v2.6-flash; unknown); 120 usd/720h (mimo-v2.6-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / GLM-5.3-Flash | ≈ 2095862000 | ≈ 12.73 | partial-rules / low | 36 usd/5h (glm-5.3-flash; unknown); 90 usd/168h (glm-5.3-flash; unknown); 180 usd/720h (glm-5.3-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Qwen3.8 Flash | ≈ 1212338000 | ≈ 22.01 | partial-rules / low | 18 usd/5h (qwen3.8-flash; unknown); 45 usd/168h (qwen3.8-flash; unknown); 90 usd/720h (qwen3.8-flash; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Kimi K3 | ≈ 33320000 | ≈ 800.69 | partial-rules / low | 12 usd/5h (kimi-k3; unknown); 30 usd/168h (kimi-k3; unknown); 60 usd/720h (kimi-k3; subscription) | 2026-10-26 |
| OpenCode OpenCode Go Plus / Beam Free | ≈ 149600000 | ≈ 178.34 | workload-proxy / low | 未核验 | 未知 |
| OpenCode OpenCode Go Plus / Muse Spark 1.3 Contributor | ≈ 3269202000 | ≈ 8.16 | partial-rules / low | 24 usd/5h (muse-spark-1.3-contributor; unknown); 60 usd/168h (muse-spark-1.3-contributor; unknown); 120 usd/720h (muse-spark-1.3-contributor; subscription) | 2026-10-26 |
| 字节方舟 Lite / 套餐参考用量 / Plan reference（套餐参照） | ≈ 796858000 | ≈ 5.02 | historical / low | 未核验 | 未知 |
| 字节方舟 Lite / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 796858000 | ≈ 5.02 | historical / low | 未核验 | 未知 |
| 字节方舟 Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 3984358000 | ≈ 5.02 | historical / low | 未核验 | 未知 |
| 字节方舟 Pro / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 3984358000 | ≈ 5.02 | historical / low | 未核验 | 未知 |
| Claude Max 20× / 套餐参考用量 / Plan reference（套餐参照） | ≈ 1705134000 | ≈ 78.23 | community / low | 未核验 | 2026-09-20 |
| Claude Max 5× / 套餐参考用量 / Plan reference（套餐参照） | ≈ 852924000 | ≈ 78.20 | community / low | 未核验 | 2026-09-20 |
| Claude Max 5× / 套餐内模型（综合）（历史收录，型号待核验） | ≈ 852924000 | ≈ 78.20 | community / low | 未核验 | 2026-09-20 |
| Claude Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 102544000 | ≈ 130.09 | community / low | 未核验 | 2026-09-20 |
| Claude Pro / 套餐内模型（综合）（历史收录，型号待核验） | ≈ 102544000 | ≈ 130.09 | community / low | 未核验 | 2026-09-20 |
| CommandCode CommandCode GOAT / 套餐参考用量 / Plan reference（套餐参照） | ≈ 208080000 | ≈ 32.05 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4.1 Flash（历史收录，型号待核验） | ≈ 6970000000 | ≈ 0.96 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 1604800000 | ≈ 4.16 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GPT 5.6 Sol（历史收录，型号待核验） | ≈ 20128000 | ≈ 331.37 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4 Flash Latest（历史收录，型号待核验） | ≈ 5236000000 | ≈ 1.27 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GLM 5.2（历史收录，型号待核验） | ≈ 161160000 | ≈ 41.39 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GPT 5.6 Luna（历史收录，型号待核验） | ≈ 503200000 | ≈ 13.25 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Tencent Hy3（历史收录，型号待核验） | ≈ 1203600000 | ≈ 5.54 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 27B（历史收录，型号待核验） | ≈ 816000000 | ≈ 8.17 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 Max（历史收录，型号待核验） | ≈ 44540000 | ≈ 149.75 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.7 Max（历史收录，型号待核验） | ≈ 39440000 | ≈ 169.11 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.7 Plus（历史收录，型号待核验） | ≈ 241740000 | ≈ 27.59 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.6 Plus（历史收录，型号待核验） | ≈ 187000000 | ≈ 35.67 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiniMax M3（历史收录，型号待核验） | ≈ 472600000 | ≈ 14.11 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Kimi K2.7 Code（历史收录，型号待核验） | ≈ 184280000 | ≈ 36.19 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Gemini 3.8 Flash（历史收录，型号待核验） | ≈ 133280000 | ≈ 50.04 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / LongCat 2.0（历史收录，型号待核验） | ≈ 2179400000 | ≈ 3.06 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiMo V2.5（历史收录，型号待核验） | ≈ 3311600000 | ≈ 2.01 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4 Pro Latest（历史收录，型号待核验） | ≈ 335920000 | ≈ 19.86 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiMo V2.5 Pro（历史收录，型号待核验） | ≈ 969000000 | ≈ 6.88 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 Omni Flash（历史收录，型号待核验） | ≈ 669800000 | ≈ 9.96 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 Max 0902（历史收录，型号待核验） | ≈ 44540000 | ≈ 149.75 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Tencent Hy4 Preview（历史收录，型号待核验） | ≈ 208080000 | ≈ 32.05 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 Flash（历史收录，型号待核验） | ≈ 666400000 | ≈ 10.01 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GLM 5.3 Flashx（历史收录，型号待核验） | ≈ 160480000 | ≈ 41.56 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4 Flash Vision Exp（历史收录，型号待核验） | ≈ 1744200000 | ≈ 3.82 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4 Flash Fast（历史收录，型号待核验） | ≈ 177140000 | ≈ 37.65 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GLM 5.3（历史收录，型号待核验） | ≈ 45900000 | ≈ 145.31 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Muse Spark 1.3（历史收录，型号待核验） | ≈ 72760000 | ≈ 91.67 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Muse Spark 1.3 Contributor（历史收录，型号待核验） | ≈ 3090600000 | ≈ 2.16 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Muse Spark 1.2（历史收录，型号待核验） | ≈ 72760000 | ≈ 91.67 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Muse Spark 1.2 Contributor（历史收录，型号待核验） | ≈ 3090600000 | ≈ 2.16 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Kimi K3（历史收录，型号待核验） | ≈ 33320000 | ≈ 200.17 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Kimi K2.7 Code Highspeed（历史收录，型号待核验） | ≈ 30736000 | ≈ 217.00 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Grok 4.5（历史收录，型号待核验） | ≈ 24446000 | ≈ 272.84 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Grok 4.6（历史收录，型号待核验） | ≈ 24446000 | ≈ 272.84 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Gemini 3.7 Flash（历史收录，型号待核验） | ≈ 133280000 | ≈ 50.04 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GLM 5.2 Fast（历史收录，型号待核验） | ≈ 23494000 | ≈ 283.89 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Inkling（历史收录，型号待核验） | ≈ 67320000 | ≈ 99.08 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Inkling Small（历史收录，型号待核验） | ≈ 120700000 | ≈ 55.26 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Step 3.7 Flash（历史收录，型号待核验） | ≈ 284580000 | ≈ 23.44 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Step 3.5 Flash（历史收录，型号待核验） | ≈ 601800000 | ≈ 11.08 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Nemotron 3 Ultra（历史收录，型号待核验） | ≈ 97580000 | ≈ 68.35 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Grok 4.7（历史收录，型号待核验） | ≈ 24446000 | ≈ 272.84 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Step 5 Preview（历史收录，型号待核验） | ≈ 177140000 | ≈ 37.65 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiMo V2.6 Flash（历史收录，型号待核验） | ≈ 2206600000 | ≈ 3.02 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiMo V2.6 Pro（历史收录，型号待核验） | ≈ 969000000 | ≈ 6.88 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiMo V2.6 Pro Ultraspeed（历史收录，型号待核验） | ≈ 48280000 | ≈ 138.15 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / GPT 6 Luna（历史收录，型号待核验） | ≈ 1030200000 | ≈ 6.47 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Jev（历史收录，型号待核验） | ≈ 20230000000 | ≈ 0.33 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / DeepSeek V4.1 Flash Fast（历史收录，型号待核验） | ≈ 1955000000 | ≈ 3.41 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Claude Sonnet 5.5（历史收录，型号待核验） | ≈ 40460000 | ≈ 164.85 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Mistral Large 4（历史收录，型号待核验） | ≈ 76160000 | ≈ 87.58 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Claude Haiku 5.5（历史收录，型号待核验） | ≈ 1016600000 | ≈ 6.56 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Ling 3.1 Flash（历史收录，型号待核验） | ≈ 992800000 | ≈ 6.72 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Qwen 3.8 Max Prime（历史收录，型号待核验） | ≈ 22236000 | ≈ 299.95 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Muse Spark Open（历史收录，型号待核验） | ≈ 72760000 | ≈ 91.67 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Nemotron 3.5 Super Vl（历史收录，型号待核验） | ≈ 300900000 | ≈ 22.17 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Jev 1.14.0（历史收录，型号待核验） | ≈ 20230000000 | ≈ 0.33 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / MiniMax M3.1 Flash（历史收录，型号待核验） | ≈ 720800000 | ≈ 9.25 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Ornith 1.5 122B（历史收录，型号待核验） | ≈ 540600000 | ≈ 12.34 | historical / low | 未核验 | 未知 |
| CommandCode CommandCode GOAT / Kimi K3.1 Pro（历史收录，型号待核验） | ≈ 49980000 | ≈ 133.45 | historical / low | 未核验 | 未知 |
| GitHub Copilot Max / 套餐参考用量 / Plan reference（套餐参照） | ≈ 88536000 | ≈ 753.34 | budget-proxy / low | 未核验 | 未知 |
| GitHub Copilot Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 8840000 | ≈ 754.50 | budget-proxy / low | 未核验 | 未知 |
| GitHub Copilot Pro+ / 套餐参考用量 / Plan reference（套餐参照） | ≈ 34510000 | ≈ 753.75 | budget-proxy / low | 未核验 | 未知 |
| Cursor Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 17680000 | ≈ 754.50 | budget-proxy / low | 未核验 | 未知 |
| Cursor Pro+ / 套餐参考用量 / Plan reference（套餐参照） | ≈ 53108000 | ≈ 753.53 | budget-proxy / low | 未核验 | 未知 |
| Cursor Ultra / 套餐参考用量 / Plan reference（套餐参照） | ≈ 177072000 | ≈ 753.34 | budget-proxy / low | 未核验 | 未知 |
| Devin（原 Windsurf） Max / 套餐参考用量 / Plan reference（套餐参照） | ≈ 35156000 | ≈ 3794.38 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Max / Premium Plus 档（Opus/GPT-5.x）（历史收录，型号待核验） | ≈ 31382000 | ≈ 4250.69 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Max / Premium 档（Sonnet/GPT-5.2/Gemini Pro）（历史收录，型号待核验） | ≈ 35156000 | ≈ 3794.38 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Max / Lightweight 档（Haiku/Flash）（历史收录，型号待核验） | ≈ 217634000 | ≈ 612.93 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 5984000 | ≈ 2229.20 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Pro / Premium Plus 档（Opus/GPT-5.x）（历史收录，型号待核验） | ≈ 5236000 | ≈ 2547.65 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Pro / Premium 档（Sonnet/GPT-5.2/Gemini Pro）（历史收录，型号待核验） | ≈ 5984000 | ≈ 2229.20 | historical / low | 未核验 | 未知 |
| Devin（原 Windsurf） Pro / Lightweight 档（Haiku/Flash）（历史收录，型号待核验） | ≈ 35156000 | ≈ 379.44 | historical / low | 未核验 | 未知 |
| Gemini Code Assist Enterprise / 套餐参考用量 / Plan reference（套餐参照） | ≈ 1496000000 | ≈ 24.08 | historical / low | 未核验 | 未知 |
| Gemini Code Assist Enterprise / 套餐内模型（综合）（历史收录，型号待核验） | ≈ 1496000000 | ≈ 24.08 | historical / low | 未核验 | 未知 |
| Gemini Code Assist Standard / 套餐参考用量 / Plan reference（套餐参照） | ≈ 1122000000 | ≈ 13.55 | historical / low | 未核验 | 未知 |
| Gemini Code Assist Standard / 套餐内模型（综合）（历史收录，型号待核验） | ≈ 1122000000 | ≈ 13.55 | historical / low | 未核验 | 未知 |
| Grok（xAI） SuperGrok / 套餐参考用量 / Plan reference（套餐参照） | ≈ 26554000 | ≈ 753.53 | budget-proxy / low | 未核验 | 未知 |
| Grok（xAI） SuperGrok Plus / 套餐参考用量 / Plan reference（套餐参照） | ≈ 88536000 | ≈ 753.34 | budget-proxy / low | 未核验 | 未知 |
| Kimi（月之暗面） Allegretto / 套餐参考用量 / Plan reference（套餐参照） | ≈ 26384000 | ≈ 754.24 | budget-proxy / low | 未核验 | 未知 |
| Kimi（月之暗面） Allegro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 92786000 | ≈ 753.35 | budget-proxy / low | 未核验 | 未知 |
| Kimi（月之暗面） Andante / 套餐参考用量 / Plan reference（套餐参照） | ≈ 6494000 | ≈ 754.54 | budget-proxy / low | 未核验 | 未知 |
| Kimi（月之暗面） Moderato / 套餐参考用量 / Plan reference（套餐参照） | ≈ 13124000 | ≈ 754.34 | budget-proxy / low | 未核验 | 未知 |
| MiniMax Max / 套餐参考用量 / Plan reference（套餐参照） | ≈ 1195304000 | ≈ 9.96 | historical / low | 未核验 | 未知 |
| MiniMax Max / MiniMax-M3（历史收录，型号待核验） | ≈ 1195304000 | ≈ 9.96 | historical / low | 未核验 | 未知 |
| MiniMax Plus / 套餐参考用量 / Plan reference（套餐参照） | ≈ 398412000 | ≈ 12.30 | historical / low | 未核验 | 未知 |
| MiniMax Plus / MiniMax-M3（历史收录，型号待核验） | ≈ 398412000 | ≈ 12.30 | historical / low | 未核验 | 未知 |
| MiniMax Ultra / 套餐参考用量 / Plan reference（套餐参照） | ≈ 3652314000 | ≈ 12.84 | historical / low | 未核验 | 未知 |
| MiniMax Ultra / MiniMax-M3（历史收录，型号待核验） | ≈ 3652314000 | ≈ 12.84 | historical / low | 未核验 | 未知 |
| OpenAI ChatGPT Pro 5× / 套餐参考用量 / Plan reference（套餐参照） | ≈ 187000000 | ≈ 356.67 | historical / low | 未核验 | 未知 |
| OpenAI ChatGPT Pro 5× / GPT-5.6 Sol（历史收录，型号待核验） | ≈ 74800000 | ≈ 891.68 | historical / low | 未核验 | 未知 |
| OpenAI ChatGPT Pro 5× / GPT-5.6 Terra（历史收录，型号待核验） | ≈ 187000000 | ≈ 356.67 | historical / low | 未核验 | 未知 |
| OpenAI ChatGPT Pro 5× / GPT-5.6 Luna（历史收录，型号待核验） | ≈ 1870000000 | ≈ 35.67 | historical / low | 未核验 | 未知 |
| 通义 Qwen Code Coding Plan / 套餐内模型（综合）（历史收录，型号待核验） | ≈ 3060000000 | ≈ 6.54 | historical / low | 未核验 | 未知 |
| 通义 Qwen Code Coding Plan / qwen3.7-plus | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| 通义 Qwen Code Coding Plan / qwen3.6-plus | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| 通义 Qwen Code Coding Plan / kimi-k2.5 | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| 通义 Qwen Code Coding Plan / glm-5 | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| 通义 Qwen Code Coding Plan / minimax-m2.5 | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| 通义 Qwen Code Coding Plan / qwen3.5-plus | ≈ 3060000000 | ≈ 6.54 | rules / medium | 6000 requests/5h (qwen-pro-shared; rolling); 45000 requests/168h (qwen-pro-shared; fixed); 90000 requests/720h (qwen-pro-shared; subscription) | 2026-10-26 |
| R4Coder R4Coder Mini / 套餐参考用量 / Plan reference（套餐参照） | ≈ 1912500000 | ≈ 1.74 | historical / low | 未核验 | 未知 |
| R4Coder R4Coder Mini / DeepSeek V4.1 Flash（历史收录，型号待核验） | ≈ 1912500000 | ≈ 1.74 | historical / low | 未核验 | 未知 |
| R4Coder R4Coder Mini / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 1089054000 | ≈ 3.06 | historical / low | 未核验 | 未知 |
| Trae Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 17680000 | ≈ 754.50 | budget-proxy / low | 未核验 | 未知 |
| Trae Pro+ / 套餐参考用量 / Plan reference（套餐参照） | ≈ 53108000 | ≈ 753.53 | budget-proxy / low | 未核验 | 未知 |
| Trae Ultra / 套餐参考用量 / Plan reference（套餐参照） | ≈ 177072000 | ≈ 753.34 | budget-proxy / low | 未核验 | 未知 |
| 智谱AI Lite / 套餐参考用量 / Plan reference（套餐参照） | ≈ 578510000 | ≈ 20.40 | historical / low | 未核验 | 未知 |
| 智谱AI Lite / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 578510000 | ≈ 20.40 | historical / low | 未核验 | 未知 |
| 智谱AI Lite / GLM-5.3（历史收录，型号待核验） | ≈ 192814000 | ≈ 61.20 | historical / low | 未核验 | 未知 |
| 智谱AI Max / 套餐参考用量 / Plan reference（套餐参照） | ≈ 8099412000 | ≈ 13.31 | historical / low | 未核验 | 未知 |
| 智谱AI Max / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 8099412000 | ≈ 13.31 | historical / low | 未核验 | 未知 |
| 智谱AI Max / GLM-5.3（历史收录，型号待核验） | ≈ 2699804000 | ≈ 39.93 | historical / low | 未核验 | 未知 |
| 智谱AI Pro / 套餐参考用量 / Plan reference（套餐参照） | ≈ 3471162000 | ≈ 15.50 | historical / low | 未核验 | 未知 |
| 智谱AI Pro / GLM-5.3-Flash（历史收录，型号待核验） | ≈ 3471162000 | ≈ 15.50 | historical / low | 未核验 | 未知 |
| 智谱AI Pro / GLM-5.3（历史收录，型号待核验） | ≈ 1157054000 | ≈ 46.50 | historical / low | 未核验 | 未知 |

完整公式、画像、历史归档和来源见 [data/catalog.json](data/catalog.json)。官方未知额度不影响价格收录。社区估算为低置信度，不作为官方保证。
