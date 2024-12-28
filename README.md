# Are the Bank of Korea's Inflation Forecasts Biased toward the Target?
Seong and Lee (2024) - "Are the Bank of Korea's Inflation Forecasts Biased toward the Target?"

#### How to access to the replication code and data?
You can either download [LeeSeong2024_replication.zip] or clone this repo to your local environment.

## Summary

The Bank of Korea (BoK) regularly publishes the <i>Economic Outlook </i>, offering forecasts for key macroeconomic variables such as GDP growth, inflation, and unemployment rates. 

This study examines whether the BoK’s inflation forecasts exhibit bias, specifically a tendency to align with its inflation target.

![figure_3](/figures/figure_3.png)

Figure above illustrates the forecast and realized values of the CPI inflation rate in Korea since 2012. 

The shaded area represents the range of the Bank of Korea’s inflation target; the dotted line represents the point target. 

The dashed lines depict the projection paths from the respective issues.

When actual inflation is below the target, the inflation forecast tends to be overestimated, and vice versa.

![figure_6](/figures/figure_6.png)

We display the ordered pairs $(y_{h,t}, y_t)$ in Figure above, with the realization on the y-axis and the forecast on the x-axis. Each panel corresponds to a different forecast horizon. 

The black circles represent the paired realization and forecast observations. 

The red line is the $45^\circ$ line passing through the origin, referred to by Mincer and Zarnowitz (1969) as the Line of Perfect Forecast (LPF). 

The blue dashed line indicates the estimated regression line (RL) of the equation $y_t = \alpha + \beta y_{h,t} + v_{h,t}$.

If the regression line lies exactly on the line of perfect forecast, the forecast is unbiased.

We extend the Mincer and Zarnowitz (1969) test to incorporate state-dependency, defining the state of the economy based on whether realized inflation falls below the target at the time of the forecast. 

Our analysis reveals that the BoK’s inflation forecasts are biased under this state-dependent framework. 

![figure_8](/figures/figure_8.png)

Furthermore, we show that applying an AR(1) bias correction strategy enhances forecast accuracy, as demonstrated by a reduction in root mean square error.

The results are illustrated in Figure above. 

The x-axis represents the window size; the y-axis shows the ratio of RMSEs (RRMSE) between the BoK’s forecasts and each bias-correction strategy. 

An RRMSE below 1 indicates that the corresponding strategy outperforms the BoK’s forecast.

The black line with circles represents the RRMSEs for the AR(1) bias-correction strategy.

The results show that the AR(1) strategy improves forecasts across all horizons except for the longest one, $h=3$.