# Saudi POS | تحليل نقاط البيع في السعودية

**Power BI dashboard for exploring point-of-sale spending and transaction trends in Saudi Arabia.**

مشروع تحليلي باستخدام Power BI لاستكشاف الإنفاق عبر نقاط البيع، ومقارنة الأنشطة الاقتصادية، ومتابعة تطور العمليات عبر الزمن.

[Download the Power BI report](../../raw/refs/heads/main/Saudi_POS.pbix)

## Project at a glance

| Item | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Reporting period | January 2024 – August 2026 |
| Dataset | 864 monthly activity records |
| Coverage | 27 activities |
| Report language | Arabic |
| Measures | DAX |

## Dashboard pages

1. **نظرة عامة — Overview:** spending, transactions, average transaction value and monthly trends.
2. **مقارنة الأنشطة — Activity comparison:** compare activities and sectors, and explore each activity’s share of spending.
3. **التفاصيل والمنهجية — Details and methodology:** detailed data and the report’s analytical context.

## Key metrics

- Total POS spending in Saudi riyals, also displayed in billions.
- Total transaction count, also displayed in millions.
- Average transaction value = spending ÷ transactions.
- Activity share within the selected activity context.
- Year-over-year spending growth for the latest month in the current filter context, compared with the same month a year earlier.

## How to explore

1. Download **Saudi_POS.pbix** from this repository.
2. Open it in **Microsoft Power BI Desktop**.
3. Use the year, sector and activity filters to explore the report.

GitHub hosts the report file; open the downloaded PBIX in Power BI Desktop to interact with it.

## Files

| File | Purpose |
|---|---|
| `Saudi_POS.pbix` | Power BI report |
| `POS_Data.csv` | Monthly activity data used by the project |
| `README.md` | Project overview and usage guide |

## Data and methodology

The project documentation identifies the **Saudi Central Bank (SAMA) monthly statistics** as its data source:

[Saudi Central Bank — Monthly Statistics](https://www.sama.gov.sa/en-us/statistics/pages/monthlystatistics.aspx)

The included dataset contains month, activity, sector, spending in SAR and transaction count. It is a fixed snapshot covering January 2024 through August 2026; it does not update automatically when SAMA publishes new statistics. Derived indicators are calculated in DAX. Source statistics remain attributable to SAMA; this is an independent analytical project, with no implied affiliation or endorsement.

## المهارات المستخدمة

Power BI · DAX · Data Modeling · Data Visualization · Business Intelligence

## ملخص بالعربية

يعرض التقرير بيانات شهرية لنقاط البيع في السعودية خلال الفترة من يناير 2024 إلى أغسطس 2026، ويغطي 27 نشاطًا عبر 864 سجلًا. يركز على قيمة الإنفاق، وعدد العمليات، ومتوسط قيمة العملية، وحصة الأنشطة، والنمو السنوي. يمكن تنزيل الملف وفتحه في Power BI Desktop لاستكشاف الصفحات والفلاتر التفاعلية.
