# EUR/USD Fair Value Model 

This TradingView indicator estimates the fair value of EUR/USD based on macroeconomic indicators.

###  Inputs
- US & EU GDP Growth
- US & EU Inflation Rates
- Purchasing Managers' Index (PMI)
- Economic Sentiment Index (ESI)

###  Methodology
1. Starts from a base PPP estimate.
2. Adjusted with:
   - Inflation differential
   - GDP growth differential
   - PMI differential
   - Sentiment differential

###  Output
- Blue line = Fair value based on the model.
- Green line = Real market EUR/USD rate.
- Alert triggered if price deviates >10% from fair value.

### 🛠 Code
Written in Pine Script v6 – built for TradingView.

---

> You can fork this model or adapt it to other currency pairs or macro frameworks.
