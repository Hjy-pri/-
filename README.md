# 🛒 零售销售分析  

一项以零售销售数据为重点的全面探索性数据分析 (EDA) 和预测项目。该项目旨在识别关键销售模式和季节性趋势，并构建预测模型，以预测商品门店层面的未来需求。 

---

## 📊 项目概览

本项目分析交易销售数据的目的是：

- 了解各商品和各门店的销售分布情况    
- 识别时间趋势和季节性
- 利用机器学习和时间序列技术预测未来销售额
- 帮助企业优化库存和促销活动

---

## 📈 仪表盘 Dashboards  

<img width="1166" height="729" alt="retail_sales_analysis" src="https://github.com/user-attachments/assets/a816a31f-5093-4f45-a1bb-9b36778094cc" />

---

## 📁 数据描述 Data Description  

该数据集通常包含：  
 
| 列名 | 描述 |
|-------------|------------------|
| ' date '    | 交易日期          |
| ' store_id '| 每个店铺的唯一 ID |
| ' item_id ' | 每个产品的唯一 ID |
| ' sales '   | 售出商品数量      |

> **注意:**    
> 实际使用的数据集是 'Superstore.csv' 和 'cleaned_superstore.csv'。
> 关键列包括： 
> 'Order ID', 'Order Date', 'Ship Date', 'Ship Mode', 'Customer ID', 'Customer Name', 'Segment', 'Country', 'City', 'State', 'Postal Code', 'Region', 'Product ID', 'Category', 'Sub-Category', 'Product Name', 'Sales', 'Quantity', 'Discount', 'Profit'.  
中文翻译：'订单号', '订单日期', '发货日期', '发货方式', '客户ID', '客户姓名', '细分', '国家', '城市', '省', '邮政编码', '地区', '产品ID', '类别', '子类别', '产品名称', '销售额', '数量', '折扣', '利润'.

---

## 🛠 环境设置 Environment Setup 

首先，克隆存储库并安装所需的依赖项。 

### 1. 克隆仓库 Clone the repository  

```bash
git clone https://github.com/Madhuarvind/Retail_sales_analysis.git          
cd Retail_sales_analysis   
```

### 2. 创建并激活虚拟环境 Create a virtual environment and activate it  创建并激活虚拟环境

```bash
# 在 Windows 系统上
python -m venv venv
.\venv\Scripts\activate

# 在 macOS/Linux 系统上
python3 -m venv venv
source venv/bin/activate
```

### 3. 安装依赖项 Install dependencies  

```bash
pip install -r requirements.txt
```

---
 
## 🚀 用法

- 运行 SQL 查询：

```bash
python run_all_queries.py
```

- 如果 'app.py' 是一个 Web 应用程序 （例如，使用 Flask 或 Dash 构建），请使用以下命令运行它：

```bash
python app.py
```

> * 更多说明取决于 'app.py' 的性质和框架 。 *  

---

## 🧾 Data

- 原始数据集： ` dataset/Superstore.csv `    
- 用于分析的已清理数据集： ` cleaned_dataset/ cleaned_superstore.csv`  

---

## 📂 分析Analysis  
 
用于分析的 SQL 查询语句存储在：

```
SQL/retail_analysis.sql      
```

---

## 📊 可视化 Visualization  

主仪表盘可视化效果：

```
visualization/retail_sales_analysis.png    
```

---

## 🤝 贡献 Contributing  

欢迎提交 Pull Request。对于重大更改，请先创建一个 Issue 来讨论您想要更改的内容。

---

## 📄 许可证
  
本项目采用 **MIT License** 进行许可。
