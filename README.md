# 📊 Sales Performance Analysis

> Global sales data across **100 orders** | Jan 2010 – Jun 2017 | USD

---

## 📌 Key KPIs

| Metric | Value |
|---|---|
| Total Revenue | $137,348,768 |
| Total Profit | $44,168,198 |
| Overall Profit Margin | 32.16% |
| Avg Revenue / Order | $1,373,488 |
| Avg Profit / Order | $441,682 |
| Total Orders | 100 |
| Date Range | Jan 8, 2010 – Jun 17, 2017 |

---

## 💡 Key Insights

- **Concentration:** Top 3 item types contribute **70.7% of total revenue** and **63.2% of total profit**
- **Top 5 item types** contribute **83.9% of total revenue**
- **Channel mix:** Order count is split **50/50 Online vs Offline**, but revenue differs due to item-type mix
- **Time series completeness:** 24 of 90 months (26.7%) have zero revenue — treat seasonality/forecasting as exploratory unless dataset is confirmed complete
- **Recommended follow-ups:**
  - Focus growth on the largest profit pools (e.g., Cosmetics) and test scaling high-margin categories (e.g., Clothes)
  - Review Item Type × Channel mix to shift high-margin items into the best-performing channel
  - Validate whether missing/zero months reflect true inactivity or incomplete data extraction

---

## 🏷️ Performance by Item Type

| Item Type | Orders | Revenue | Profit | Avg Margin |
|---|---|---|---|---|
| Cosmetics | 13 | $36,601,510 | $14,556,049 | 39.77% |
| Office Supplies | 12 | $30,585,380 | $5,929,584 | 19.39% |
| Household | 9 | $29,889,712 | $7,412,606 | 24.80% |
| Baby Food | 7 | $10,350,328 | $3,886,644 | 37.55% |
| Clothes | 13 | $7,787,293 | $5,233,334 | 67.20% |
| Cereal | 7 | $5,322,899 | $2,292,443 | 43.07% |
| Meat | 2 | $4,503,676 | $610,610 | 13.56% |
| Personal Care | 10 | $3,980,905 | $1,220,622 | 30.66% |
| Vegetables | 6 | $3,089,057 | $1,265,820 | 40.98% |
| Beverages | 8 | $2,690,795 | $888,047 | 33.00% |
| Snacks | 3 | $2,080,733 | $751,944 | 36.14% |
| Fruits | 10 | $466,481 | $120,495 | 25.83% |

---
## 📊 Key Visualizations

### 1️⃣ Monthly Revenue
<img width="2001" height="894" alt="01_monthly_revenue" src="https://github.com/user-attachments/assets/5ab6aefe-0979-4b53-afea-f40c691b7c7d" />


### 2️⃣ Monthly Profit
<img width="2030" height="894" alt="02_monthly_profit" src="https://github.com/user-attachments/assets/0ea1ba0d-dedc-4121-a071-e16431544cdc" />


### 3️⃣ Revenue & Profit by Sales Channel
<img width="1404" height="904" alt="03_revenue_profit_by_channel" src="https://github.com/user-attachments/assets/f789ad8b-4aeb-4916-8475-876c62647d0b" />


### 4️⃣ Revenue by Region
<img width="1774" height="1221" alt="04_revenue_by_region" src="https://github.com/user-attachments/assets/18b3eed8-6073-42a0-811c-8ca807015daf" />


### 6️⃣ Top 10 Item Types by Revenue
<img width="1774" height="1089" alt="06_top10_itemtypes_by_revenue" src="https://github.com/user-attachments/assets/e2da69ff-7c32-48ad-9c2a-d22653a12076" />


### 7️⃣ Revenue Mix by Channel (Top Item Types)
<img width="1945" height="1048" alt="07_revenue_mix_by_channel_top10_items" src="https://github.com/user-attachments/assets/758a4bf5-993d-4893-b61d-b9e03892d322" />


### 8️⃣ Pareto Analysis (80/20 Rule)
<img width="2151" height="1157" alt="08_pareto_revenue_itemtype" src="https://github.com/user-attachments/assets/4261e734-a5e0-4310-975a-e5169494cfa3" />


## 🌍 Performance by Region

| Region | Orders | Revenue | Profit | Avg Margin |
|---|---|---|---|---|
| Sub-Saharan Africa | 36 | $39,672,031 | $12,183,211 | 35.09% |
| Europe | 22 | $33,368,932 | $11,082,939 | 37.58% |
| Asia | 11 | $21,347,091 | $6,113,846 | 36.45% |
| Australia and Oceania | 11 | $14,094,265 | $4,722,160 | 34.16% |
| Middle East and North Africa | 10 | $14,052,707 | $5,761,192 | 39.37% |
| Central America and the Caribbean | 7 | $9,170,385 | $2,846,908 | 39.23% |
| North America | 3 | $5,643,357 | $1,457,943 | 28.71% |

---

