# PayPalExercise
 Repository for Team PayPal's in-class exercise.

Class exercise for Team PayPal, walks students through the basics of the PayPal SDK.

Recommended extension: Live Server, for real-time updates as you work through the exercise.

Link to the SDK: https://developer.paypal.com/sdk/js/reference/

GUIDE TO COMPLETION:
STEP 1: ADDING SDK SCRIPT
    Replace the placeholder client id with 'sb', used for testing purposes.
STEP 2: ADDING BUTTON CONTAINER
    In a div, enter the id 'paypal-button-container'.
STEP 3: INPUT FIELD
    Create an input field. Input type is 'number', id is 'payment-amount', placeholder is your own message asking for a payment amount, value is '10.00'.
STEP 4: AMOUNT FROM INPUT FIELD
    Fill in with 'payment-amount', declared in step 3.
STEP 5: CUSTOM CONFIRMATION MESSAGE
    Fill in the alert with your own personal message that thanks the payer for their purchase. 
    Payer's name: details.payer.name.given_name
    Payment amount: details.purchase_units[0].amount.value
STEP 6: ERROR MESSAGE
    Fill in the alert with your own personal error message.
