# 分析背景


本文分析了有关消费品销售的详细数据，这些数据通过零售店的电子销售点“扫描”单个产品的条形码所获得，提供了有关所售货物的数量、特征和价值及其价格的详细信息。


**Inspiration**  
> You can use the data for the identification of customer purchase patterns, association rule mining or RFM & CLV analysis. You can also study how changes to prices affects quantity sold.

# 分析目的与结论、策略建议
**提出问题：**
- 用户画像  
- 用户数据分析  
- 产品数据分析  
GMV、成交总额、净成交总额  
成交总额占GMV  
净成交总额占GMV  
每个月的销售趋势折线图  
销售复购率  
活跃时间段  
RFM模型  

# 数据集概览
**3.1 数据集描述**  
数据来源：  
数据集名称：  
数据集大小： 131706*8   
**3.2 数据字段理解**  
*表：scanner_data*  
| 字段名 | 字段意义 |
| :-: | :-:|
| ID | 销售ID |
| Date | 销售日期 |
| Customer_ID | 客户ID |
| Transaction_ID | 交易ID |
| SKU_Category | 库存量种类 |
| SKU | 库存量单位 |
| Quantity | 售出数量 |
| Sales_Amount| 销售额 |


<u>*Sales_Amount为单价乘以数量*</u>


# 数据清洗
**1.缺失值**  

**2.异常值**  
**3.重复值**
# 用户画像
# 用户数据分析
# 产品数据分析
# RFM
# SQL代码
```SQL
select *
from scanner_data;  
```
