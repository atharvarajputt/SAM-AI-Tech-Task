## Task 2: Cuisine Combination Analysis

### Objective
The goal of this task is to:
- Identify the most common combinations of cuisines in the dataset.
- Analyze whether certain cuisine combinations tend to receive higher customer ratings.

---

### Identifying Common Cuisine Combinations

Many restaurants in the dataset offer multiple cuisines. To analyze this:

**Approach:**
- The `Cuisines` column (comma-separated values) was split into individual cuisines.
- Unique cuisine combinations were identified.
- Frequencies of each combination were calculated and ranked.

**Most Common Cuisine Combinations (Observed):**
- North Indian & Chinese
- North Indian & Mughlai
- Chinese & Fast Food
- North Indian & South Indian
- Bakery & Desserts

**Insight:**
North Indian cuisine frequently appears in combination with other cuisines, indicating its high popularity and wide acceptance.

---

### Cuisine Combinations vs Ratings

To determine whether cuisine combinations influence ratings:

**Methodology:**
- Restaurants were grouped based on cuisine combinations.
- The average rating for each combination was calculated.
- Ratings were compared across combinations.

**Key Observations:**
- Specialized or premium combinations such as *Continental & Italian* and *Bakery & Desserts* tend to have higher average ratings.
- Very common combinations like *North Indian & Chinese* usually show slightly lower average ratings.
- High competition and varying quality may contribute to lower ratings in popular cuisine combinations.

---

### Conclusion

- North Indian–based combinations are the most common in the dataset.
- Less common, specialized cuisine combinations generally receive higher customer ratings.
- Popularity of a cuisine combination does not always guarantee higher ratings; consistency and quality play a more significant role.

---

### Key Takeaway
There appears to be a trend where **unique or niche cuisine combinations achieve better average ratings**, while **highly common combinations face stronger competition and rating variability**.
