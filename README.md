PayPal payment integration using Spring Boot

Hello, after three weeks of work, I recently completed a project using Java and Spring Boot, incorporating Thymeleaf templates. The project focuses on integrating a payment gateway with PayPal
The project also provides a comprehensive understanding of the Sandbox environment and guides on handling payment APIs in our application when receiving payments from clients. It delves into the process of issuing payments and facilitating transfers.
Below are the steps I followed:

1. Set up a standard project with all dependencies in a Spring Boot Maven project.
2. Created an account on developer.paypal.com.
3. Activated a Sandbox account.
4. Generated credentials for Rest API apps on developer.paypal.com.
5. Deactivated NVP/Soap API apps.
6. Exported sandbox username, client ID, and secret key for use in Spring Boot.
7. Activated the action and granted permission to SandBox WEBHOOKS.
8. Configured Sandbox in the application.properties/application.yml file of the Spring Boot project.
9. Created Controller, Service, Configuration, Entity, and Main classes.
10. In the Configuration class, configured sandbox credentials in key-value pairs for encryption.
11. Implemented @PostMapping in the Controller to collect payments via the sandbox.
12. Added @GetMapping to inform users whether the payment was successful or not.
13. In the service class, utilized Spring Boot for PayPal payment integration, creating and executing payments through the PayPal REST API. The APIContext was used for configuration, including methods for payment creation and execution.
14. Selected the mode in the configuration class.
15. Created JSP pages and linked them through return methods.
16. Ran the project and checked for any issues.
17. If no issues, created a JAR file, ran it, and accessed localhost to initiate payments.
18. After completion, observed the payment issued in the PayPal app, and waited for some time to generate an invoice.
19. Successfully completed the payment integration. In order to perform more health checks and enhance performance, you can also add Actuator.
20. Similar integration can be achieved with third-party APIs like Paytm and Razorpay for additional payment options.

HashNode : https://gevariyameetb.hashnode.dev/paypal-payment-integration-using-spring-boot
GithHub : https://github.com/gevariyameetb/PayPal-payment-integration-using-Spring-Boot
