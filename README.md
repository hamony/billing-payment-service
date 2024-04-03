# Billing-Payment-Service
## EventStorming Proccess
### Topic
payment

### Unstructured Exploration
1. PaymentAuthorizedEvent
Signals successful authorization of payment associated with a booking.
2. PaymentCompletedEvent
Indicates the successful completion of a payment transaction for a booking.
3. PaymentFailedEvent
Signals that a payment transaction for a booking has failed.

### Timelines
Happy Path Workflow:

### Commands
1. AuthorizePaymentCommand
Requests authorization for payment associated with a booking.
2. CompletePaymentCommand
Indicates the successful completion of a payment transaction for a booking.
3. FailPaymentCommand
Indicates the failure of a payment transaction for a booking.


