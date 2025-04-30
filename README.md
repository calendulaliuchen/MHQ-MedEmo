English | 中文版本请见下方

MHQ-MedEmo is the first benchmark dataset designed to simultaneously model medical informational needs and emotional support needs in mental health queries. It is constructed using a multi-layer annotation framework grounded in Rhetorical Structure Theory (RST).

📌 Dataset Summary
Source: Mental health questions from haodf.com, a leading Chinese online healthcare platform.
Collection:
468 queries from MedDialog (2020)
235 queries from haodf.com (2024), collected via Python crawler
Total: 703 curated user queries
Each query includes 10 structured fields such as symptom description, diagnosis, duration, and user request.

🧪 Annotation Details
Total annotations:
1,346 medical needs
1,155 emotional needs
Context spans:
3.68 medical-context spans/query
1.65 emotional-context spans/query

💡 Key Insights
89.9% of cases contain both medical and emotional needs
Medical needs are mostly treatment-seeking (61%) and diagnostic clarification (21%)
Emotional needs are categorized into expressions of feeling (56%) and viewpoints (44%)
Covers 582 distinct disease descriptors; 16 mapped to ICD-10 codes
Most frequent diagnoses: depression, anxiety, insomnia, OCD, bipolar disorder
This dataset is intended to support dual-objective evaluation of LLMs in mental healthcare, enabling better alignment of medical accuracy and empathy.

🧠 MHQ-MedEmo：面向医疗与情绪双重需求的心理健康问答数据集
MHQ-MedEmo 是首个同时建模医疗信息需求与情绪支持需求的心理健康问答基准数据集，采用基于**修辞结构理论（RST）**的多层标注框架构建。

📌 数据集概述
来源：来自中国领先的线上医疗平台 好大夫在线 的真实用户心理健康咨询。
数据收集方式：
468 条来自 MedDialog (2020) 的公开数据
235 条由 Python 爬虫从好大夫在线 2024 年咨询日志中随机抽取
总计：703 条高质量用户咨询
每条咨询包含 10 个结构化字段，包括症状描述、诊断信息、病程、过敏史等内容。

🧪 标注信息
医疗需求实例：1,346 条
情绪需求实例：1,155 条
上下文支持片段：
平均每条含 3.68 个医疗类上下文
平均每条含 1.65 个情绪类上下文

💡 数据洞察
89.9% 的咨询同时包含医疗和情绪需求
医疗需求以治疗请求（61%）和诊断澄清（21%）为主
情绪需求主要包括情感表达（56%）和观点表达（44%）
涵盖 582 种不同疾病描述，其中 16 个可映射至 ICD-10 编码
最常见的五类疾病为：抑郁、焦虑、失眠、强迫症和双相障碍
本数据集为心理健康领域，面向医疗与共情双目标的问答或对话模型训练和评估提供了坚实基础。
