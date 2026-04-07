# Lab 8 — Cost Management

**Services used:** Cost Explorer, AWS Budgets, Pricing Calculator, Trusted Advisor

## Objective

Got hands-on with AWS's cost management tools to understand how to track, forecast, budget, and optimize cloud spending — a core competency for any Cloud Practitioner.

## What I did

1. **Opened AWS Cost Explorer** and explored my current spending (mostly Free Tier usage from previous labs), including cost breakdowns by service and by day.
2. **Created an AWS Budget** with a **$5 monthly threshold** and configured an email alert at 80% of the forecasted amount, so I'd be warned before going over.
3. **Opened the AWS Pricing Calculator** and estimated the monthly cost of running a single `t3.micro` EC2 instance 24/7 in eu-west-3, including EBS storage and outbound data transfer.
4. **Opened Trusted Advisor** and reviewed the checks available on the Basic support plan — primarily **service limits** and **security** checks (like MFA on the root account and open security group ports).

## Screenshots

## Key takeaways

- **Cost Explorer is free and retains 12 months of history** — it's the go-to tool for analyzing spending trends and forecasting.
- **Budgets catch problems proactively**, before the bill arrives — an essential safety net for personal accounts and small teams.
- **The Pricing Calculator is the right tool for architecting a workload on paper** before launching anything. It handles complex scenarios like Reserved Instances, Savings Plans, and regional pricing differences.
- **Trusted Advisor on the Basic plan is limited** to a handful of security and service-limit checks; the full set (including cost optimization and performance checks) requires a Business or Enterprise support plan.
- Cost awareness is part of **the Shared Responsibility Model** — AWS provides the tools, but controlling spend is on the customer.
