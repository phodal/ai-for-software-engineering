# AI 运维

## 行业趋势

- NewRelic
    - 构建生成式 AI 应用的可观测性
    - 无缝辅助从异常到错误代码修复建议
    - 文档问答、自然查询语言转换等。
- PageDuty
    - 日常聊天助手辅助（PageDuty Copilot）
    - 总结问题、起草事故回顾报告等文本工作
    - 辅助生成 Runbook 自动化任务代码
- Dynatrace
    - 自动化的根因分析
    - 自然语言转化 Dynatrace 查询语言（DQL）
    - Davis CoPilot 辅助生成工作流代码
- Datalog
    - 辅助诊断问题，确定范围及修复问题
    - 自然语言查询数据
    - 撰写事故分析的初稿和防范（自动化测试）

## AI 运维 Copilot

问题示例：

- 告警来自哪里？
- 相关的服务及其状态是什么？
- 在过去的24小时内发生了什么变化？
- 这个事故之前是否发生过？
- 这些变化中是否有任何可能是事故原因的？
- 将@用户名添加为响应者
- 运行工作流{工作流名称}
- 确认该事故
- 帮我了解最新情况
- 解决该事故

## 运营驱动

> 产品类的问答对准确性要求高，对幻觉容忍度相对低，需要搭建运营机制多重保障落地

- 冷启动运营：
    - LLM辅助从文档抽取FAQ
    - 队伍进一步审核入库FAQ
- 日常检视运营：
    - 是否需要补充更多材料数据？
    - 是否高频问题落到FAQ通道？
    - 哪些需要进一步结构化？
- 模型持续运营：
    - 意图识别数据标注&模型迭代
    - 向量相似召回数据标注&模型迭代

