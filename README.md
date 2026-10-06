# Motor Heurístico de Deteção de Fraudes (TCC) 🛡️

Este projeto é um Motor Heurístico desenvolvido em Java com Spring Boot. O seu objetivo é analisar mensagens (como SMS), aplicar regras de deteção baseadas em heurística e calcular uma pontuação de risco (Score) para determinar se a mensagem é maliciosa ou não. Todo o histórico de análises é guardado numa base de dados PostgreSQL.

## 🛠️️ Tecnologias Utilizadas
* **Java 25**
* **Spring Boot 4.1.1**
* **PostgreSQL** (via Docker)
* **JPA / Hibernate** (ORM e Auto-criação de tabelas)
* **Maven** (Gestão de dependências)

## 📋 Pré-requisitos
Antes de executar o projeto, certifique-se de que tem instalado na sua máquina:
* [Java JDK 25](https://jdk.java.net/)
* [Docker Desktop](https://www.docker.com/products/docker-desktop) (para rodar o banco de dados)
* Uma IDE (ex: IntelliJ IDEA)
* [Postman](https://www.postman.com/) ou Insomnia (para testar a API)

## 🚀 Como Executar o Projeto

### 1. Subir a Base de Dados (Docker)
O projeto utiliza um contentor Docker para o PostgreSQL. Na raiz do projeto (onde está o ficheiro `docker-compose.yml`), abra o terminal e execute:
```bash
docker-compose up -d
