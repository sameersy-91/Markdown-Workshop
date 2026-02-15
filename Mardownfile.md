# Accept simple payments for a startup

Learn how to enable Stripe payments for your business without writing code.

This guide describes the actions you need to take in your Stripe integration to accept one-off payments as a startup.

## Create a Stripe account

Before integrating with Stripe, you must create a Stripe account.

1. [Create an account](https://dashboard.stripe.com/register) by entering your email address, full name and country, and creating a password.
1. Fill out your business profile.
1. In the Dashboard, click **Verify your email**. Stripe sends a verification email to your email address.
1. Verify your email address.

## Create a payment link

[Payment Links](https://docs.stripe.com/payment-links.md) let your customers pay you when you sell online. Create a single link that you can share with everyone.

### Create a payment link

1. In the Dashboard, open the [Payment Links](https://dashboard.stripe.com/payment-links/create/standard-pricing) page and click **+New**.
1. Select an existing product or click **+Add a new product**.
1. If you’re adding a new product, fill out the product details and click **Add product**.
1. Click **Create link**.

## Share the payment link with your customers

Use the Dashboard to copy your payment link and share it online. Click the copy icon next to an existing link on the [Payment Links](https://dashboard.stripe.com/payment-links/create/standard-pricing) page or go to the payment link’s details page. You can share your payment link multiple times and anywhere online, including:

- Emails
- Text messages
- Social media platforms

## Go live

1. In the Dashboard, open your [Account settings](https://dashboard.stripe.com/account/onboarding).
1. Enter your business type, tax details, business details, personal verification information and customer-facing information (for example, a statement descriptor).
1. Add bank details to confirm where to pay out your money.
1. Set up two-step authentication to secure your account.
1. You can optionally add automatic tax collection or revenue-based climate donations.
1. Review the information you entered and click **Agree and submit**.
1. After you activate your profile, Stripe updates you from sandbox mode to live mode.

Learn more about [activating your Stripe account](https://docs.stripe.com/get-started/account/activate.md).

## Next steps

After setting up your integration, we recommend you implement the following features:

- [Customise your checkout UI](https://docs.stripe.com/payment-links/customize.md) with brand settings.
- [Create a promotion code](https://docs.stripe.com/payment-links/promotions.md) to provide your customers with a discount.
- [Management fulfilment](https://docs.stripe.com/payment-links/post-payment.md) for your orders and view metrics.
- [Embed the payment link as a button](https://docs.stripe.com/no-code/payment-links.md?pricing-model=standard#embed-button) on your website.