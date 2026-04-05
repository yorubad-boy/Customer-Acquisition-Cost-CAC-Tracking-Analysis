# Customer Acquisition Cost (CAC) Tracking Analysis

A multi-year performance analysis of customer acquisition across campaigns and channels — 281K customers, $11.72M revenue, 290M impressions.

Analyst: Sanni Sultan O.  |  Period: 2020–2024  |  Campaigns: 7  |  Channels: 7

## KPI Summary

|Metric| Value| vs. Prior Year |
|--|--|--|
| Total Customers Acquired| 281K|  +24.02%|
| Total Revenue| $11.72M|  +24.21%|
| Average CAC| $33.87|  +4.40%|
| Conversion Rate| 14.64%|  +0.37%|

![Dashboard Preview](projectdashboard-page-00001.jpg)

*Revenue growth (+24.21%) significantly outpaces CAC growth (+4.40%), confirming improving return on marketing investment year-over-year.*

## Dashboard Pages
| Page | Description |
|--|--|
| Executive Overview | Top-level KPIs, CAC monthly trend, campaign breakdown, funnel |
| Channel Performance | Channel-level spend, CAC, impressions, conversion rates |

## Campaign Performance

### Revenue & Spend by Campaign
| Campaign       |       Customers |  Revenue  |  Ad Spend  | ROAS |
| -- | -- | -- | -- | -- |
Black Friday Push   |    44K    |   $1.8M   |   $0.5M   |   3.60x
Holiday Sales       |    43K    |   $1.8M   |   $0.5M   |   3.60x
Brand Awareness     |    42K    |   $1.8M   |   $0.5M   |   3.60x
Discount Week       |    40K    |   $1.8M   |   $0.5M   |   3.60x
Summer Promo        |    39K    |   $1.7M   |   $0.4M   |   4.25x  ← Best ROAS
Reactivation Campaign |  37K    |   $1.5M   |   $0.5M   |   3.00x
Lead Gen Burst     |     36K    |   $1.3M   |   $0.4M   |   3.25x

## Key Findings

- Black Friday Push leads in customer volume at 44K
- Summer Promo achieves the best ROAS (4.25x) through efficient spend ($0.4M)
- Lead Gen Burst acquires the fewest customers but targets higher-value segments
- All campaigns maintain a healthy ROAS range of 3.00x–4.25x

## Channel Performance
### Customers vs. CAC by Channel
| Channel     |    Customers |  Ad Spend  |  Op. Cost  |  Impressions |  
|--|--|--|--|--|
|Email          |   43K   |     ~$470K   |   ~$45K    |   41.04M|
|Facebook Ads   |   39K   |     ~$467K   |   ~$43K    |   40.02M|
|Google Search  |   38K   |     ~$452K   |   ~$44K    |   41.22M|
|Instagram      |  44K    |    ~$441K    |  ~$43K     |  43.91M   ← Top volume|
|LinkedIn Ads   |   38K   |     ~$412K   |   ~$42K    |   41.47M|
|Referral       |   41K   |     ~$388K   |   ~$41K    |   44.09M   ← Most impressions|
|TikTok         |   38K   |     ~$354K   |   ~$36K    |   38.60M   ← Lowest spend|

## Key Findings

Instagram delivers the highest customer volume (44K) at mid-range spend
Referral leads in impressions (44.09M) with the second-lowest ad spend — best efficiency ratio
TikTok is the most capital-efficient channel, with room to scale
Email has the highest ad spend ($470K) relative to customer acquisition, indicating optimization potential

## Funnel Analysis
```
290M Impressions
      │
      ▼  CTR: 3.8%
 11M Clicks
      │
      ▼  Click → Lead: 27.3%
  3M Leads
      │
      ▼  Lead → Customer: 9.4%  ⬅ Primary optimization opportunity

281K Customers
```

## Funnel Insights

- Click-through rate (3.8%) is healthy across a mixed-channel portfolio
- Lead conversion from clicks (27.3%) indicates strong landing page and offer performance
- Lead-to-customer rate (9.4%) is the primary conversion gap — a 2% improvement would yield ~60K additional customers at zero extra acquisition spend

## Recommendations
### Immediate Actions

 * Implement lead nurturing sequences to improve the 9.4% lead-to-customer rate
 * Audit Email channel ROI — highest spend, not highest volume
 * Scale Black Friday Push and Holiday Sales budgets based on consistent performance

### Strategic Priorities

 * Expand Referral program — highest impressions, lowest spend, strong volume
 * Test TikTok spend ceiling — economics are favorable, scale is untested
 * Refresh Reactivation Campaign creative — only campaign below 3.5x ROAS
 * Apply Summer Promo efficiency tactics to other campaigns


## CAC Monthly Trend
CAC ranges between ~$20 and ~$70 across the year, with peak acquisition costs observed mid-year (July) and lowest costs in Q1. Seasonal campaigns (Black Friday, Holiday) correspond to efficient cost periods in Q4

## Data Structure
```
DATA/
├── DATASET.csv
├── DIM DATE.csv
```
## Dashboard
Built with Power BI — two-page interactive dashboard with year and campaign filters.
| Filter | Options |
| -- | -- |
| Year | 2020, 2021, 2022, 2023, 2024 |
| Campaign Name | All / Individual |

The dashboard can be interacted with through this link: https://app.powerbi.com/view?r=eyJrIjoiYWNlNWVjYmEtYjExMS00NjFjLTlhM2UtMGM2Njc0N2NkODgyIiwidCI6IjYyNjQwMmE4LWM4YmEtNGEzOC04ZjEwLTc2ZTE4MGM1MWJlMSJ9
