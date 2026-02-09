Results
Model specification

We estimate a reduced-form Vector Autoregression (VAR) using monthly growth rates (month-over-month, MoM) for:

U.S. food CPI inflation (cpi_food_mom)

Wheat price inflation (wheat_mom)

Corn price inflation (corn_mom)

The VAR includes an intercept and lagged endogenous variables. Lag length selection supported a short-memory structure, and the baseline model was estimated with 2 lags (VAR(2)).

The sample contains 272 monthly observations.

VAR estimation summary

The estimated coefficients suggest:

Strong persistence in food CPI inflation:

L1.cpi_food_mom and L2.cpi_food_mom are positive and statistically significant.

Evidence of short-run pass-through from wheat to food inflation:

L1.wheat_mom is positive and statistically significant in the food inflation equation.

Weak pass-through from corn to food inflation:

Corn lags are not statistically significant in the food inflation equation.

Stability condition

The VAR satisfies the stability condition: all eigenvalues lie inside the unit circle.

This supports valid impulse response analysis and suggests the system is dynamically stable

Impulse Response Functions (IRFs)
Wheat shock → Food CPI inflation

A one-standard-deviation shock to wheat inflation produces:

An immediate positive response in food CPI inflation.

The response reaches its peak at horizon 1 (month 1).

The confidence bands do not include zero at the peak, suggesting the effect is statistically significant in the short run.

The response gradually decays and is close to zero by approximately 12 months.

Interpretation: wheat price shocks exhibit a clear short-run pass-through into U.S. food inflation.

Corn shock → Food CPI inflation

A one-standard-deviation shock to corn inflation produces:

A positive response in food CPI inflation.

The response peaks at horizon 2 (month 2), indicating a slightly slower transmission mechanism.

However, the confidence bands include zero at the peak, implying the effect is not statistically distinguishable from zero at the chosen confidence level.

The response converges toward zero and becomes negligible by 12 months.

Interpretation: corn shocks show a weaker and less robust pass-through effect compared to wheat shocks.

Main conclusion

The VAR results provide consistent evidence that wheat price shocks transmit into U.S. food CPI inflation in the short run, while the pass-through from corn appears weaker and not statistically robust under this specification.

Notes and limitations

The VAR is reduced-form and does not establish causal identification.

Results may be sensitive to lag length, variable transformations, or alternative price indices.

Future extensions could include structural identification (SVAR), additional commodities, or global shock proxies.
