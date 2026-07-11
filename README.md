# kaggle-projects

Kaggle data analysis projects by Eser Karaçeper.

---

## 📊 Lettuce Growth Analysis
**Dataset:** [Lettuce Growth Days](https://www.kaggle.com/datasets/jurijsruko/lettuce) — 3,169 records | Aug–Sep 2023

**Goals:**
- Find the date with the lowest recorded humidity
- Calculate average pH level across all plants
- Test whether higher TDS levels shorten growth time

**Results:**
- Lowest humidity: 2023-09-01 → 50%
- Average pH: 6.3992 (within ideal range 6.0–7.0)
- TDS vs Growth Days correlation: r = -0.021 (no significant relationship)
- Linear regression R²: 0.006 — environmental variables alone cannot predict growth days

**Notebook:** [lettuce-growth-analysis](notebooks/lettuce-growth-analysis/)
