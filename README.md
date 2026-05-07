# Quantium Store Trial Analysis 🏪

## 📌 Project Overview
Completed as part of the Quantium Data Analytics Job Simulation on Forage.
Evaluated the performance of three trial stores (77, 86, 88) by comparing 
them against matched control stores to determine whether the trial had a 
significant impact on sales.

## 🛠️ Tools Used
- R
- RStudio
- ggplot2
- dplyr
- lubridate

## 📂 Dataset
- Source: Quantium via Forage
- Monthly store level transaction data
- Columns: Store Number, Year Month, Total Sales, Customer Count

## ❓ Business Questions Answered
1. Which control stores best match each trial store?
2. Did the trial have a positive impact on sales?
3. Which trial store showed the strongest uplift?

## 📊 Methodology

### Control Store Matching
Control stores were selected based on the highest correlation score 
combining sales correlation and customer count correlation during 
the pre-trial period.

| Trial Store | Control Store | Correlation Score |
|---|---|---|
| Store 77 | Store 233 | 1.89 |
| Store 86 | Store 155 | High |
| Store 88 | Store 178 | High |

## 📈 Results

### Store 77
| Period | Trial Store Avg Sales | Control Store Avg Sales |
|---|---|---|
| Pre-Trial | $243 | $237 |
| During Trial | $268 | $233 |

💡 **Insight:** Store 77 showed a clear positive trial impact — sales 
increased while the control store declined.

### Store 86
| Period | Trial Store Avg Sales | Control Store Avg Sales |
|---|---|---|
| Pre-Trial | $874 | $901 |
| During Trial | $903 | $864 |

💡 **Insight:** Store 86 showed moderate positive impact — recovery 
and growth relative to a declining control store.

### Store 88
| Period | Trial Store Avg Sales | Control Store Avg Sales |
|---|---|---|
| Pre-Trial | $1,341 | $935 |
| During Trial | $1,390 | $952 |

💡 **Insight:** Store 88 showed the strongest and most consistent 
uplift — significantly outperforming its control store throughout 
the trial period.

## ✅ Key Findings
- All three trial stores outperformed their control stores
- Store 88 showed the strongest uplift and is recommended as a benchmark
- Store 86 demonstrated recovery and growth relative to its control
- Store 77 showed clear improvement against a declining control store

## 💡 Recommendations
- Roll out the trial strategy to additional stores
- Use Store 88 as a benchmark for future trials
- Investigate key drivers including customer traffic and transaction frequency
- Focus future trials on replicating conditions from high performing stores

## 🖼️ Charts


## 🔗 Full Project Write-Up
[View on Notion Portfolio](https://merciful-coconut-e1f.notion.site/Ompha-Ramaru-Data-Analyst-Portfolio-3498a09bc57780a8851ed774fa74d0b6)
