# Global Unicorn Analysis Dashboard

## Overview

This Power BI report provides a comprehensive analysis of the global unicorn landscape — companies valued at over $1 billion. The dashboard explores trends across time, industries, and geography, offering insights into valuation growth, investor diversity, and capital efficiency using valuation multiples.

## Purpose

The purpose of this dashboard is to:

- Analyze the development of unicorn companies over time

- Compare industry performance based on valuation multiples and investor engagement

- Identify top-performing global hubs in valuation and investment activity

- Provide decision-makers with insights into which sectors and regions drive the unicorn economy

##  Key Insights

### Unicorn Development

- The number of unicorns surged in recent years, peaking in 2021 with over 500 new unicorns

- Most unicorns reached $1B valuation in under 8 years, with a median time of 7 years

- Early-stage unicorns often display higher valuation multiples, showing high value generated per dollar of funding

### Industry Performance

- Fintech leads in unicorn count, reflecting maturity and consistent performance.

- Artificial Intelligence stands out for high average valuation and the fastest YoY growth.

- Industries like Cybersecurity and Data Analytics attract a high number of investors per unicorn, signaling increased stakeholder interest.

###  Global Hubs

- North America leads in total unicorn valuation and count, driven by major markets like the United States.

- Oceania stands out for capital efficiency, generating $22.99 in valuation per $1 of funding.

- San Francisco remains the dominant city hub globally in both valuation and unicorn density.

## Methodology

### Data Source

The dataset was sourced from the Maven Analytics Unicorn Challenge: https://mavenanalytics.io/challenges/maven-unicorn-challenge/b63d748c-ea7f-4e87-a3a8-c7698453ee00 


### Metrics Used

- Valuation: Total and average by year, industry, and location.

- Valuation Multiple:  Calculated as Valuation ÷ Funding. Shows how much valuation is created per $1 of funding — a startup-focused alternative to traditional ROI.

- YoY Growth: Year-over-year valuation growth at the industry level.

## Tools

Power BI for data modeling, DAX measures, custom visuals, and interactivity.



## How to Use This Report

- Navigate through bookmarks: Analyze trends by company, industry, and geography.

- Interact with slicers: Use the Country, City, Industry, Company, and Year slicers to filter data across all sections. These slicers are repeated and synchronized to maintain a smooth and consistent user experience throughout the report.

- Use tooltips: Hover for detailed context on each data point.

- Refer to KPIs: Summary cards show top-level metrics and highlight trends over time.

### Data Dictionary

A dedicated Data Dictionary page has been included to enhance model transparency and documentation. It was built using:

```ruby
INFO.VIEW.TABLES()
```
```ruby
INFO.VIEW.COLUMNS()
```

```ruby
INFO.VIEW.MEASURES()
```

```ruby
INFO.VIEW.RELATIONSHIPS()
```

This view dynamically lists all visible tables, columns, measures, and relationships, including metadata like expressions, descriptions, and data locations.
