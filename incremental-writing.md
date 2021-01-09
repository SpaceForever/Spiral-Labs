# Incremental Writing

incremental writing is intervals priority queue based presentation of stuff to write
pretty great

### plugin proposal for IW in Foam

you need priorities and intervals 
could you present sorted links?

The core of incremental writing is the priority queue in SuperMemo:
[pic]

It's just a queue of all the writing you have that you want to write about sorted based on two criteria: 

-intervals

-priorities

I'll go into priorities first. If you have 5 things you want to write, what order should you write them in? Random order is arbitrary, in order of creation has a recency bias... in SuperMemo we fix this by assigning priorities. Priorities are values between 0 and 100, with 0 being the highest. 
The queue is then sorted by those priorities:
[pic]
But as you can see, not purely by priority. There's a bit of randomization to avoid tunnel vision of never getting past high priority each day. 

That's just the first