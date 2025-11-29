🚖 Taxi Trip Data Analysis — 2020

This project is about understanding fare amount, payment type, trip distance, and how drivers can improve earnings using data.

📝 Problem Statement

Taxi business me revenue strong rakhna is important.
Goal: check if payment method affects fare amount and use data to give better insights to drivers.

🎯 Objectives

Explore trip distance, fare amount, and trip duration

Check which payment type people use more

Remove wrong values (negative fare, impossible distance)

Give useful insights for better taxi operations

❓ Research Questions

Is there any link between fare amount and payment type?

How can drivers increase profit without hurting customer experience?

📦 Dataset

Source: Taxi Trip Data 2020 (data.gov)
Columns used:

Passenger count

Payment type (Cash / Card)

Fare amount

Trip duration

Trip distance

🔍 Key Insights
1. Travel Insights

Card users have a higher average distance and higher fare than cash users.

When distance and fare go up, people mostly use card.

2. Payment Type Split

Cash: 37%

Card: 63%
Card is clearly more common.

3. Passenger Count

Even single passengers use card more than cash.

🧪 Hypothesis Test (t-test)

H0: Payment method does not affect fare

H1: Payment method affects fare

Result:

p-value < significance

t-score ≈ 14.5
👉 We reject the null — payment method impacts fare.

🤖 Regression Models

Used to predict fare based on distance:

Linear Regression

Random Forest Regression

Gradient Boosting Regression

Gradient Boosting performed best.

✅ Conclusion

Payment type and fare amount have a clear relation.
Card payments dominate long and high-fare trips.
Insights from this study can help drivers improve earnings and understand customer behavior.

🙏 Thank You
