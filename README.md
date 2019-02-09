### Comments
I initially did this as a take home test for a company and I ran low on time so instead of building out 148 models,
plots & predictions (one for each buyer_id) and then cumulative ones (listed below), I just showed a bunch of different
techniques for one that I randomly selected.

It is possible I could have gotten a better AIC score.  I just ran out of computation time but ideally I would have 
liked to grid search from 0-24 for PDQ (you can see I stopped it midway through

The comments precede the code and the relevant Markdown immediately follows it.
Even though I could tell the data was stationary I Intentionally did a lot of tests for stationary / vs not stationary 
since this is a key factor in time series and I wanted you guys to see I understood that and could execute it.
 
### Future ideas:
* Automate building all the other models
* Try other time series algos: ARIMAX, etc
#### Other model ideas / feature engineering
* Plot all time per hour across all buyers and do predictions against that (same for days / weeks)
* Downsampling from days into weeks and weeks into months (for buyers with less data)
* Minutes elapsed for the day.
* Hour of day.
* Business hours or not.
* Weekend or not.
* Holidays
