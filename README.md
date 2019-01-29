# serverless-aws-experience

A sample project using Serverless framework, where I customise *Cloud Formation* in a separate file.

Cloud Formation config automatically enables **XRay Tracing**, **CloudWatch Logs** and **Detailed CloudWatch Metrics** on deploy, as shown below:

![alt APIGateway](https://s3.amazonaws.com/private-mendes/api-gateway-tracing.png)

Besides, it changes the response body of the API Gateway's Gateway Responses, and it also extends the cors configurations, in this case, adding an allowed preflight header called *X-Access-Token*.
