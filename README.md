# DeliverySystemApacheKafka

# Spring Boot Projects: Delivery Boy & End User

This repository contains two Spring Boot projects simulating a delivery system with two roles:
- **Delivery Boy**: Handles delivery updates.
- **End User**: Receives delivery status updates.

## Project Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/springboot-delivery-demo.git
```
2. Import both projects into your IDE (Spring Tool Suite, IntelliJ, etc.).

## Running Projects
1. **Run the Delivery Boy project:**
```bash
cd delivery-boy
./mvnw spring-boot:run
```
2. **Run the End User project:**
```bash
cd end-user
./mvnw spring-boot:run
```

### Run in Spring Tool Suite (STS)
- Right-click each project > Run As > Spring Boot App.
- Ensure both projects run on different ports.

## Tech Stack
- Java
- Spring Boot
- Kafka (Optional for real-time communication)

## Contributing
Feel free to fork and make improvements. Submit a pull request when ready.
