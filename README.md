# retention-intelligence
Predicting, explaining, and measuring churn.

Churn is a measure that defines the proportion of individuals or items moving out of a specific group over a specific period of time. In other terms, churn measures the percentage of loss of individuals in a population over a defined time period. It is widely used in business in relation to subcriptions or memberships to certain programs, applications, softwares, and more. Churn can be used anywhere from measuring the loss of users on a dating app to the loss of clients in an investment firm. It is defined by:

Churn = $$\frac{L}{T} * 100% = \frac{Individuals Lost}{Total Individuals in Group} * 100$$

While churn is an extremely useful statistic, itt is important to not only treat churn as a measure but also as a _possibility_. Let's say that I am a CEO of a popular subscription service and I'm noticing my subscriber count is decreasing drastically. In this case, I may want to know how long it will take until my churn is at 50%. Once churn reaches 50%, I stop making a profit. Therefore, we can treat churn as a time-to-event problem. Basically, how long do I have to remedy this massive issue that my company is facing? The beauty of churn is that we can use it as a way to predict this but also to gauge the subcribers response to a certain treatment to such an issue.

I plan to build a high level SaaS that not only computes churn but also allows users to predict when, how, and if a certain churn rate will occur. Furthermore, this application will predict future churn under similar circumstances and try to understand churn rates using AI. All of these tools will be extremely useful for any business that strives to succeed.

# Retention Intelligence

## What is churn?
Customer churn occurs when a user permanently stops using a product or service.
In subscription businesses, churn directly determines revenue and growth.

## Why churn is a time-to-event problem
Churn is not just whether a customer leaves, but **when** they leave.
Many customers have not churned yet, leading to censoring.
Survival analysis provides a principled way to model this.

## Project goal
Build a retention intelligence system that:
- estimates churn risk with uncertainty
- explains drivers of churn
- recommends intervention actions
- quantifies expected revenue impact