## 🔁 Performance by Sales Channel

| Sales Channel | Orders | Revenue | Profit | Avg Margin |
|---|---|---|---|---|
| Offline | 50 | $79,094,809 | $24,920,727 | 35.69% |
| Online | 50 | $58,253,959 | $19,247,472 | 36.73% |

---

## 📐 Pareto Analysis — Item Type

| Item Type | Orders | Revenue | Profit | Margin | Rev Share | Rev Cumulative | Profit Share | Profit Cumulative |
|---|---|---|---|---|---|---|---|---|
| Cosmetics | 13 | $36,601,510 | $14,556,049 | 39.77% | 26.65% | 26.65% | 32.96% | 32.96% |
| Office Supplies | 12 | $30,585,380 | $5,929,584 | 19.39% | 22.27% | 48.92% | 13.43% | 46.38% |
| Household | 9 | $29,889,712 | $7,412,606 | 24.80% | 21.76% | 70.68% | 16.78% | 63.16% |
| Baby Food | 7 | $10,350,328 | $3,886,644 | 37.55% | 7.54% | 78.21% | 8.80% | 71.96% |
| Clothes | 13 | $7,787,293 | $5,233,334 | 67.20% | 5.67% | 83.88% | 11.85% | 83.81% |
| Cereal | 7 | $5,322,899 | $2,292,443 | 43.07% | 3.88% | 87.76% | 5.19% | 89.00% |
| Meat | 2 | $4,503,676 | $610,610 | 13.56% | 3.28% | 91.04% | 1.38% | 90.38% |
| Personal Care | 10 | $3,980,905 | $1,220,622 | 30.66% | 2.90% | 93.94% | 2.76% | 93.15% |
| Vegetables | 6 | $3,089,057 | $1,265,820 | 40.98% | 2.25% | 96.19% | 2.87% | 96.01% |
| Beverages | 8 | $2,690,795 | $888,047 | 33.00% | 1.96% | 98.15% | 2.01% | 98.02% |
| Snacks | 3 | $2,080,733 | $751,944 | 36.14% | 1.51% | 99.66% | 1.70% | 99.73% |
| Fruits | 10 | $466,481 | $120,495 | 25.83% | 0.34% | 100.00% | 0.27% | 100.00% |

---

## 🔀 Revenue by Item Type × Sales Channel

| Item Type | Offline | Online | Total |
|---|---|---|---|
| Cosmetics | $18,252,663 | $18,348,847 | $36,601,510 |
| Office Supplies | $13,544,517 | $17,040,863 | $30,585,380 |
| Household | $29,701,260 | $188,452 | $29,889,712 |
| Baby Food | $6,151,737 | $4,198,590 | $10,350,328 |
| Clothes | $4,466,383 | $3,320,910 | $7,787,293 |
| Cereal | $773,638 | $4,549,261 | $5,322,899 |
| Meat | $0 | $4,503,676 | $4,503,676 |
| Personal Care | $3,297,806 | $683,099 | $3,980,905 |
| Vegetables | $803,731 | $2,285,326 | $3,089,057 |
| Beverages | $1,973,351 | $717,444 | $2,690,795 |
| Snacks | $0 | $2,080,733 | $2,080,733 |
| Fruits | $129,724 | $336,757 | $466,481 |

---

## 🔀 Profit by Item Type × Sales Channel

| Item Type | Offline | Online | Total |
|---|---|---|---|
| Cosmetics | $7,258,899 | $7,297,150 | $14,556,049 |
| Office Supplies | $2,625,874 | $3,303,710 | $5,929,584 |
| Household | $7,365,870 | $46,736 | $7,412,606 |
| Baby Food | $2,310,034 | $1,576,609 | $3,886,644 |
| Clothes | $3,001,566 | $2,231,768 | $5,233,334 |
| Cereal | $333,187 | $1,959,256 | $2,292,443 |
| Meat | $0 | $610,610 | $610,610 |
| Personal Care | $1,011,171 | $209,451 | $1,220,622 |
| Vegetables | $329,349 | $936,470 | $1,265,820 |
| Beverages | $651,268 | $236,779 | $888,047 |
| Snacks | $0 | $751,944 | $751,944 |
| Fruits | $33,509 | $86,987 | $120,496 |

---

## 🌐 Profit by Region (Pivot)

| Region | Total Profit |
|---|---|
| Sub-Saharan Africa | $12,183,211 |
| Europe | $11,082,939 |
| Asia | $6,113,846 |
| Middle East and North Africa | $5,761,192 |
| Australia and Oceania | $4,722,160 |
| Central America and the Caribbean | $2,846,908 |
| North America | $1,457,943 |
| **Grand Total** | **$44,168,198** |

---

## 📅 Monthly Revenue Trend

