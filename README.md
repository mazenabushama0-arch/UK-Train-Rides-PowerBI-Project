# UK Train Rides Analysis (Power BI)

> 🌐 Part of my data analytics portfolio: [YOUR-PORTFOLIO-URL](https://YOUR-PORTFOLIO-URL/projects/uk-train-rides) · 👤 [More projects on my GitHub](https://github.com/mazenabushama0-arch)

A 7-page Power BI report analyzing UK railway ticket transactions: sales trends, how customers buy, ticket and railcard mix, journey punctuality, delay reasons, and refunds.

## Business questions

- How do ticket sales trend month over month?
- How do customers buy tickets: online or at the station, by payment method, and at which hours?
- Which ticket types, ticket classes, and railcards drive sales?
- How punctual are journeys, and what are the main reasons for delay?
- How many refunds are requested, and what share is approved?

## Dashboard pages

| Page | What it shows |
|---|---|
| **Ticket Purchase Trends** | Total sales, MoM growth %, sales trend by month, online vs station purchases, payment method split, peak-hour purchases (6–9) |
| **Time Analysis Dashboard** | Monthly sales trend, MoM trend by ticket type, year and railcard slicers, journeys by arrival month |
| **Passenger Behavior Dashboard** | Sales by ticket type and railcard, average price, ticket type distribution |
| **Customer Insights & Behavior** | Transactions by ticket class and railcard, purchase type split, sales by arrival destination, purchase day/hour matrix |
| **Journey Performance & Delays** | Journey status breakdown, delay reasons, journey status by departure hour, purchase activity by hour |
| **Refund & Delay Analysis** | Total refund requests, refund approval rate, on-time %, reasons for delay, journey status per month, delay duration distribution |
| **Customer Segmentation** | Ticket type distribution, railcard usage, ticket type by departure hour |

## Key measures

`Total Sales` · `MoM Growth %` · `Avg Price` · `On-Time %` · `Refund Approval Rate` · `Total Refund Requests`

## Data

A single table of railway ticket transactions with fields such as transaction ID, purchase type, payment method, railcard, ticket class and type, price, purchase date and hour, arrival destination, journey status, reason for delay, delay minutes, and refund request.

## Tech stack

- Power BI Desktop
- DAX measures and calculated columns (date, hour, delay minutes)

## How to open

Download `UK Train Rides PowerBI Project.pbix` and open it with the latest Power BI Desktop.

<!-- Add screenshots to an /images folder, then uncomment:
## Screenshots
![Ticket Purchase Trends](images/ticket-purchase-trends.png)
![Journey Performance & Delays](images/journey-performance-delays.png)
-->

## Author

**Mazen Mohsen** · Senior Data & Merchandise Analyst · [LinkedIn](https://linkedin.com/in/mazen-abushama-934246398)
