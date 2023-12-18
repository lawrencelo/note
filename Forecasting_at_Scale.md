# note

https://peerj.com/preprints/3190.pdf
# Forecasting at Scale

## Abstract

The paper presents a unique approach to forecasting "at scale" that addresses the challenges of producing reliable, high-quality forecasts in scenarios where a variety of time series are involved, and expertise in time series modeling is scarce. The proposed solution is a modular regression model with interpretable parameters, allowing analysts with domain knowledge to intuitively adjust the model. This approach is significant for its practicality in enabling efficient and effective use of analyst expertise in large-scale forecasting.

## Introduction to Forecasting Challenges

Forecasting is vital in many organizational activities, including capacity planning, goal setting, and anomaly detection. The paper identifies two primary challenges in business forecasting: the difficulty of tuning automatic forecasting techniques and the rarity of analysts with substantial experience in time series forecasting. The research aims to provide guidance for producing forecasts on a large scale, catering to a wide audience and diverse forecasting problems.

## The Prophet Forecasting Model

The paper describes a decomposable time series model consisting of three components: trend, seasonality, and holidays. This model aligns with the Generalized Additive Model (GAM) framework, known for its flexibility and quick fitting. The model is particularly advantageous due to its ability to accommodate multiple seasonality periods and provide easily interpretable parameters. Unlike ARIMA models, it does not require regularly spaced measurements and can handle missing values more efficiently.

## Analyst-in-the-Loop Modeling

A key aspect of the proposed model is the incorporation of the analyst-in-the-loop approach. Analysts, often with extensive domain knowledge but limited statistical expertise, can modify the model by specifying capacities, change points, holidays, and seasonality. This approach enables analysts to apply their insights effectively, improving model fit and making informed interventions without needing deep statistical knowledge. This method bridges the gap between statistical forecasts, which are model-based, and judgmental forecasts, which rely on human expertise.

## Automating Evaluation of Forecasts

The paper also outlines a method for automating the evaluation of forecast performance. This involves comparing various forecasting methods and identifying cases where manual intervention is necessary. The approach includes using baseline forecasts and modeling forecast accuracy over different horizons. This automated evaluation is crucial in understanding the reliability and trustworthiness of forecasting procedures in a business context.

## Conclusion

This paper makes a significant contribution to the field of data science and business forecasting. By proposing a flexible, modular regression model and integrating an analyst-in-the-loop approach, it addresses the pressing need for scalable, reliable forecasting methods in diverse business environments. The model's ease of use and interpretability make it a valuable tool for a wide range of users, bridging the gap between complex statistical methods and practical business applications.
