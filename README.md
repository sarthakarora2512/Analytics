# Analytics

# Juniper Delivery Analysis - NYC Launch Performance (December 2023)

## Overview

This project analyzes the performance of Juniper's delivery service in New York City one month after launch.  The analysis identifies key areas impacting user retention and revenue, primarily focusing on delivery wait times.  This document summarizes the findings and proposed next steps.

## Problem Statement

Weekly order volume and active users have plateaued, and customer retention is declining, primarily due to long delivery wait times. This trend, if not addressed, will lead to a decline in revenue.

## Key Findings

*   **Declining Retention:** ~80% of users churn between weeks 1 & 2; only ~30% place a repeat order. Declining week-over-week acquisition exacerbates the issue.
*   **Impact of Delivery Time:** Delivery times exceeding 45 minutes on the first order are a strong predictor of customer churn.  Faster deliveries correlate with higher reorder rates within 10 days.
*   **Courier Wait Times:** Significant courier idle time at pickup contributes to longer delivery durations.
*   **Revenue Loss:** Failure to retain customers leads to substantial revenue loss (estimated $1.8M annually), as acquiring new customers is more expensive than retaining existing ones.

## Proposed Solutions

**Short-Term:**

*   **Verify Delivery Time Estimates:** Ensure accurate delivery time estimates are displayed to customers when placing orders.  Investigate discrepancies and correct inaccuracies.
*   **Investigate Courier Wait Times:** Conduct on-the-ground research (orders, interviews, restaurant visits) to identify root causes of long courier wait times at pickup.

**Long-Term:**

*   **Wait-Time Surge Redirection:** Experiment with redirecting order traffic from popular restaurants with long wait times to similar nearby restaurants with shorter wait times. *See Experiment Parameters below.*

## Experiment Parameters (Wait-Time Surge Redirection)

*   **Target Audience:** Customers ordering from popular restaurants in the East Village.
*   **Experiment:** When wait times exceed a threshold, alert customers to similar nearby restaurants with lower wait times.
*   **Time Frame:** One month.
*   **Key Metrics:** Order Retention Rate, Weekly Customer Retention Rate, Daily Promotion Click-Rate, Wait Time Ratings.
*   **Key Risks:** Unhappy restaurant partners due to order traffic redirection.

## Problem Solving Approach

The analysis considered these key questions for each stakeholder to perform the assessment:

*   **Customers:** Are we growing and retaining customers?
*   **Couriers:** Are we matching supply and demand?
*   **Merchants:** Are we delivering efficiently?

## Contact

Sarthak Arora
