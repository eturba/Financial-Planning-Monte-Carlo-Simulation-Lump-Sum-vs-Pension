# Financial-Planning-Monte-Carlo-Simulation-Lump-Sum-vs-Pension

## 🧠 Situation Context

Your client is a single male age 58. He is a participant in his workplace defined benefit pension plan. Upon retirement, he receives an offer for a one-time lump sum buyout of his pension of $525,000. He comes to you for help. He wants to know if taking the lump-sum distribution is worth giving up the consistant pension income stream. You decide to use R to help run a Monte Carlo simulation to help determine what decision would be best for your client. 

These factors are assumed in the simulaton:

- **Retirement Age = 62**
- **Maximum Living Age = 100**
- **Lump Sum Amount = $525,000**
- **Annual Pension Payment = $42,000**
- **Real Annual Withdrawal from Portfolio = $42,000**
- **Expected Inflation-Adjusted Portfolio Return = 6%**
- **Expected Standard Deviation of Returns = 12%**
- **Discount Rate (Used to Convert Future Dollars into Today's Dollars) = 3%**
- **Number of Monte Carlo Runs = 10,000**

## 📊 Results

### Probability Lump Sum Wins: 51.17%

### Lump Sum Results
- **AVG PV - $704,926.00**
- **Median PV - $627,565.00**
- **STD DEV - $307,958.00**
- The **average is higher than the median**. That tells us the distribution is **right-skewed** where a smaller number of strong market scenarios are pulling the mean up but most outcomes are closer to the median.
-  **High standard deviation** reflects a high market volatility.

### Pension Results
- **AVG PV - $649,716**
- **Median PV - $711,293**
- **STD DEV - $233,029**
- The **median is higher than the average**. That tells us some early death scenarios **drag down the average** but most outcomes are closer to the median.
- Standard deviation is large but is lower than the standard deviation of the lump sum method.

There is not a dominant strategy either way.

The decision depends heavily on the clients:

-   **Risk tolerance**

-   **Health**

-   **Desire for guaranteed income**

-   **Behavioral discipline**

-   **Legacy goals**

### Pension is better for the client if:

-   They expect to live a long time
-   They value guaranteed income
-   They prefer certainty
-   They don’t need liquidity
-   They want longevity insurance

### Lump Sum is better for the client if:

-   They are in poor health
-   They want estate value
-   They want flexibility
-   They are comfortable with volatility
