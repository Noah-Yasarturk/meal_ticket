Meal planning / analysis app.

## Stack
- UI: React
- Backend: Django 
- DB: Postgres

## MVP 
This use case will focus on simply storing meals and selecting them to form a grocery list.

### Future features
- Post-trip analysis: How much did things cost?
    - Initially form-driven, then automation w/Textract on reciept upload
- Generate meal plan & grocery list
- Meal analysis - how much do meals cost?
- Store analysis - do meals cost more elsewhere?
- Eating out costs - how does eating out compare to eating in?
- Nutrition/meal analysis 

## Current Architecture
Local.
All servers will be containerized & served from my local desktop machine & accessed on my home network for cost & simlicity.

### Future architecture
AWS.
Django API broken up into Lambdas behind API Gateway authenticated with Cognito, UI served from an S3 bucket strapped to Route53, DB in RDS.

