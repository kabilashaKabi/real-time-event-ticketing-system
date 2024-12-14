# real-time-event-ticketing-system

A comprehensive real-time ticketing system with a **Backend**, and **Command-Line Interface**. This project is a real-time event ticketing system designed to simulate the interaction between vendors and customers. Vendors add tickets to a shared pool, and customers can purchase tickets from that pool. The system ensures that ticket limits, retrieval rates, and capacities are properly enforced, and provides real-time updates on ticket availability.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Backend](#backend)
  - [CLI](#cli)

---

## Features

- Vendor and Customer Simulation
- Real-Time Update.
- Configurable ticket parameters (capacity, release rate, retrieval rate).
- CLI for quick interaction and testing.
- Scalability for multiple vendors and customers.
-Validation

---

## Technologies Used

### Backend
- Java (Spring Boot)
- Maven for dependency management



### CLI
- Java-based
- Command-line ticket management and updates

---

## Project Structure

The repository is organized into three main components: **Backend**, and **CLI**.

---

### Explanation of Key Directories

- **Backend**:
  - Contains Spring Boot application for handling API requests, managing ticket pools
  

- **CLI**:
  - Command-line interface for interaction with the ticketing system and allowing configurations .


---

## Getting Started
### Prerequisites

Ensure you have the following installed:
- **Java 17+** for the Backend and CLI
- **Maven** for Backend and CLI dependency management

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/RealTimeTicketingSystem.git
   cd RealTimeTicketingSystem
   
2. **Setup Backend**:
   Navigate to the `Backend` directory and build the project:
   ```bash
   cd Backend
   mvn clean install
   


3. **Setup CLI**:
   Navigate to the `CLI` directory and install dependencies:
   ```bash
   cd ../CLI
   mvn clean install
   
---

## Usage

### Backend

1. **Navigate to the `Backend` directory**:
   ```bash
   cd Backend
   
2. **Run the application**:
   ```bash
   mvn spring-boot:run

3. **The backend will start on `(http://localhost:8080)`. Available endpoints**:
- API Base URL: `(http://localhost:8080)`



### CLI

1. **Navigate to the `CLI` directory**:
   ```bash
   cd ../CLI
   
2. **Run the CLI application**:
   ```bash
 - run Main class
   
3. **Follows the  prompts to manage the ticketing system through the terminal**



