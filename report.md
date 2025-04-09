# Report

I checked my theory, in which I thought a chi-squared test where each square has the same number in it, would yield a low value of independence. I thought this would be true, however I had forgotten that a high p value means a high independence with no correlation, and not a low value.
I ran a chi-squared test with men and women, and the number of cat/dogs each group had. I put a '5' for each value, and the results of this yielded a p value of 1. Since there is obviously no correlation between gender and choice of pet.

.  |Male  |  Female
---|------|--------
Cat|  5   |    5   
Dog|  5   |    5   

> This table returns a p value of 1.
    
    
.  |Male  |  Female|
---|------|--------|
Cat|  10  |    0   |
Dog|  0   |    10  |
>This tale returns a p value of 5.699e-05

Tried to load data from teaching_hours.csv, but ran into issues.
11:15 AM
Copied Richels code for loading the data from the analysis, however ran into a wall when trying to run a chi-squared test on it. I could not for the life of me think out a way to do it myself, and when trying to copy Richels test, it returned the error: Error in sum(x) : invalid 'type' (character) of argument. I also added tables to previous part of report, to clarify what I was doing.
## Goal

To find out if gender and academic status matters for hours spent teaching.

## Tasks (written by supervisor)

- [x] Install RStudio
- [x] Do a chi-squared test in R
- [x] Prove understanding of chi-squared test
- [ ] Determine if tables in `[Bendfeldt & Söderström, unpublished]` are
  only descriptive or can be used to find a gendered effect.
  If a table shows a potential gendered effect, prove it is a
  significant effect
- [ ] At Uppsala University they know that males and females will never
  put in *exactly* the same amount of hours. Instead, they use a 
  rule-of-thumb of 40%-60% to say when the amounts of hours are
  equal enough. This is a different rule than when using statistics,
  where can get a significant effect of gender on teaching hours
  at 49% hours by males to 51% hours by female, **if and only if**
  the dataset is big enough. Are there examples when there is difference
  beyond the rule-of-thumb range and the statistics? When?
  How big should the data be for the 40%-60% rule-of-thumb to be valid?


## References (written by supervisor)

- `[Bendfeldt & Söderström, unpublished]`
  Fair division of labor? Examining access to prestigious
  teaching –formulating equitable and transparent policies