| Month | Revenue | Profit | Margin |
|---|---|---|---|
| Jan 2010 | $1,082,418 | $727,423 | 67.20% |
| Feb 2010 | $3,162,705 | $1,257,776 | 39.77% |
| Mar 2010 | $247,956 | $166,635 | 67.20% |
| Apr 2010 | $0 | $0 | 0.00% |
| May 2010 | $0 | $0 | 0.00% |
| Jun 2010 | $2,533,654 | $951,411 | 37.55% |
| Jul 2010 | $0 | $0 | 0.00% |
| Aug 2010 | $0 | $0 | 0.00% |
| Sep 2010 | $0 | $0 | 0.00% |
| Oct 2010 | $54,319 | $14,031 | 25.83% |
| Nov 2010 | $6,064,934 | $1,495,393 | 24.66% |
| Dec 2010 | $3,458,252 | $1,375,312 | 39.77% |
| Jan 2011 | $3,000,722 | $779,849 | 25.99% |
| Feb 2011 | $0 | $0 | 0.00% |
| Mar 2011 | $519,348 | $202,057 | 38.91% |
| Apr 2011 | $2,798,046 | $693,912 | 24.80% |
| May 2011 | $623,289 | $225,247 | 36.14% |
| Jun 2011 | $0 | $0 | 0.00% |
| Jul 2011 | $272,410 | $89,904 | 33.00% |
| Aug 2011 | $0 | $0 | 0.00% |
| Sep 2011 | $0 | $0 | 0.00% |
| Oct 2011 | $574,952 | $235,601 | 40.98% |
| Nov 2011 | $3,593,377 | $696,648 | 19.39% |
| Dec 2011 | $77,575 | $22,932 | 29.56% |
| Jan 2012 | $824,432 | $159,833 | 19.39% |
| Feb 2012 | $8,570,413 | $2,265,306 | 26.43% |
| Mar 2012 | $707,696 | $283,800 | 40.10% |
| Apr 2012 | $0 | $0 | 0.00% |
| May 2012 | $4,870 | $1,258 | 25.83% |
| Jun 2012 | $380,513 | $255,718 | 67.20% |
| Jul 2012 | $5,807,207 | $1,609,445 | 27.71% |
| Aug 2012 | $5,665,347 | $1,613,431 | 28.48% |
| Sep 2012 | $2,868,038 | $858,106 | 29.92% |
| Oct 2012 | $3,812,933 | $1,516,683 | 39.78% |
| Nov 2012 | $5,508,429 | $1,085,877 | 19.71% |
| Dec 2012 | $0 | $0 | 0.00% |
| Jan 2013 | $1,212,580 | $455,335 | 37.55% |
| Feb 2013 | $140,287 | $60,418 | 43.07% |
| Mar 2013 | $835,759 | $359,941 | 43.07% |
| Apr 2013 | $0 | $0 | 0.00% |
| May 2013 | $3,262,562 | $632,513 | 19.39% |
| Jun 2013 | $3,296,425 | $639,078 | 19.39% |
| Jul 2013 | $4,220,729 | $1,678,541 | 39.77% |
| Aug 2013 | $4,324,782 | $1,719,922 | 39.77% |
| Sep 2013 | $89,624 | $23,150 | 25.83% |
| Oct 2013 | $71,253 | $18,405 | 25.83% |
| Nov 2013 | $2,702,770 | $1,074,864 | 39.77% |
| Dec 2013 | $0 | $0 | 0.00% |
| Jan 2014 | $173,676 | $53,253 | 30.66% |
| Feb 2014 | $400,559 | $122,819 | 30.66% |
| Mar 2014 | $1,419,102 | $532,886 | 37.55% |
| Apr 2014 | $3,174,803 | $1,259,743 | 39.68% |
| May 2014 | $1,431,772 | $603,600 | 42.16% |
| Jun 2014 | $1,901,836 | $714,157 | 37.55% |
| Jul 2014 | $243,134 | $80,242 | 33.00% |
| Aug 2014 | $1,613,982 | $530,697 | 32.88% |
| Sep 2014 | $0 | $0 | 0.00% |
| Oct 2014 | $50,363 | $13,009 | 25.83% |
| Nov 2014 | $1,747,515 | $869,823 | 49.77% |
| Dec 2014 | $4,647,150 | $1,152,486 | 24.80% |
| Jan 2015 | $5,513,228 | $1,367,273 | 24.80% |
| Feb 2015 | $2,003,911 | $780,096 | 38.93% |
| Mar 2015 | $324,971 | $122,030 | 37.55% |
| Apr 2015 | $257,654 | $85,034 | 33.00% |
| May 2015 | $802,334 | $539,196 | 67.20% |
| Jun 2015 | $0 | $0 | 0.00% |
| Jul 2015 | $0 | $0 | 0.00% |
| Aug 2015 | $967,438 | $296,635 | 30.66% |
| Sep 2015 | $6,279 | $1,622 | 25.83% |
| Oct 2015 | $0 | $0 | 0.00% |
| Nov 2015 | $2,552,168 | $804,654 | 31.53% |
| Dec 2015 | $0 | $0 | 0.00% |
| Jan 2016 | $0 | $0 | 0.00% |
| Feb 2016 | $0 | $0 | 0.00% |
| Mar 2016 | $0 | $0 | 0.00% |
| Apr 2016 | $197,883 | $85,224 | 43.07% |
| May 2016 | $0 | $0 | 0.00% |
| Jun 2016 | $228,779 | $93,748 | 40.98% |
| Jul 2016 | $940,312 | $526,460 | 55.99% |
| Aug 2016 | $2,836,991 | $1,128,242 | 39.77% |
| Sep 2016 | $0 | $0 | 0.00% |
| Oct 2016 | $414,371 | $127,054 | 30.66% |
| Nov 2016 | $221,117 | $72,976 | 33.00% |
| Dec 2016 | $7,533,414 | $2,870,135 | 38.10% |
| Jan 2017 | $2,914,130 | $879,507 | 30.18% |
| Feb 2017 | $7,115,009 | $1,891,272 | 26.58% |
| Mar 2017 | $246,416 | $75,556 | 30.66% |
| Apr 2017 | $0 | $0 | 0.00% |
| May 2017 | $1,317,326 | $476,184 | 36.15% |
| Jun 2017 | $1,780,539 | $766,835 | 43.07% |

