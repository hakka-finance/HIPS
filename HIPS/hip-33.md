# HIP-33

| hip | title | author | created | duration | Snapshot Block Number |
|----------|:----------:|:----------:|:----------:|:----------:|:----------:|
| 33 | Implementation of the "lockup" or "vesting" period | 0x0E29e5AbbB5FD88e28b2d355774e73BD47dE3bcd | 2020-11-17 13:00 | 1 | 11275428 |


### Summary
Implement the "lockup" or "vesting" period for liquidity mining rewards

### Details

According to the previous proposal provided by the Hakka community, team Hakka will implement the lockup/vesting period for liquidity mining rewards to align the long-term interests of the liquidity provider and the community.

Here are two options for the community to discuss, comment, modify, and vote.

**Option 1: Lockup**
For all future rewards, in addition to voting to determine the number, a lock-up period will be added. For example, the length of one week, one month, three months, one year, etc. After LP claims the rewards, the rewards will go to a lock-up vault and can only be claimed when the time is up.

**Option 2: Vesting**
All the future rewards will be released gradually over time according to a given schedule. For example, 15% of the balance every week; or 40% every month.

The advantage of option 1 is that different types of reward pools can have different lock-up periods, and can also be determined by community governance in the future. In the second scenario, the reward pool needs to share the same schedule, but the advantages are that the reward distribution is relatively smooth, the impact on the circulation is small, and keeping users' attention on Hakka.

### Options
1. Lockup
2. Vesting
