# Inter-Service Communication

This project demonstrates **inter-service communication** in a microservices architecture using **Spring Boot**, **Spring Cloud OpenFeign**, and **REST APIs**. It simulates communication between multiple services to showcase how microservices can interact efficiently and reliably.

## 🚀 Features

- 📡 Service-to-service communication via OpenFeign
- ⚙️ REST API endpoints for communication simulation
- 🧪 Easy to run and test locally
- 🧩 Modular structure for scalability and flexibility

## 🏗️ Project Structure

```
Inter-Service-Communication/
├── provider-service/       # Simulated service provider
├── consumer-service/       # Consumer calling the provider
├── README.md               # Project documentation
└── pom.xml                 # Maven configuration
```

## 📦 Technologies Used

- Java 17+
- Spring Boot
- Spring Cloud OpenFeign
- Maven
- RESTful APIs

## 🧑‍💻 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/Subhadip956425/Inter-Service-Communication.git
cd Inter-Service-Communication
```

2. **Navigate to Each Service and Run Individually**

```bash
cd provider-service
./mvnw spring-boot:run
# or use: mvn spring-boot:run

cd ../consumer-service
./mvnw spring-boot:run
# or use: mvn spring-boot:run
```

> You can also run both services in IntelliJ IDEA or any IDE that supports Maven projects.

## 📍 Endpoints Example

- `GET /instance-info` → Returns basic info from provider-service
- `GET /fetch-provider-info` → Consumer calls provider via Feign Client

## 📌 Use Case

This project is ideal for learning or demonstrating:
- Feign-based service calls
- Setting up microservices locally
- REST API communication patterns

## 🛠️ Future Improvements

- Add Eureka or Spring Cloud Discovery
- Implement circuit breakers with Resilience4j
- Add Docker support for containerized deployment

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

**Developed with ❤️ by [Subhadip Guchhait](https://github.com/Subhadip956425)**
