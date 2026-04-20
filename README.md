# 信用卡申请数据分析与可视化

本项目对某银行信用卡申请数据进行清洗、统计检验与用户画像构建，并制作 Tableau 交互仪表板。

## 🔍 核心结论

- 收入类型、教育程度、住房类型是与审批结果显著相关的三大特征（p<0.05）
- 公务员通过率最高（95.0%），低教育程度拒绝率最高（27.8%）

## 🛠 技术栈

- **数据处理**：Python（Pandas, NumPy）
- **统计分析**：SciPy（卡方检验、t检验等）
- **可视化**：Matplotlib, Seaborn, Tableau
- **报告撰写**：Jupyter Notebook, Markdown

## 📁 文件说明

- `credit_card_analysis.ipynb` ：数据清洗、特征工程、统计检验代码
- `report.pdf` ：详细分析报告（含图表与洞察）
- `Credit_card.twb` ：Tableau 打包工作簿
- `Credit_card.pdf` ：Tableau 仪表板截图