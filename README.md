# Maximizing Revenue for Taxi Cab Drivers 💰🚕

This project explores how payment methods impact fare amounts in NYC taxi services, aiming to uncover insights that can help drivers maximize their earnings using data-driven decision-making.

## 📌 Problem Statement

In a competitive taxi industry, maximizing driver revenue is crucial. This project investigates whether the **payment type (cash vs card)** significantly affects the **total fare amount** and how this information can guide strategies to increase revenue for drivers.

## 🔍 Research Questions

- Is there a relationship between total fare amount and payment type?
- Can customers be nudged towards high-revenue payment methods without hurting their experience?

## 📊 Dataset Overview

The analysis is based on the **NYC Taxi Trip Records** dataset. The key columns used in this study:

- `passenger_count`
- `payment_type` (Card or Cash)
- `fare_amount`
- `trip_distance` (in miles)
- `trip_duration` (in minutes)

## ⚙️ Methodology

- **Descriptive Statistics**: To understand fare distributions and payment behaviors.
- **Hypothesis Testing (T-test)**: To determine if payment type significantly affects average fare amount.

## 📈 Key Insights

- **Card payments dominate** (64.3%) and are associated with higher average fare amounts.
- **Cash payments** make up 35.7%, typically for shorter rides.
- Single-passenger rides are most common across both payment types.
- A **statistically significant difference** was found in average fare between card and cash payments (p-value < 0.05).

## 🧪 Hypothesis Test

- **Null Hypothesis (H₀)**: No difference in average fare between card and cash payments.
- **Alternative Hypothesis (H₁)**: A difference exists.
- **Result**: Rejected H₀ with a t-statistic of 165.5 and p-value < 0.05.

## ✅ Recommendations

- Encourage card payments to maximize fare revenue.
- Offer small incentives or rewards for customers using cards.
- Improve in-car card payment systems to ensure seamless and secure transactions.

## 📂 Folder Structure (if applicable)
