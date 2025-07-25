---
title: About billing for GitHub Copilot in your organization
shortTitle: Billing for organizations
intro: 'Learn about pricing and billing cycles for {% data variables.product.prodname_copilot_short %} in your organization.'
permissions: Organization owners
product: '{% data variables.copilot.copilot_for_business %}'
versions:
  feature: copilot
topics:
  - Copilot
redirect_from:
  - /copilot/managing-copilot/managing-github-copilot-in-your-organization/managing-the-copilot-subscription-for-your-organization/about-billing-for-github-copilot-in-your-organization
  - /copilot/managing-copilot/managing-github-copilot-in-your-organization/managing-the-copilot-plan-for-your-organization/about-billing-for-github-copilot-in-your-organization
  - /copilot/concepts/copilot-billing/about-billing-for-github-copilot-in-your-organization
  - /copilot/concepts/copilot-billing/billing-for-organizations
contentType: concepts
---

## About pricing for {% data variables.product.prodname_copilot_short %} in your organization

{% data variables.copilot.copilot_business_short %} plans are available on a monthly cycle. The plans are billed at the end of each cycle, at {% data variables.copilot.cfb_price_per_month %} per user per month.

## Premium requests

Paid {% data variables.product.prodname_copilot_short %} plans include premium requests. Premium requests use advanced models and features and are subject to monthly allowances or potential overage costs. See [AUTOTITLE](/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/monitoring-usage-and-entitlements/avoiding-unexpected-copilot-costs).

## About the billing cycle for {% data variables.product.prodname_copilot_short %} in your organization

Billed users are calculated at the end of each billing cycle, based on the number of {% data variables.product.prodname_copilot %} seats that are assigned. You can add or remove seats at any time during the billing cycle.

* **Any seat assigned part way through the billing cycle** is prorated based on the number of days remaining in the cycle.
* **Any seat assignment cancellation during a billing cycle** takes effect at the beginning of the next cycle. The user can access {% data variables.product.prodname_copilot %} until the end of the cycle.
* **Any user removed from the organization during a billing cycle** loses access to {% data variables.product.prodname_copilot %} immediately. Billing for that user stops at the end of the cycle. If the user is restored to the organization during the billing cycle, they will regain access to {% data variables.product.prodname_copilot %} immediately.

If your organization belongs to an enterprise, your enterprise will be charged on whichever payment method you’ve set up for the organization account, such as a credit card or a Microsoft Azure subscription. If an organization with {% data variables.product.prodname_copilot %} seats is removed from an enterprise, billing for those seats will stop at the end of the billing cycle. The users who had seats assigned by the removed organization will lose access to {% data variables.product.prodname_copilot %} unless they receive a seat through another organization.

{% data reusables.billing.authorization-charge %}

> [!NOTE] {% data variables.product.prodname_copilot %} billing operates in Coordinated Universal Time (UTC), but it calculates your bill according to the timezone of your billing cycle. For example, if you're billed through Azure and your current billing cycle ends at 11:59 PM EST on December 1st, canceling a seat at 7:00 PM EST on December 1st might show the seat cancellation at 12:00 AM UTC on December 2nd. However, the seat would end within the billing cycle that you requested the cancellation, and you would not pay for that seat in the following cycle.

### About seat assignment for {% data variables.product.prodname_copilot_short %} in your organization

A {% data variables.product.prodname_copilot_short %} seat is a license to use {% data variables.product.prodname_copilot_short %}, which is granted to a unique user account through an organization's {% data variables.copilot.copilot_business_short %} plan. Each month, the organization is charged for the number of assigned seats.

Removing all assigned {% data variables.product.prodname_copilot_short %} seats in your organization will cancel your organization's {% data variables.product.prodname_copilot_short %} plan.

Seat assignment is managed by organization owners. See [AUTOTITLE](/copilot/managing-copilot/managing-github-copilot-in-your-organization/managing-access-to-github-copilot-in-your-organization/granting-access-to-copilot-for-members-of-your-organization).

If you are a member of an organization with a {% data variables.product.prodname_copilot_short %} plan, to use {% data variables.product.prodname_copilot_short %}, you will need to be assigned a seat by an organization owner.

{% data reusables.copilot.copilot-one-account %}

### About billing through Azure

When you connect an Azure subscription to your organization account and enable metered billing via Azure, metered usage will start to be sent to Azure. You will be billed through {% data variables.product.prodname_dotcom %} for usage from the start of the current billing cycle to when you enabled metered billing via Azure, on your next billing date. The period between the date you connected your Azure subscription and enabled metered billing via Azure, and the end of the calendar month will be charged in Azure on the first of the month. For more information, see [AUTOTITLE](/billing/managing-the-plan-for-your-github-account/connecting-an-azure-subscription).

> [!NOTE] Usage data is sent to Azure daily, but you are billed at the end of the month based on the number of seats used. This means that although you can track your daily spending (number of seats in this case), actual payments are processed monthly.

## Further reading

* [AUTOTITLE](/copilot/about-github-copilot/subscription-plans-for-github-copilot)
* [AUTOTITLE](/copilot/managing-copilot/managing-github-copilot-in-your-organization/managing-the-copilot-subscription-for-your-organization)
* [AUTOTITLE](/billing/managing-your-billing/managing-your-payment-and-billing-information)
