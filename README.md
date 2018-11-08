<img src="Icon.png" align="left" />

# cablecity-db-optimization
Oracle PL/SQL Query optimization for the [cablecity database](https://github.com/kyleruss/cablecity-db). The motivation for this project was to apply  
tuning techniques and parallelism on variable structures and investigate its affect on query performance.  

A baseline query consisting of an equi-join and numerical ID search is performed on various data structures including unstrcuctured, indexed, clustered, hash clustered. 
Further optimizations are then made using tuning techniques such as hinting and table order then finally we optimize the query again using parallelism  
For a full report of the optimization findings see [here](https://github.com/kyleruss/cablecity-db-optimization/blob/master/Report.docx). Additionally the trace results are available [here](https://github.com/kyleruss/cablecity-db-optimization/blob/master/TraceTables.xlsx)

## Features
- Query optimization at the structure level including unstructured, indexed, clustered and hash clustered structures
- Tuning techniques applied using hinting and table order
- Further query optimzation with parallel execution

## License
cablecity-db-optimization is available under the MIT License  
See [LICENSE](LICENSE) for more details
