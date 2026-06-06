# ✅ AI Data Quality

AI数据质量工具，支持数据验证、数据清洗、数据监控。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 质量框架设计
- ✅ 验证规则生成
- 📊 数据画像生成
- 🔗 数据血缘设计
- 🧹 清洗规则生成
- 📋 质量报告生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_data_quality import create_tools

tools = create_tools()

# 质量框架
framework = tools.design_quality_framework("用户数据")

# 验证规则
rules = tools.generate_validation_rules(schema)

# 数据画像
profiling = tools.generate_data_profiling("用户行为数据")

# 数据血缘
lineage = tools.design_data_lineage(data_flows)

# 清洗规则
cleansing = tools.generate_cleansing_rules(["空值", "重复", "格式错误"])

# 质量报告
report = tools.generate_quality_report(metrics)
```

## 📁 项目结构

```
ai-data-quality/
├── tools.py       # 数据质量工具核心
└── README.md
```

## 📄 许可证

MIT License
