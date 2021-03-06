**To enable or disable email feedback forwarding for an Amazon SES verified identity**

The following example uses the ``set-identity-feedback-forwarding-enabled`` command to enable a verified email address to receive feedback notifications by email::

    aws ses set-identity-feedback-forwarding-enabled --identity user@example.com --forwarding-enabled

Output::    

 {
    "ResponseMetadata": {
        "RequestId": "d20fd97e-d48c-11e2-bb91-ebbd7d5a4bee"
    }
 }


For more information about feedback notifications, see `Bounce and Complaint Notifications in Amazon SES`_ in the *Amazon Simple Email Service Developer Guide*.

.. _Bounce and Complaint Notifications in Amazon SES: http://docs.aws.amazon.com/ses/latest/DeveloperGuide/bounce-complaint-notifications.html

