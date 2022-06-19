# EazyDates



## What is our motivation to build this project?

Owing to the inherent variability of the menstrual experience, it can be difficult to predict the time to each user’s next cycle start. Various survey results have shown that menstrual experiences vary both within and between individuals, encompassing not only period and cycle length (the number of days between subsequent periods),but also qualitative symptoms like period flow, physical pain, and quality-of-life characteristics. Combined with the aforementioned possibility of inconsistent adherence(eg, some users may track their information consistently, while others may skip tracking, whether intentionally or by accident), the difficulty of modeling menstruation holds especially true for such self-tracking data, as well as we must take into account multiple sources of uncertainty. As such, there exists a need for accurate predictive models that can address the specific nature of data from mobile apps.

## What problem does it solve?

Our goal is to provide users with more accurate predictions of next cycle start date (that is, next period date) by characterizing the underlying mechanisms (both physiological and behavioral) implicit in menstrual data as collected via self-tracking apps. Specifically, we aim at disentangling true cycle lengths from self-tracking artifacts that result from inconsistent adherence, allowing for better understanding of collected health data and greater predictive power. We also aim to provide predictions that evolve over time. To that end, we take a probabilistic machine learning approach. We aim at a model with 3 key features. First, it shall account explicitly for the possibility that users may adhere differently to the app by factoring in the possibility that the observed cycle lengths are not the true, experienced cycle lengths. Second, it should dynamically update predictions each day as the cycle proceeds, providing insights into how predictions evolve over time. Third, it must prioritize each individual’s unique menstrual experience by modeling user-specific cycle length history and providing individual user predictions, while also harnessing the power of population-wide knowledge.

## 

## Contributors
Samridhi Garg: https://github.com/Samridhi412

Akanksha Takkar: https://github.com/akankshatakkar

Divya Gandhi: https://github.com/divya16-bit
