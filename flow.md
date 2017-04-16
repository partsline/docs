![](/Users/milenkov/projects/Partsline/docs/assets/anatomy_search.png)

Shopping cart architecture. (Pick list?)

![](/Users/milenkov/projects/Partsline/docs/assets/anatomy_transaction.png)

What is the market doing with respect to fees? Is the supplier willing to pay a fee? Is the customer willing to pay a fee? 

From a fulfillment side, we escrow funds, we verify that the order was shipped, we verify that the order is received. Fulfillment receipts are used for tracking. Escrow is staged.

Onboarding:

1. Customer gave us their credit card.
2. Braintree, Stripe Connect, or reverse ACH transaction.
3. Onboarding for supplier, we can use reverse ACH. (Terry has the hookup) Or regular ACH. 
4. Debit is the fastest.

Exploratory diagrams:

1. Anatomy of the escrow
2. Notification system
3. Checkout process flow - search to payment
    * If searh query returns no matches, we provide the option for partsline to do a watchdog search for the customer
4. Using google for querys. Search engine.


Architecture overview: we need Sean on this.






