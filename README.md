# 📊 Sales Insights Dashboard

**Interactive Tableau dashboard** analyzing $10.8M+ revenue with dynamic measure switching and regional filters.

![Dashboard Preview](https://github.com/Siam-analytics/Sales-Performance-Viz/blob/main/Screenshot%202025-04-23%20164042.png)

## Key Features
- **Measure Toggle**: Switch between `Profit` and `Sales` metrics
- **Region Filter**: Drill down by continent (Americas, Europe, Asia)
- **Campaign Analysis**: Compare 5 marketing promotions
- **Leaderboards**: Top performers update dynamically (e.g., Monica Bell - $358K profit)

## Tech Stack
- **Frontend**: Tableau (Parameters, Calculated Fields)
- **Backend**: SQL aggregations, Excel data modeling
- **Data**: 12,964 customer plans, 4 sales channels

## Datasets Used
- <a href= "https://github.com/Siam-analytics/Sales-Performance-Viz/blob/main/DATA-20250322T123852Z-001.zip">SalesData</a>

## 🔍 Evidence-Based Insights

### 1. **Revenue Distribution**
- **Region Breakdown**
- **Winner**: North America (42% of total revenue)
- **Opportunity**: South America (8%) shows untapped potential

### 2. **Channel Performance**
| Metric        | Online | In-Store | Difference |
|--------------|--------|----------|------------|
| Sales Share  | 68.4%  | 31.6%    | **+116%**  |
| Avg. Rating  | 4.2    | 3.1      | **+35%**   |

**Recommendation**: Shift budget toward digital channels

### 3. **Campaign Effectiveness**
```mermaid
barChart
    title Profit by Campaign ($K)
    bar Winter Promo : 58
    bar Summer Deals : 49
    bar Spring Promo : 42
