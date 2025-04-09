# Report
10:15 AM
I checked my theory, in which I thought a chi-squared test where each square has the same number in it, would yield a low value of independence. I thought this would be true, however I had forgotten that a high p value means a high independence with no correlation, and not a low value.
I ran a chi-squared test with men and women, and the number of cat/dogs each group had. I put a '5' for each value, and the results of this yielded a p value of 1. Since there is obviously no correlation between gender and choice of pet.
Tried to load data from teaching_hours.csv, but ran into issues.
11:15 AM

## Goal (written by supervisor)

To find out if gender and academic status matters for hours spent teaching.

## Tasks (written by supervisor)

- [x] Install RStudio
- [x] Do a chi-squared test in R
- [ ] Prove understanding of chi-squared test
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


