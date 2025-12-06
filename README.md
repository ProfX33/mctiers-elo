# MCTIERS ELO
### **About**
- This is a small project, takes tierlist matches from #results and #high-results and runs them through an Elo system
- For any questions or suggestions contact `profx33` on discord
### **Elo**
- Elo is one of the most basic ranking systems. Because of that, it is flawed in a few ways
  - Tierlist fights dont happen frequently enough to produce accurate rating results. Take any generated Elo leaderboard with a grain of salt. The actual rating of a player could just as well be 60 above or below calcuated Elo.
  - Since more players have joined the tierlist in later years, the ratings also increase by a slight amount. This makes it difficult to compare peak ratings of players that are more than ~1 year apart.
### **Inconsistent Data**
- Wrongly logged results from the tierlist discord will affect the Elo ratings slightly. Most of them can only be fixed manually. The most common types are:
  - Inconsistent message formatting
    - leads to that result not being included in the Elo calculation  
  - Players changing their username
    - results in both their old and new username appearing as separate players in the Elo ratings
- I have manually gone through and fixed many of these, but there likely still are a lot of the remaining
