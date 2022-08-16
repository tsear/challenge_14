# challenge_14
repo for challenge 14


This challenge asked me to build an algorthimic trading bot, train a new Regression model, & tune its parameters from what was used initially. This challenge prompted me to think from the perspective of a quant trader at a high frequency trading firm in order to tailor the application to what is sought by fund managers. 

The first step in building this new model was understanding the baseline preformance of its predecessor. To do this first I must read in all corresponding data, generate signals, split the data, generate the SVC classifier model, & plot the strategy returns against actual. 

Next, I tuned the training data parameters to best besst training option of 6 months, instead of 3. This resulted in sligthly better returns than the prior dataset. After tinkering with SMA values, I decided that the original returned, on average, better results. 

Then, I built a new Regression model & backtested it which output worse results, trading mostly in-line with actual returns &, for an extended period of time, worse. 