---

## 🔮 Forecast (Jul–Sep 2017)

| Month | Forecast Revenue | Forecast Profit | Assumed Margin |
|---|---|---|---|
| Jul 2017 | $1,903,039 | $664,732 | 34.93% |
| Aug 2017 | $1,899,082 | $663,350 | 34.93% |
| Sep 2017 | $1,895,125 | $661,968 | 34.93% |


---

## 🚨 Top 10 Orders by Revenue

| Ship Date | Country | Region | Item Type | Channel | Revenue | Profit | Margin | Z-Score |
|---|---|---|---|---|---|---|---|---|
| Feb 13, 2017 | Honduras | Central America | Household | Offline | $5,997,055 | $1,487,261 | 24.80% | 3.183 |
| Jan 3, 2015 | Myanmar | Asia | Household | Offline | $5,513,228 | $1,367,273 | 24.80% | 2.850 |
| Nov 17, 2010 | Lithuania | Europe | Office Supplies | Offline | $5,396,577 | $1,046,234 | 19.39% | 2.769 |
| Dec 12, 2014 | Mexico | North America | Household | Offline | $4,647,150 | $1,152,486 | 24.80% | 2.253 |
| Aug 5, 2012 | Brunei | Asia | Office Supplies | Online | $4,368,317 | $846,885 | 19.39% | 2.062 |
| Aug 16, 2013 | Pakistan | Middle East & NA | Cosmetics | Offline | $4,324,782 | $1,719,922 | 39.77% | 2.032 |
| Jul 8, 2013 | Samoa | Australia & Oceania | Cosmetics | Online | $4,220,729 | $1,678,541 | 39.77% | 1.960 |
| Dec 31, 2016 | Iceland | Europe | Cosmetics | Online | $3,876,652 | $1,541,705 | 39.77% | 1.723 |
| Oct 20, 2012 | Switzerland | Europe | Cosmetics | Offline | $3,786,589 | $1,505,888 | 39.77% | 1.661 |
| Nov 15, 2011 | Cameroon | Sub-Saharan Africa | Office Supplies | Online | $3,593,377 | $696,648 | 19.39% | 1.528 |

---

## 📉 Top 10 Highest Profit Margin Orders

| Ship Date | Country | Region | Item Type | Channel | Revenue | Profit | Margin | Z-Score |
|---|---|---|---|---|---|---|---|---|
| Jul 9, 2016 | Belize | Central America | Clothes | Offline | $600,821 | $403,773 | 67.20% | 2.181 |
| Aug 10, 2012 | Lebanon | Middle East & NA | Clothes | Online | $861,564 | $579,001 | 67.20% | 2.181 |
| Nov 18, 2015 | Myanmar | Asia | Clothes | Online | $648,030 | $435,499 | 67.20% | 2.181 |
| Mar 9, 2011 | Mali | Sub-Saharan Africa | Clothes | Online | $97,041 | $65,215 | 67.20% | 2.181 |
| Nov 14, 2014 | Macedonia | Europe | Clothes | Offline | $856,974 | $575,916 | 67.20% | 2.181 |
| Jan 8, 2010 | Fiji | Australia & Oceania | Clothes | Offline | $1,082,418 | $727,423 | 67.20% | 2.181 |
| Nov 17, 2010 | Libya | Middle East & NA | Clothes | Offline | $668,356 | $449,159 | 67.20% | 2.181 |
| May 28, 2015 | Madagascar | Sub-Saharan Africa | Clothes | Offline | $802,334 | $539,196 | 67.20% | 2.181 |
| Aug 19, 2014 | Cape Verde | Sub-Saharan Africa | Clothes | Offline | $455,479 | $306,098 | 67.20% | 2.181 |
| Jan 3, 2017 | Bangladesh | Asia | Clothes | Online | $902,981 | $606,835 | 67.20% | 2.181 |

