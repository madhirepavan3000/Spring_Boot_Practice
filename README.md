# Spring_Boot_Practice




```

**Key sections:**
1. **StoreApplication.java** - Entry point with Spring Boot initialization and dependency injection demonstration
2. **PaymentService.java** - Interface showing the Strategy pattern contract
3. **OrderService.java** - Business logic with constructor injection and @Autowired usage
4. **PayPalPaymentService.java** - PayPal implementation with @Service annotation
5. **StripePaymentService.java** - Stripe implementation (not active as a bean)
6. **HomeController.java** - Web controller with @Value property injection

**Major concepts explained:**
- Dependency Injection (DI) with constructor-based injection
- Strategy Pattern for multiple payment processors
- Spring annotations (@SpringBootApplication, @Service, @Controller, @Autowired, @RequestMapping, @Value)
- IoC Container management
- Property externalization

