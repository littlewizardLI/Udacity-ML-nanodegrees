
# Capstone Project—— Predicting sales of Rossman stores

![Rossman](http://aktualnerabaty.pl/wp-content/themes/PressGrid/images/marki/logo-rossmann.jpg)

### 数据集在此处下载即可 https://www.kaggle.com/c/rossmann-store-sales/data
### 数据的内容大致为

* Id - 表示测试集中（存储，日期）副本的Id
* Store - 每个商店的独特Id
* Sales  - 任何一天的营业额（这是你预测的）
* Customers - 某一天的客户数量
* Open - 商店是否打开的指示器：0 =关闭，1 =打开
* StateHoliday - 表示一个国家假期。通常所有商店，除了少数例外，在国营假期关闭。请注意，所有学校在公众假期和周末关闭。 a =公众假期，b =复活节假期，c =圣诞节，0 =无
* SchoolHoliday - 表示（商店，日期）是否受到公立学校关闭的影响
* StoreType - 区分4种不同的商店模式：a，b，c，d
* Assortment - 描述分类级别：a = basic，b = extra，c = extended
* CompetitionDistance - 距离最接近的竞争对手商店的距离
* CompetitionOpenSince[Month/Year] ] - 给出最近的竞争对手开放时间的大约年和月
* Promo - 指示商店是否在当天运行促销
* Promo2 - Promo2是一些持续和连续推广的一些商店：0 =商店不参与，1 =商店正在参与
* Promo2自[年/周] - 描述商店开始参与Promo2的年份和日历周
* PromoInterval - 描述了Promo2的连续间隔开始，命名新的促销活动的月份。例如。 “二月，五月，八月，十一月”是指每一轮在该店的任何一年的二月，五月，八月，十一月份开始


## 文件说明
代码主要包含4个开发用的ipython notebook
* exploration[1]和processing[1]是我初次的2份代码，一个是可视化的，一个是做处理的，不过第一次我做处理的时候用的是较为简单的3个单模型，最后结果比较一般


* exploration with xgb[2]和xgb[3]是我后来实验的2个版本，其中xgb效果显著，取得了不错的成绩。


## 用到的一些库
numpy，pandas ， matplotlib，pylab，datetime，math，time，randomos都很常见


## 最终版用到的一些库以及其他说明

这个脚本用到了 [XGBoost](https://github.com/dmlc/xgboost), [Pandas](https://github.com/pydata/pandas) 和一点 [Scikit-learn](https://github.com/scikit-learn/scikit-learn).


听大神说如果添加Google趋势每日搜索“Rossmann”，每个州的州数据和天气数据，您只需一个模型即可获得第七名。 但是，由于该模型对于现实世界的使用将是无用的，因此该数据不在此模式之内。

该脚本使用大约8Gb的RAM，需要4-6个小时时间才能运行。反正我是跑了一下午。tips：32位运行会出错


