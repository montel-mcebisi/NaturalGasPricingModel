# NaturalGasPricingModel

Pricing model for the Natural gas commodity.

Objective: 
- Inject gas when prices are low
- Withdraw gas when prices are high
- Follow limits for volume, injection/withdraw rate
- Track storage cost
- Retrn total profits

Strategy:
- Inject if today's price is below the median
- Withdraw if today's price is above the median
- Never exceed max_volume or rate constraints
