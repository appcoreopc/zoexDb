# zoexDb

This is a proposal to build a database engine that is capable of querying historical data automatically. 

Problem statement. 

Dimension data update is a problem for data warehouse, for example you are building your database warehouse for equity portfolio and stock ticker changes its name over time and next time you run your report, your portofolio values disappears. 

There are ways to deal with this, replicate the entire snapshop to solve this. Storage is cheap but still it takes sql to resolve this. 
