## 📊 Hypothesis Testing

**Hypothesis testing** is a core statistical method used to determine if a result is statistically significant — in other words, whether it's likely to be due to something real or just random chance.

### 🔍 Key Terms

- **Null Hypothesis (H₀)**: There is no effect or difference (e.g., two groups behave the same).
- **Alternative Hypothesis (H₁)**: There is an effect or difference.
- **P-Value**: Probability of observing the data (or more extreme) if H₀ were true.
  - If `p < 0.05` → reject H₀ → the result is statistically significant.
- **T/Z-Statistic**: Measures how far the observed result is from what's expected under H₀.

---

### ✅ Common Tests

| Test                        | Use Case                                           |
|----------------------------|----------------------------------------------------|
| One-Sample t-Test          | Compare sample mean to a known value               |
| Two-Sample t-Test          | Compare means of two independent groups            |
| Paired t-Test              | Compare means of the same group before & after     |
| Z-Test                     | Like t-test, but used for large samples            |
| Proportion Z-Test          | Compare proportions (e.g., conversion rates)       |

---

### 🧠 Example

> Are Prime users spending more than Non-Prime users?

- **H₀**: Both groups spend the same
- **H₁**: Prime users spend more
- Run a **two-sample t-test**
- If `p-value < 0.05` → reject H₀ → conclude a significant difference

---

### 📌 Why It Matters

Hypothesis testing helps you validate if observed patterns are meaningful. It’s foundational in:
- A/B testing
- Product experiments
- Performance analysis
- Data science models
