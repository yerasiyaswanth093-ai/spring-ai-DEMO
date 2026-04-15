# spring-ai-DEMO

Demo Spring application integrated with AI features.

## Overview

This repository contains a demo Spring Boot application showcasing how to integrate AI-powered features into a Spring application. The project demonstrates basic setup, example AI integrations, and guidance for extending with real AI services.

## Features

- Spring Boot setup with recommended project structure
- Example AI integration points (text generation, embeddings, classification)
- Sample REST endpoints for interacting with AI features
- Dockerfile for containerization

## Getting Started

Prerequisites:
- Java 17+
- Maven 3.6+
- Docker (optional)

1. Clone the repository:

```bash
git clone https://github.com/yerasiyaswanth093-ai/spring-ai-DEMO.git
cd spring-ai-DEMO
```

2. Build and run the application:

```bash
mvn clean package
java -jar target/spring-ai-DEMO-0.0.1-SNAPSHOT.jar
```

3. Use the provided REST endpoints to interact with AI features (see API docs later)

## Extending

- Integrate a real AI provider by implementing the AI service interfaces under src/main/java
- Add tests and CI pipeline

## License

MIT