---

## 📉 Bottom 10 Lowest Profit Margin Orders

| Ship Date | Country | Region | Item Type | Channel | Revenue | Profit | Margin | Z-Score |
|---|---|---|---|---|---|---|---|---|
| Nov 9, 2012 | East Timor | Australia & Oceania | Meat | Online | $2,492,526 | $337,938 | 13.56% | -1.594 |
| Jan 23, 2017 | The Gambia | Sub-Saharan Africa | Meat | Online | $2,011,150 | $272,672 | 13.56% | -1.594 |
| Jan 13, 2012 | Mauritania | Sub-Saharan Africa | Office Supplies | Offline | $824,432 | $159,833 | 19.39% | -1.184 |
| Aug 5, 2014 | Russia | Europe | Office Supplies | Offline | $1,158,503 | $224,599 | 19.39% | -1.184 |
| Jun 2, 2013 | Rwanda | Sub-Saharan Africa | Office Supplies | Offline | $3,296,425 | $639,078 | 19.39% | -1.184 |
| Feb 28, 2012 | Bulgaria | Europe | Office Supplies | Online | $2,596,374 | $503,359 | 19.39% | -1.184 |
| Jul 1, 2012 | Sierra Leone | Sub-Saharan Africa | Office Supplies | Offline | $2,251,233 | $436,446 | 19.39% | -1.184 |
| May 20, 2013 | Turkmenistan | Asia | Office Supplies | Online | $3,262,562 | $632,513 | 19.39% | -1.184 |
| Nov 25, 2015 | Australia | Australia & Oceania | Office Supplies | Online | $1,904,138 | $369,155 | 19.39% | -1.184 |
| Aug 5, 2012 | Brunei | Asia | Office Supplies | Online | $4,368,317 | $846,885 | 19.39% | -1.184 |

---

## 🗂️ Raw Data — All 100 Orders

