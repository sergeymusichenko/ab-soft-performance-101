
# Testing Strategy
## Document Profile

**ID** # 1

**Revision** - 1

**Date** 3/13/19

**Recipients** - For Business owners 

**System Name** - Basic e-commerce portal

**Author** - Sergii Muzychenko-Kozlovskyi

**Contacts** - sergey.musichenko@ab-soft.net

## System Description
Small e-commerce project devided into 3 logical parts:
 - auth service - provides token auth mechanizm;
 - product service - provides info of particular product by its ID;
 - cart service - provides logic to add to user cart some product, view items in cart and checkout;

#### Project acceptance criteria
1. System can serve # of users for some period of time
2. System can serve # of max user in peak time simultanuesly.
3. System has ____% of up time.
#### Risks
- Risk of network failure.
- Risk of hardware failure.
- Risk of performance degradation due to functional issues.

## Performance Test Objectives
#### Audience
- stakeholders
- developers
- QA engeeners

Define and classify expectations according to audience ?? What does it mean? Which expectations ? My from audience or audience expectetions from test reports ?

#### Success criteria of the project
Performance of project met defined criteria.

## Expected Outputs
High-level test reprort cantaining graphics and table of test results as well as advises to invrease performance and meet KPI in time.

## KPI
- **Response time** - max 0.8 sec (including max slowdown time of 0.5 sec)
- **Throughput** - must be defined by business owner.
- **Max throughput** - Throughput * **multiplier**. Multiplier must be defined according to market research of peak time purchases/page views and user behavior.
- 
#### Reliability measurements
- Downtime -TBD
- Availability - TBD
- Error rate - TBD
