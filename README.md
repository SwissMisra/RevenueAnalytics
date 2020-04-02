# RevenueAnalytics
This project uses real company data to construct a data model and identify KPIs for theater performances. As this is data for actual performances and productions, identifying information and proprietary data has been removed.

My goal was to determine the key variables that determine the earned revenue of a "production", i.e. a theater's run of performances of a given work, or the individual performances. In particular, I wanted to examine whether an increase in the average price of a seat in the theater, or "ASP", resulted in increased revenue for a given performance or production.

In this analysis, we find that ASP cannot reliably predict revenue performance, and that existing data may only indicate as much because the effects of increased prices are comingled with that of inflation. After adjusting for inflation, we see that sales volume, or total tickets sold, is the most significant variable to impact revenue at the performance level, followed by the number of matinee performances and the general popularity of the title.

When we aggregate sales performance at the production level, we find that title is a much more significant predictor of tickets sold and, in turn, production revenue. Therefore, we can create 2 separate models: 
<ul> a linear regression to predict revenue at the performance level;</ul>
<ul> and a logarithmic model to predict tickets sold and, in turn, production revenue.</ul>
