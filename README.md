# AB-test-case-study
1. data used 

The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. 
 
2. optimization strategy 

My task is to use the training data to understand what patterns in V1-V7 indicate that a promotion should be provided to a user. Specifically, my goal is to maximize the following metrics:

* Incremental Response Rate (IRR)

* Net Incremental Revenue (NIR)
