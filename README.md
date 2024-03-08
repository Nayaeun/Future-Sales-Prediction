# Future-Sales-Prediction

## Introduction

The vast landscape of time-series data analysis offers a multitude of insights into trends, patterns, and predictive modeling. In this study, our primary objective was to unravel the intricate sales dynamics embedded within a comprehensive dataset spanning from January 1, 2013, to December 31, 2017. The rich dataset encapsulates the sales records of 50 distinct items across 10 different stores, providing a fertile ground for exploring the temporal intricacies of sales behavior.

## Objectives

The core objective of this study was to employ advanced time-series analysis and modeling techniques to uncover the underlying patterns and dependencies in the sales data. Specific goals included the transformation of the original dataset into a time-series format, exploration of autocorrelations, testing for stationarity, and the development of predictive models. The overarching aim was to derive actionable insights and construct a robust forecasting model capable of offering valuable predictions for future sales trends.

## Methodology

The methodology commenced with the meticulous reshaping of the dataset, focusing on temporal structures and seasonality. Through a step-by-step process involving date formatting, data grouping, and column addition, the dataset evolved into a refined time-series representation. Subsequent autocorrelation analyses, stationarity tests, and differencing techniques were applied to enhance the dataset's suitability for time-series forecasting models.

The arsenal of models included the Holt-Winters method, basic forecasting techniques, and a multiple linear regression model. The evaluation of each model involved performance metrics such as Mean Squared Error (MSE) and visual checks on predicted versus actual values. The analysis then delved into the realm of ARIMA and SARIMA models, with a detailed exploration of model order selection, validation through residual analysis, and a comparison between ARIMA and SARIMA.

## Results

The culminating point of the study rested on the selection of the SARIMA model as the final and most proficient forecasting tool. The SARIMA model exhibited the lowest MSE among all contenders, emphasizing its superior predictive accuracy. A 100-step ahead prediction visually showcased the model's robust performance, aligning closely with the test data in the initial phase. Nevertheless, as the forecast extended into the future, inherent uncertainties led to a flattening of predictions, a common challenge in long-term forecasting with time-series data.

## Conclusion

In conclusion, our journey through extensive analysis and modeling unveiled the SARIMA model as the optimal choice for forecasting sales trends in the given dataset. While celebrating the model's strengths, it is crucial to acknowledge its limitations, notably in long-term forecasting where uncertainty amplifies. Moreover, the study hinted at the potential of unexplored non-linear relationships in the data, paving the way for future investigations.
