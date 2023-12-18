# note

https://www.youtube.com/watch?v=pOYAXv15r3A
Forecasting at Scale: How and Why We Developed Prophet for Forecasting at Facebook
Delivered by the Prophet author Sean Taylor

# Forecasting at Scale: How and Why We Developed Prophet for Forecasting at Facebook

## Introduction

Facebook's journey in developing the open-source package Prophet stands as a testament to the evolving landscape of data forecasting. The drive behind Prophet was not merely to handle the vast amounts of data at Facebook but to address the more intricate challenge of scaling forecasting across various people and problems. The development of Prophet, now a widely accepted tool, marks a significant milestone in democratizing forecasting solutions.

## The Challenge: Demand for Forecasting Solutions

Forecasting at Facebook is multifaceted, involving capacity planning for infrastructure, goal setting, anomaly detection, and other varied applications. The diversity and volume of forecasting demands highlighted a critical gap - the lack of expert forecasters and robust, user-friendly tools to address these needs. Traditional forecasting methods, although powerful, often proved too complex and inaccessible for most users at Facebook.

## The Prophet Solution: Simplifying Forecasting

Prophet was designed as a simple, decomposable, additive model, specifically targeting time series data common in business contexts. It is a generalized additive model, where components can be linear or non-linear, encompassing:

1. **Piecewise Linear or Logistic Trend**: Capturing growth or decline trends.
2. **Seasonality**: Addressing regular cyclic changes.
3. **Holiday Effects**: Accounting for irregular, yet impactful events.
4. **Noise**: Recognizing and handling data irregularities and outliers.

### Key Features of Prophet

- **L1 Regularization**: For handling trend changes.
- **Fourier Series**: To model seasonality.
- **Dummy Variables**: For holiday effects.
- **Robust to Missing Data**: Capable of handling gaps in data.

### Advantages

1. **Explainability**: Each component of the model is explainable, enhancing user understanding.
2. **Intuitiveness**: Provides an intuitive framework for non-experts.
3. **Flexibility**: Offers various parameters for customization based on domain knowledge.
4. **Scalability**: Addresses a wide range of forecasting problems effectively.

### User Empowerment

Prophet emphasizes empowering users by providing 'knobs and levers' - parameters to adjust and tailor forecasts based on specific needs and domain knowledge.

## The Development Journey

The development of Prophet followed a structured path:

1. **Research and Hypothesis**: Understanding the feasibility and scope of the problem.
2. **Prototyping**: Developing initial models, iteratively improving them based on varied use cases.
3. **Quality Coding and Polishing**: Transitioning the tool from a prototype to a robust, user-friendly application.
4. **Documentation and Case Studies**: Providing comprehensive guides and examples for users.

## Impact and Takeaways

The success of Prophet at Facebook and in the wider community underscores several key insights:

- **Simplicity as a Virtue**: A straightforward, understandable model can be more impactful than complex systems.
- **User-Centric Design**: Tools that are intuitive and adaptable to user knowledge tend to have greater acceptance and utility.
- **Democratization of Tools**: Providing tools that make sophisticated methods accessible to a wider audience can significantly impact an organization's analytical capabilities.

## Conclusion

Prophet stands as a milestone in forecasting, particularly in how it addresses the scale of people and problems. Its development showcases the importance of user-centric design in data science tools, emphasizing simplicity, flexibility, and democratization. Prophet is not just a tool for Facebook but a contribution to the broader data science community, encouraging more inclusive and accessible forecasting solutions.
