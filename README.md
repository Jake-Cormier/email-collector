# Email Collector

 Site for testing
 https://codepen.io/JakeCormier/pen/YZvBLN.

 A simple mailing list trigger to add to websites

 # Quick Rundown

 The plan is to invoke a lambda function when the user enters their email and clicks the **Sign Up** button. The function will then add their email address to a simple DyanamoDB table that SES will use in the future. At a later date SES will allow users to unsubscribe from the mailing list and their removal will be completely automated.

 ## Services to Implement

  - SES
  - AWS SDK
  - DynamoDB
  - Lambda
  - API Gateway?
  - SNS??
