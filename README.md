# Spring Boot Payment Gateway Simulation

Welcome to my first Spring Boot project! 🚀  
This application simulates a simple payment gateway using a controller, service layer, and an interface-driven approach for handling different payment providers.

## 🧩 Project Structure

- **Controller**  
  Handles incoming HTTP requests and interacts with the service layer to process payments.

- **Service Layer**  
  Contains:
    - `PaymentService` *(Interface)*: Defines the common contract for any payment provider.
    - `PaypalPaymentService`: A concrete implementation that simulates payments through PayPal.
    - `StripePaymentService`: Another implementation simulating payments via Stripe.
    - `OrderService`: A service class to help manage payment logic or routing between providers.

## ⚙️ Features

- Basic simulation of two popular payment gateways: **PayPal** and **Stripe**.
- Clean separation of concerns using interfaces and service implementation classes.
- Built with **Spring Boot** for rapid development and dependency injection.

## 🏁 Getting Started

### Prerequisites

- Java 17+
- Maven or Gradle
- IDE (like IntelliJ IDEA or Eclipse)

### Running the App

1. Clone the repo:
   ```bash
   git clone https://github.com/ritaCosta93/spring-boot-project1.git
   cd springboot-payment-sim
