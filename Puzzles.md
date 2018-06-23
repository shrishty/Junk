### Junk Puzzle Questions

### 100 Doors

There are `100` doors initally all doors are closed.
Starting from `1`, `i` will range from `1 to 100`. We flip the doors which are multiples `i`.
Count the no of doors open at 100th turn.

**Ans**: number of squares upto 100, as their multiples are odd compared to other numbers
Example: `9 = 1,3,9` where as `10` has `1, 2, 5, 10` multiples

### Jeweller and the King
Once a traveller told the king that he may visit him any day in the next month and whichever day he visits between `1` and `31` inclusive he will give him gold equal to the day he visits.
`eg: He will give 11g if he visits on 11th day of that following month.`

So to carry the gold he went to the jeweller to buy the gold bags but not knowing which day he will arrive the kingdom and meet the king. So the jeweller suggests he will give bags of gold in such a way that we will have to carry minimum bags and any combination of those bags will give him the exact number in `[1,31]`. The bags will be of fixed size.
`eg: To make 31: 23 size bag + 8 size bag.`

Find the minimum number of bags the jeweller gave him.

**Ans**: `5` bags each of `1,2,4,8,16`
