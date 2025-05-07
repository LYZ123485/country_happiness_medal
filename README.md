
# 幸福与奖牌的联系：探索幸福与奥运成功
## 国家幸福与奥运奖牌项目

该项目于 2024 年 9 月启动，是一项充满激情的倡议，由对数据分析和持续学习的热爱推动。它利用开源数据集，并完全归属于原始创作者。对数据所做的任何修改（例如清理、整理和规范化）仅用于分析目的。

该数据集汇集了来自世界幸福报告 （WHR）、奥运会奖牌数和各种幸福感分数组成部分（如 GDP、社会支持等）的见解。目的是探索五个关键分析，特别关注国家幸福感与奥林匹克成功之间的关系：

1. 总奖牌数与幸福感分数之间的相关性：调查赢得更多奥运奖牌的国家是否也往往在 WHR 中具有更高的幸福感阶梯分数。
2. 经济繁荣（人均 GDP 对数）和奥林匹克表现：探索较富裕的国家（以人均 GDP 表示）是否在奥运会上更成功。
3. 社会支持和奥林匹克成功：评估 WHR 所反映的具有更强大社会支持系统的国家是否倾向于在奥运会上表现更好。
4. 健康预期寿命和奖牌数：分析预期寿命较高的国家（通常是人口健康的标志）是否在奥运会上取得更大的成功。
5. 对腐败和奥林匹克表现的看法：检查较低水平的感知腐败是否与较高的奖牌数有关，这可能反映了影响体育成就的系统性因素。

6. 国家和地区深入研究：提供对各个国家和地区的详细见解，提供更精细的幸福感和运动表现探索。
*** 查看完整项目，随着时间的推移，扩展的见解将在此处显示： (https://brianfperry.com/landing/country_happiness_medal/)

*** 请参阅随附的 repo 文件夹 (https://github.com/dcrefugee/country_happiness_medal/blob/main/_code_happiness_medal_2024/load_and_explore.py)

---

数据来源： 
- 世界幸福报告： https://worldhappiness.report/  
- 奥运会奖牌 - 2024年巴黎奥运会： https://olympics.com/en/paris-2024/medals
- <!-- by 李荧桢 -->
=======
# Project Introduction

## Background
In September 2024, the "The Happiness - Medal Nexus: Exploring Well - being and Olympic Success" project was initiated out of a profound passion for data analysis and an unwavering commitment to continuous learning. In a world where data has the power to uncover intricate relationships, we were intrigued by the potential link between a nation's well - being and its performance in the Olympic Games. 

We sourced open - source datasets, giving full credit to the original creators. All data pre - processing steps, such as cleansing to remove errors and inconsistencies, wrangling to transform the data into a suitable format, and normalization to standardize values, were carried out strictly for the purpose of in - depth and accurate analysis. <!-- by Alice -->

## Purpose
The core objective of this project is to comprehensively explore the relationship between national happiness and Olympic achievements. By integrating data from the World Happiness Report (WHR), Olympic medal counts, and various components of happiness scores including GDP, social support, and more, we aim to conduct five key analyses. These analyses are designed to shed light on whether factors related to national well - being, such as happiness, economic prosperity, social support, life expectancy, and perceptions of corruption, have a significant impact on a country's Olympic performance.

## Functionality

### Correlation Analysis
We conduct a statistical investigation to determine the correlation between the total number of Olympic medals a country wins and its happiness ladder score in the WHR. This analysis helps us understand if there is a general trend indicating that countries with more Olympic success tend to have higher levels of national happiness.

### Economic Influence Exploration
We explore the relationship between a country's economic prosperity, measured by the log of GDP per capita, and its performance in the Olympics. A higher GDP per capita often implies better resources for sports infrastructure, athlete training, and development programs. This analysis aims to reveal whether wealthier countries have a competitive edge in Olympic competitions.

### Social Support Assessment
We assess how a country's social support system, as reflected in the WHR, affects its Olympic performance. A strong social support system can provide athletes with the necessary emotional, financial, and institutional backing. By analyzing this relationship, we can understand if countries with more robust social support networks are more likely to produce successful Olympic athletes.

### Healthy Life Expectancy Analysis
By examining the relationship between a nation's healthy life expectancy and its medal counts, we aim to understand if a healthier population contributes to greater Olympic success. A higher life expectancy is often an indicator of a well - functioning healthcare system, a healthy lifestyle, and overall good living conditions, all of which can potentially benefit athletes.

### Corruption Perception Examination
We examine the link between lower levels of perceived corruption and higher medal counts. Corruption can undermine the fairness of sports competitions, limit access to resources for athletes, and disrupt the proper functioning of sports institutions. This analysis can highlight the systemic factors that may influence sports achievement and the importance of a corruption - free environment for Olympic success.

### Country and Regional Insights
We provide detailed insights into individual countries and regions. This allows for a more granular exploration of the relationship between happiness and sports performance, taking into account the unique cultural, social, and economic characteristics of each country or region.

## Features
- **Data - Driven Approach**: The project is firmly grounded in real - world data from reliable sources. This ensures the objectivity and credibility of our analysis, allowing us to draw meaningful conclusions based on empirical evidence.
- **Multifaceted Analysis**: By considering multiple factors related to national well - being and Olympic performance, we offer a comprehensive view of the relationship between the two. This holistic approach helps us capture the complex interplay of various elements that contribute to a country's Olympic success.
- **Open - Source and Transparent**: We use open - source datasets and make our code publicly available. This promotes transparency in our research process and allows other researchers to reproduce our results, validate our findings, and build upon our work.
=======
中英文对照项目术语表：
| 英文术语                         | 中文术语         | 简单解释                                                     
| :------------------------------ | :--------        | :-----------------------------------                         
| World Happiness Report (WHR)    | 世界幸福报告      | 全球幸福和福祉领域的权威出版物，基于多国数据和高质量分析。        
| Olympic Medals                  | 奥运奖牌          | 奥林匹克运动会中获得的金牌、银牌和铜牌数量，用于衡量国家的奥运成功。   
| Happiness Scores                | 幸福指数得分      | 基于世界幸福报告中人们对生活质量的0-10评分，用于衡量国家的幸福水平。 
| Log GDP per Capita              | 人均GDP对数       | 人均国内生产总值的对数值，用于衡量国家的经济繁荣程度。          
| Social Support                  | 社会支持          | 反映国家社会支持体系的强度，是世界幸福报告中幸福指数的重要组成部分。   
| Healthy Life Expectancy         | 健康预期寿命      | 一个人在健康状态下预期可以生存的年数，是衡量人口健康状况的重要指标。   
| Perceptions of Corruption       | 腐败感知          | 人们对本国腐败程度的主观评价，较低的腐败感知可能与更好的治理相关。    
| Country and Regional Deep Dives | 国家和地区深入剖析 | 对个别国家和地区进行详细分析，提供更细致的幸福与体育表现的关系研究。  
<!-- by 李荧桢 -->
