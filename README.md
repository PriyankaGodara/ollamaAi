# ollamaAi
# Ollama AI Chat Application

Ollama AI is a real-time AI-powered chat application leveraging **Flux streams** for asynchronous data streaming, built with **Spring Boot** in the backend. The app integrates **Deepseek AI models** via **Ollama**, providing intelligent conversational capabilities.

---

## **Features**
- **Real-time streaming chat** using Spring WebFlux.
- **AI-powered responses** through Deepseek models.
- **Seamless integration with Ollama** for managing AI models.
- **Scalable architecture** with reactive programming.
- **Spring Boot backend** with REST APIs.

---

## **Tech Stack**
- **Backend**: Spring Boot, Spring WebFlux
- **AI Integration**: Ollama, Deepseek AI models
- **Build Tool**: Maven/Gradle
- **Database**: (Optional) MongoDB or PostgreSQL

---

## **Project Structure**
```plaintext
ollama-ai/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.ollama.chat/
│   │   │       ├── config/        # WebFlux configuration
│   │   │       ├── controller/    # REST controllers
│   │   │       ├── service/       # Business logic for AI interaction
│   │   │       └── model/         # Data models
│   │   └── resources/
│   │       └── application.yml    # Spring configurations
│
├── pom.xml  # Maven dependencies
└── README.md
```

---

## **API Endpoints**
- `POST /chat/stream` – Start a streaming conversation with AI.
- `GET /models` – List available Deepseek models via Ollama.

---

## **Setup Guide**
### 1. Clone the repository:
```bash
git clone https://github.com/PriyankaGodara/ollamaAi.git
cd ollamaAi
```

### 2. Configure Ollama for Deepseek models:
- Install Ollama and configure Deepseek models as per [Ollama Docs](https://ollama.ai/docs).

### 3. Build the project:
```bash
./mvnw clean install
```

### 4. Run the application:
```bash
./mvnw spring-boot:run
```

---

## **Contribution Guide**
- Fork the repository.
- Create a feature branch.
- Commit your changes.
- Open a pull request.


