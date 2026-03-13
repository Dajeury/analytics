{% docs stg_stripe__payments_description %}

This model processes and transforms raw Stripe payment data into a
structured format for analysis. It includes details about each payment, such as
the payment method, status, creation date, and amount, facilitating financial
reporting and transaction analysis.

{% enddocs  %}

{% docs stripe_payment_method %}

| payment_method | definition |
|----------------|------------|
| credit_card    | Payment made using a credit card          |
| bank_transfer  | Payment made via direct bank transfer     |
| coupon         | Payment applied using a discount coupon   |
| gift_card      | Payment made using a gift card balance    |

{% enddocs  %}