| Region | Country | Item Type | Channel | Priority | Ship Date | Unit Cost | Revenue | Profit | Margin | Expense |
|---|---|---|---|---|---|---|---|---|---|---|
| Australia and Oceania | Tuvalu | Baby Food | Offline | H | 27/06/2010 | $159.42 | $2,533,654 | $951,411 | 37.55% | $1,582,244 |
| Central America and the Caribbean | Grenada | Cereal | Online | C | 15/09/2012 | $117.11 | $576,783 | $248,406 | 43.07% | $328,376 |
| Europe | Russia | Office Supplies | Offline | L | 05/08/2014 | $524.96 | $1,158,503 | $224,599 | 19.39% | $933,904 |
| Sub-Saharan Africa | Sao Tome and Principe | Fruits | Online | C | 07/05/2014 | $6.92 | $75,592 | $19,526 | 25.83% | $56,066 |
| Sub-Saharan Africa | Rwanda | Office Supplies | Offline | L | 02/06/2013 | $524.96 | $3,296,425 | $639,078 | 19.39% | $2,657,348 |
| Australia and Oceania | Solomon Islands | Baby Food | Online | C | 21/02/2015 | $159.42 | $759,203 | $285,088 | 37.55% | $474,115 |
| Sub-Saharan Africa | Angola | Household | Offline | M | 27/04/2011 | $502.54 | $2,798,046 | $693,912 | 24.80% | $2,104,135 |
| Sub-Saharan Africa | Burkina Faso | Vegetables | Online | H | 27/07/2012 | $90.93 | $1,245,113 | $510,217 | 40.98% | $734,896 |
| Sub-Saharan Africa | Republic of the Congo | Personal Care | Offline | M | 25/08/2015 | $56.67 | $496,101 | $152,114 | 30.66% | $343,987 |
| Sub-Saharan Africa | Senegal | Cereal | Online | H | 30/05/2014 | $117.11 | $1,356,180 | $584,074 | 43.07% | $772,106 |
| Asia | Kyrgyzstan | Vegetables | Online | H | 07/12/2011 | $90.93 | $19,103 | $7,828 | 40.98% | $11,275 |
| Sub-Saharan Africa | Cape Verde | Clothes | Offline | H | 19/08/2014 | $35.84 | $455,479 | $306,098 | 67.20% | $149,381 |
| Asia | Bangladesh | Clothes | Online | L | 03/01/2017 | $35.84 | $902,981 | $606,835 | 67.20% | $296,146 |
| Central America and the Caribbean | Honduras | Household | Offline | H | 13/02/2017 | $502.54 | $5,997,055 | $1,487,261 | 24.80% | $4,509,794 |
| Asia | Mongolia | Personal Care | Offline | C | 23/02/2014 | $56.67 | $400,559 | $122,819 | 30.66% | $277,740 |
| Europe | Bulgaria | Clothes | Online | M | 06/03/2012 | $35.84 | $182,825 | $122,865 | 67.20% | $59,960 |
| Asia | Sri Lanka | Cosmetics | Offline | M | 18/12/2016 | $263.33 | $3,039,414 | $1,208,744 | 39.77% | $1,830,670 |
| Sub-Saharan Africa | Cameroon | Beverages | Offline | C | 18/04/2015 | $31.79 | $257,654 | $85,034 | 33.00% | $172,620 |
| Asia | Turkmenistan | Household | Offline | L | 20/01/2011 | $502.54 | $2,559,474 | $634,746 | 24.80% | $1,924,728 |
| Australia and Oceania | East Timor | Meat | Online | L | 09/11/2012 | $364.69 | $2,492,526 | $337,938 | 13.56% | $2,154,589 |
| Europe | Norway | Baby Food | Online | L | 28/06/2014 | $159.42 | $1,901,836 | $714,157 | 37.55% | $1,187,679 |
| Europe | Portugal | Baby Food | Online | H | 09/03/2015 | $159.42 | $324,971 | $122,030 | 37.55% | $202,942 |
| Central America and the Caribbean | Honduras | Snacks | Online | L | 26/07/2016 | $97.44 | $339,491 | $122,687 | 36.14% | $216,804 |
| Australia and Oceania | New Zealand | Fruits | Online | H | 10/04/2014 | $6.92 | $20,405 | $5,271 | 25.83% | $15,134 |
| Europe | Moldova | Personal Care | Online | L | 05/10/2016 | $56.67 | $414,371 | $127,054 | 30.66% | $287,317 |
| Europe | France | Cosmetics | Online | H | 06/05/2017 | $263.33 | $793,518 | $315,574 | 39.77% | $477,944 |
| Australia and Oceania | Kiribati | Fruits | Online | M | 11/10/2014 | $6.92 | $50,363 | $13,009 | 25.83% | $37,354 |
| Sub-Saharan Africa | Mali | Fruits | Online | L | 05/10/2010 | $6.92 | $54,319 | $14,031 | 25.83% | $40,288 |
| Europe | Norway | Beverages | Offline | C | 30/07/2014 | $31.79 | $243,134 | $80,242 | 33.00% | $162,892 |
| Sub-Saharan Africa | The Gambia | Household | Offline | L | 06/09/2012 | $502.54 | $1,583,800 | $392,780 | 24.80% | $1,191,020 |
| Europe | Switzerland | Cosmetics | Offline | M | 20/10/2012 | $263.33 | $3,786,589 | $1,505,888 | 39.77% | $2,280,701 |
| Sub-Saharan Africa | South Sudan | Personal Care | Offline | C | 28/01/2014 | $56.67 | $173,676 | $53,253 | 30.66% | $120,424 |
| Australia and Oceania | Australia | Office Supplies | Online | C | 25/11/2015 | $524.96 | $1,904,138 | $369,155 | 19.39% | $1,534,983 |
| Asia | Myanmar | Household | Offline | H | 03/01/2015 | $502.54 | $5,513,228 | $1,367,273 | 24.80% | $4,145,955 |
| Sub-Saharan Africa | Djibouti | Snacks | Online | M | 25/02/2017 | $97.44 | $1,117,954 | $404,011 | 36.14% | $713,943 |
| Central America and the Caribbean | Costa Rica | Personal Care | Offline | L | 21/05/2017 | $56.67 | $523,808 | $160,610 | 30.66% | $363,198 |
| Middle East and North Africa | Syria | Fruits | Online | L | 12/03/2011 | $6.92 | $35,305 | $9,119 | 25.83% | $26,185 |
| Sub-Saharan Africa | The Gambia | Meat | Online | M | 23/01/2017 | $364.69 | $2,011,150 | $272,672 | 13.56% | $1,738,477 |
| Asia | Brunei | Office Supplies | Online | L | 05/08/2012 | $524.96 | $4,368,317 | $846,885 | 19.39% | $3,521,432 |
| Europe | Bulgaria | Office Supplies | Online | M | 28/02/2012 | $524.96 | $2,596,374 | $503,359 | 19.39% | $2,093,016 |
| Sub-Saharan Africa | Niger | Personal Care | Online | H | 28/03/2017 | $56.67 | $246,416 | $75,556 | 30.66% | $170,860 |
| Middle East and North Africa | Azerbaijan | Cosmetics | Online | M | 25/02/2010 | $263.33 | $3,162,705 | $1,257,776 | 39.77% | $1,904,929 |
| Sub-Saharan Africa | The Gambia | Cereal | Offline | H | 06/08/2012 | $117.11 | $435,467 | $187,545 | 43.07% | $247,922 |
| Europe | Slovakia | Vegetables | Online | H | 11/10/2012 | $90.93 | $26,344 | $10,795 | 40.98% | $15,549 |
| Asia | Myanmar | Clothes | Online | H | 18/11/2015 | $35.84 | $648,030 | $435,499 | 67.20% | $212,531 |
| Sub-Saharan Africa | Comoros | Cereal | Offline | H | 29/04/2016 | $117.11 | $197,883 | $85,224 | 43.07% | $112,660 |
| Europe | Iceland | Cosmetics | Online | C | 31/12/2016 | $263.33 | $3,876,652 | $1,541,705 | 39.77% | $2,334,947 |
| Europe | Switzerland | Personal Care | Online | M | 31/01/2011 | $56.67 | $22,312 | $6,841 | 30.66% | $15,471 |
| Europe | Macedonia | Clothes | Offline | C | 14/11/2014 | $35.84 | $856,974 | $575,916 | 67.20% | $281,057 |
| Sub-Saharan Africa | Mauritania | Office Supplies | Offline | C | 13/01/2012 | $524.96 | $824,432 | $159,833 | 19.39% | $664,599 |
| Europe | Albania | Clothes | Online | C | 18/03/2010 | $35.84 | $247,956 | $166,635 | 67.20% | $81,321 |
| Sub-Saharan Africa | Lesotho | Fruits | Online | L | 18/09/2013 | $6.92 | $89,624 | $23,150 | 25.83% | $66,474 |
| Middle East and North Africa | Saudi Arabia | Cereal | Online | M | 28/03/2013 | $117.11 | $835,759 | $359,941 | 43.07% | $475,818 |
| Sub-Saharan Africa | Sierra Leone | Office Supplies | Offline | M | 01/07/2012 | $524.96 | $2,251,233 | $436,446 | 19.39% | $1,814,787 |
| Sub-Saharan Africa | Sao Tome and Principe | Fruits | Offline | H | 24/10/2013 | $6.92 | $71,253 | $18,405 | 25.83% | $52,848 |
| Sub-Saharan Africa | Cote d'Ivoire | Clothes | Online | C | 27/06/2012 | $35.84 | $380,513 | $255,718 | 67.20% | $124,795 |
| Australia and Oceania | Fiji | Clothes | Offline | C | 08/01/2010 | $35.84 | $1,082,418 | $727,423 | 67.20% | $354,995 |
| Europe | Austria | Cosmetics | Offline | H | 03/02/2015 | $263.33 | $1,244,708 | $495,008 | 39.77% | $749,701 |
| Europe | United Kingdom | Household | Online | L | 14/02/2012 | $502.54 | $188,452 | $46,736 | 24.80% | $141,716 |
| Sub-Saharan Africa | Djibouti | Cosmetics | Offline | H | 19/04/2014 | $263.33 | $3,154,398 | $1,254,472 | 39.77% | $1,899,926 |
| Australia and Oceania | Australia | Cereal | Offline | H | 07/02/2013 | $117.11 | $140,287 | $60,418 | 43.07% | $79,869 |
| Europe | San Marino | Baby Food | Online | L | 07/01/2013 | $159.42 | $1,212,580 | $455,335 | 37.55% | $757,245 |
| Sub-Saharan Africa | Cameroon | Office Supplies | Online | M | 15/11/2011 | $524.96 | $3,593,377 | $696,648 | 19.39% | $2,896,729 |
| Middle East and North Africa | Libya | Clothes | Offline | H | 17/11/2010 | $35.84 | $668,356 | $449,159 | 67.20% | $219,197 |
| Central America and the Caribbean | Haiti | Cosmetics | Offline | H | 16/11/2013 | $263.33 | $745,426 | $296,448 | 39.77% | $448,978 |
| Sub-Saharan Africa | Rwanda | Cosmetics | Offline | H | 25/11/2013 | $263.33 | $1,957,344 | $778,416 | 39.77% | $1,178,928 |
| Sub-Saharan Africa | Gabon | Personal Care | Offline | L | 07/09/2012 | $56.67 | $707,455 | $216,919 | 30.66% | $490,536 |
| Central America and the Caribbean | Belize | Clothes | Offline | M | 09/07/2016 | $35.84 | $600,821 | $403,773 | 67.20% | $197,048 |
| Europe | Lithuania | Office Supplies | Offline | H | 17/11/2010 | $524.96 | $5,396,577 | $1,046,234 | 19.39% | $4,350,344 |
| Sub-Saharan Africa | Madagascar | Clothes | Offline | L | 28/05/2015 | $35.84 | $802,334 | $539,196 | 67.20% | $263,137 |
| Asia | Turkmenistan | Office Supplies | Online | M | 20/05/2013 | $524.96 | $3,262,562 | $632,513 | 19.39% | $2,630,050 |
| Middle East and North Africa | Libya | Fruits | Online | L | 30/09/2015 | $6.92 | $6,279 | $1,622 | 25.83% | $4,657 |
| Sub-Saharan Africa | Dem. Rep. of the Congo | Beverages | Online | C | 15/07/2011 | $31.79 | $272,410 | $89,904 | 33.00% | $182,506 |
| Sub-Saharan Africa | Djibouti | Cereal | Online | H | 17/06/2017 | $117.11 | $1,780,539 | $766,835 | 43.07% | $1,013,704 |
| Middle East and North Africa | Pakistan | Cosmetics | Offline | L | 16/08/2013 | $263.33 | $4,324,782 | $1,719,922 | 39.77% | $2,604,860 |
| North America | Mexico | Household | Offline | C | 12/12/2014 | $502.54 | $4,647,150 | $1,152,486 | 24.80% | $3,494,663 |
| Australia and Oceania | Federated States of Micronesia | Beverages | Online | C | 15/11/2014 | $31.79 | $445,034 | $146,875 | 33.00% | $298,158 |
| Asia | Laos | Vegetables | Offline | C | 23/10/2011 | $90.93 | $574,952 | $235,601 | 40.98% | $339,351 |
| Europe | Monaco | Baby Food | Offline | H | 06/02/2012 | $159.42 | $2,198,982 | $825,738 | 37.55% | $1,373,244 |
| Australia and Oceania | Samoa | Cosmetics | Online | H | 08/07/2013 | $263.33 | $4,220,729 | $1,678,541 | 39.77% | $2,542,188 |
| Europe | Spain | Household | Offline | L | 30/11/2012 | $502.54 | $3,015,903 | $747,939 | 24.80% | $2,267,963 |
| Middle East and North Africa | Lebanon | Clothes | Online | L | 10/08/2012 | $35.84 | $861,564 | $579,001 | 67.20% | $282,563 |
| Middle East and North Africa | Iran | Cosmetics | Online | H | 12/08/2016 | $263.33 | $2,836,991 | $1,128,242 | 39.77% | $1,708,748 |
| Sub-Saharan Africa | Zambia | Snacks | Online | L | 01/05/2011 | $97.44 | $623,289 | $225,247 | 36.14% | $398,042 |
| Sub-Saharan Africa | Kenya | Vegetables | Online | L | 04/07/2012 | $90.93 | $994,765 | $407,630 | 40.98% | $587,135 |
| North America | Mexico | Personal Care | Offline | L | 20/03/2012 | $56.67 | $524,870 | $160,935 | 30.66% | $363,935 |
| Sub-Saharan Africa | Sao Tome and Principe | Beverages | Offline | C | 21/01/2011 | $31.79 | $418,936 | $138,262 | 33.00% | $280,674 |
| Sub-Saharan Africa | The Gambia | Baby Food | Offline | M | 20/03/2014 | $159.42 | $1,419,102 | $532,886 | 37.55% | $886,216 |
| Middle East and North Africa | Kuwait | Fruits | Online | M | 18/05/2012 | $6.92 | $4,870 | $1,258 | 25.83% | $3,612 |
| Europe | Slovenia | Beverages | Offline | C | 25/11/2016 | $31.79 | $221,117 | $72,976 | 33.00% | $148,141 |
| Sub-Saharan Africa | Sierra Leone | Office Supplies | Offline | H | 14/12/2016 | $524.96 | $617,347 | $119,685 | 19.39% | $497,662 |
| Australia and Oceania | Australia | Beverages | Offline | H | 07/11/2014 | $31.79 | $445,508 | $147,032 | 33.00% | $298,476 |
| Middle East and North Africa | Azerbaijan | Office Supplies | Online | M | 24/07/2012 | $524.96 | $1,316,095 | $255,151 | 19.39% | $1,060,944 |
| Europe | Romania | Cosmetics | Online | H | 25/12/2010 | $263.33 | $3,458,252 | $1,375,312 | 39.77% | $2,082,940 |
| Central America and the Caribbean | Nicaragua | Beverages | Offline | C | 21/03/2011 | $31.79 | $387,002 | $127,723 | 33.00% | $259,279 |
| Sub-Saharan Africa | Mali | Clothes | Online | M | 09/03/2011 | $35.84 | $97,041 | $65,215 | 67.20% | $31,826 |
| Asia | Malaysia | Fruits | Offline | L | 28/12/2011 | $6.92 | $58,471 | $15,103 | 25.83% | $43,368 |
| Sub-Saharan Africa | Sierra Leone | Vegetables | Offline | C | 29/06/2016 | $90.93 | $228,779 | $93,748 | 40.98% | $135,031 |
| North America | Mexico | Personal Care | Offline | M | 08/08/2015 | $56.67 | $471,337 | $144,521 | 30.66% | $326,816 |
| Sub-Saharan Africa | Mozambique | Household | Offline | L | 15/02/2012 | $502.54 | $3,586,605 | $889,473 | 24.80% | $2,697,132 |

---

*Source: `Sales_Excel_Report_Deep.xlsx` | 100 orders | Jan 2010 – Jun 2017*
