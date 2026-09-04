# Microservices Services (Parent Repository)

## Student Information
- **Student Name:** Shavindi R. Aloka
- **Student Number:** [241711095]
- **Slack Handle:** [shavindi aloka]
- **GCP Project ID:** [project-c2d114f1-e0c4-497d-a05]

---

## Project Description
This repository acts as the main parent (super) repository for the backend business microservices. It utilizes Git Submodules to manage individual service repositories (`book-service`, `borrow-service`, and `user-service`) and includes process management and build configurations.

---

## Technology Stack
- **Language:** Java 25
- **Framework:** Spring Boot (Latest), Spring Cloud
- **Data Access:** Spring Data
- **Databases:** Postgres SQL and MongoDB (Relational and Non-Relational integration)
- **Process Manager:** PM2 (for automatic restarts and process management)

---

## Included Submodules
This repository contains the following service submodules:
1. **`book-service`** - Manages library book records and related operations.
2. **`borrow-service`** - Handles donations and financial records.
3. **`user-service`** - Manages user authentication, profiles, and data.

---

## Setup / Getting Started Instructions
1. Clone this parent repository along with all its submodules:
   ```bash
   git clone --recursive https://github.com/Shavindi0609/eca-backend-services.git
