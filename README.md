# EDA-on-Customer-Churn
Analyzed telecom customer data to identify churn drivers like short tenure and month-to-month contracts. Insights reveal opportunities in retention, service bundling, and payment improvements. Highlights value of predictive analytics for proactive churn management and boosting customer lifetime value.

## Objective

To thoroughly analyze telecom customer data to identify key factors influencing churn, extract actionable insights, and recommend strategic initiatives that enhance customer retention and optimize revenue growth.

## Dataset Overview

- **Total Customers:** 7,043
    
- **Key Data Attributes:**
    
    - _Demographic Info:_ Gender, Senior Citizen status, Partner and Dependents.
        
    - _Service Usage:_ Phone Service, Multiple Lines, Internet Service types (DSL, Fiber optic, None), and add-on features like Online Security, Device Protection, Tech Support, Streaming TV/Movies.
        
    - _Contract Details:_ Contract type (Month-to-month, One year, Two year), Paperless Billing.
        
    - _Billing Info:_ Monthly Charges, Total Charges, Payment Method.
        
    - _Churn Indicator:_ Binary variable indicating if a customer has churned.
        

## Key Insights

## 1. **Demographic Distribution**

- Gender split is balanced between male and female customers, suggesting gender-neutral churn strategies.
    
- Senior citizens constitute approximately 16% of customers and may have distinct preferences or vulnerabilities influencing churn.
    
- Significant portions of customers have partners and/or dependents, which may impact preferences for bundling and retention tactics.
    

## 2. **Customer Tenure Profile**

- Average tenure is approximately 32 months, with customers ranging from very new (0 months) to long-term users (up to 72 months).
    
- A large portion (~75%) of customers have tenure less than 55 months, indicating a considerable number of relatively new or moderately tenured customers who may be at higher churn risk.
    

## 3. **Service Subscription Patterns**

- Nearly all customers have phone service; however, subscription to multiple lines varies widely, presenting opportunities for upselling.
    
- Internet Service distribution: DSL and Fiber optic dominate, with some customers having no internet service, highlighting diverse customer needs.
    
- Add-on services (Online Security, Device Protection, Tech Support, Streaming services) show moderate subscription rates, suggesting potential upsell arenas but also gaps in awareness or adoption.
    

## 4. **Contract and Billing Insights**

- Contract types vary, with a substantial share on month-to-month contracts, which statistically correlates with higher churn.
    
- Paperless billing is popular and may associate with ease of payment and customer satisfaction.
    
- Monthly charges average around $65 but range widely, reflecting heterogeneous service usage.
    
- Total charges correlate with tenure but exhibit outliers, indicating differing customer value and billing patterns.
    
- Payment methods show diversity—Electronic Check is common but potentially less stable compared to credit card or bank transfers.
    

## 5. **Churn Dynamics**

- Customers on month-to-month contracts with shorter tenure and higher monthly charges exhibit increased propensity to churn.
    
- Churn is less frequent among customers with longer contracts (one or two years), suggesting the success of contractual retention mechanisms.
    
- Use of bundled services and add-ons appears to reduce churn likelihood, indicating “stickiness” when multiple services are consumed.
    
- Senior citizens show nuanced churn behaviors and may require tailored engagement strategies.
    

## 6. **Additional Observations**

- Discrepancies in Total Charges vs Tenure hint at either billing irregularities or early churn without substantial billing accumulation.
    
- Customers paying with electronic checks have higher churn rates, indicating possible payment failure risks or convenience issues.
    
- Paperless billing adoption aligns somewhat inversely with churn, but further analysis might clarify causality.
    

## Recommendations for Senior Stakeholders

## 1. **Targeted Retention Programs**

- Prioritize customers on month-to-month plans, especially those with high monthly charges and low tenure. Tailored retention offers (discounts, upgrades, loyalty benefits) should be developed to reduce attrition.
    
- Monitor payment methods; encourage migration to more reliable electronic payment methods to minimize churn linked to payment failures.
    

## 2. **Senior Citizen Customer Engagement**

- Develop specialized service bundles, dedicated support, and communications targeting senior customers to improve satisfaction and retention.
    

## 3. **Service Bundling and Upselling**

- Promote bundled offerings including internet, device protection, and streaming services to enhance customer value and stickiness.
    
- Cross-sell add-on features with clear communication highlighting benefits to encourage adoption.
    

## 4. **Contract Strategy Refinement**

- Incentivize longer-term contracts through pricing or added benefits to reduce churn triggered by month-to-month subscriptions.
    
- Consider proactive engagement before contract renewal or termination points.
    

## 5. **Payment Experience Optimization**

- Simplify billing and payment processes, and encourage paperless billing and automated payments.
    
- Address pain points associated with electronic check payment to reduce churn risk.
    

## 6. **Data-Driven Predictive Analytics**

- Utilize the dataset to build and constantly refine churn prediction models that identify high-risk customers in real-time.
    
- Integrate predictive analytics with CRM systems to enable proactive retention campaigns.
    

## Conclusion

This detailed churn analysis elucidates multiple actionable insights about customer behavior, billing patterns, and service utilization. Executing these recommendations will likely reduce churn rates, improve customer lifetime value, and increase revenue stability. Adopting a data-driven approach emphasizes targeting specific customer segments and refining engagement and payment frameworks.
