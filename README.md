# Options Algorithmic Trading Strategy

This GitHub repository contains the code and documentation for a project focused on developing and evaluating options trading strategies. The objective of this project is to compare various strategies across different strike prices, implied volatility levels, and times to maturity for options. The strategies involve selecting a subset of options based on specific criteria, employing portfolio optimization techniques, and assessing their performance against standard options trading strategies.

## Project Idea

### Overview

The project revolves around exploring high-frequency options trading strategies and utilizing portfolio optimization techniques to potentially generate positive returns. The primary idea is to select a set of options from a larger investment universe based on specific criteria, such as implied volatility, and then apply various trading strategies to assess their effectiveness.

### Key Objectives

1. Compare options trading strategies across different strike prices, implied volatility levels, and times to maturity.
2. Select a predetermined number of options with the highest implied volatility (or other relevant metrics).
3. Implement trading strategies, including longing one group of options and shorting the other, as well as more advanced portfolio optimization techniques.
4. Evaluate the performance of the developed strategies against standard options trading approaches, such as longing or shorting calls or puts.

## Methodology/Timeline

### Data

- Data for this project will be obtained from Refinitiv and the Bloomberg Terminal, with assistance from Edward Loeser in the Hanlon Lab. The dataset will include listed SPY options and their prices, both calls and puts, for different strike prices and expiry dates in five-minute intervals over a one-month time period.
- Key metrics, including option greeks, implied volatility (if not already provided), and intrinsic and extrinsic values, will be calculated from the obtained data.
- Additional data for testing the model's performance during periods of extreme volatility, such as the 2010 Flash Crash, will be collected separately.

### Timeline

1. **Data Collection**: Gather and preprocess the necessary data from Refinitiv, the Bloomberg Terminal, and other sources.
2. **Model Development**: Implement and optimize trading strategies, including portfolio optimization techniques.
3. **Testing and Evaluation**: Evaluate the performance of the strategies using historical data and metrics.
4. **Benchmark Comparison**: Compare the results against benchmark strategies and traditional options trading approaches.
Documentation and Reporting: Create comprehensive documentation and reports outlining the project's methodology, findings, and conclusions.

## Expected Outcome

We anticipate the following outcomes from this project:

- Our trading strategies will likely outperform the benchmark (simply longing the stock over one month) due to the use of advanced techniques.
- The strategies may also outperform standard options trading strategies, such as longing or shorting calls, puts, or various combinations like spreads, straddles, and strangles.

## Useful Links

For additional information on algorithmic options trading strategies, you can refer to this [Medium article](https://medium.com/@foolproofoptions/unleash-the-power-of-algorithms-algo-strategies-for-options-trading-38e352ddd607).

For any inquiries or collaboration opportunities, please feel free to reach out to the project contributors.

Thank you for your interest in our Options Trading Strategy project! We look forward to sharing our findings and insights with the GitHub community.