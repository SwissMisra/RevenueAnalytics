# RevenueAnalytics
This project uses real company data to construct a data model and identify KPIs for theater performances. As this is data for actual performances and productions, identifying information and proprietary data has been removed.

My goal was to determine the key variables that determine the earned revenue of a "production", i.e. a theater's run of performances of a given work, or the individual performances. In particular, I wanted to examine whether an increase in the average price of a seat in the theater, or "ASP", resulted in increased revenue for a given performance or production. We'll call that the <b>null hypothesis</b>, and our goal is to see whether ASP can predict revenue with at least 95% certainty.

The <b>alternative hypothesis</b>, which we will confirm, is that ASP cannot reliably predict revenue performance. Furthermore, the existing data only indicates as much because the effects of increased prices are comingled with that of inflation. Our subsequent hypothesis will see if there is another variable or combination of variables that that can predict revenue at the performance level with 95% certainty. This analysis determines that total sales volume, regardless of pricing, is the key predictor, followed by the number of matinee performances and the general popularity of the title, for revenue at the performance level. 

When we aggregate sales performance at the production level, we find that title is a much more significant predictor of tickets sold and, in turn, production revenue. Therefore, we can create 2 separate models: 
<ul> 
  <li>a linear regression to predict revenue at the performance level;</li>
  <li>and a logarithmic model to predict tickets sold and, in turn, production revenue.</li>
</ul>

Let's dive in!
