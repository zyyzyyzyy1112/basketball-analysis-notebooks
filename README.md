# basketball-analysis-notebooks
Store IPython notebooks for basketball data analysis, including player performance and injury risk assessment
# 篮球数据分析项目：球员表现与伤病风险评估  
本仓库存储用于篮球数据分析的 Jupyter Notebook，涵盖**球员表现分析**和**伤病风险评估**两大核心场景，助力挖掘赛事规律、防控伤病风险，为篮球赛事策略制定提供数据支撑。  

## 一、项目结构  
basketball-analysis-notebooks/
├── 篮球球员表现分析.ipynb # 球队表现分析（主客场胜率、得分特征、赛事预测）
├── 伤病风险评估.ipynb # 球员伤病风险分析（训练强度、身体指标、风险预测）
└── README.md # 项目说明（环境配置、使用指南）



## 二、环境配置依赖工具  
- **Python **：项目核心编程语言  
- **Jupyter Notebook**：运行 `.ipynb` 文件的交互式环境  
- **关键 Python 库**：  
  | 库名          | 作用                     |  
  |---------------|--------------------------|  
  | `pandas`      | 数据清洗、分析           |  
  | `numpy`       | 数值计算                 |  
  | `matplotlib`/`seaborn` | 数据可视化       |  
  | `scikit-learn`| 机器学习模型（逻辑回归等）|  
  | `xgboost`     | 梯度提升模型（可选扩展）  |  


## 三、使用说明
- 数据准备
将NBA赛事数据和伤病合成数据放入data/目录，修改.ipynb中pd.read_csv('data/xxx.csv') 的路径适配文件。
- 运行分析
启动Jupyter Notebook：jupyter notebook
打开对应.ipynb 文件，点击Cell → Run All执行分析。
-核心输出
球员表现：主客场胜率、得分特征可视化（箱线图 / 热力图），揭示主场优势、得分稳定性规律。
伤病风险：球员属性分布、伤病关联分析（热力图 / 逻辑回归），输出防控建议（训练强度、恢复周期优化）。
