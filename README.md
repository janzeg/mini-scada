# 🏭 MiniSCADA
A SCADA system designed for visualization and control of industrial processes.

The project is divided into three main components. Repository references:
- **[mini-scada-frontend](https://github.com/janzeg/mini-scada-frontend)** – Angular web application for visualization
- **[mini-scada-backend](https://github.com/janzeg/mini-scada-backend)** – Spring Boot backend managing process data and WebSocket communication  
- **[mini-scada-plc-controller](https://github.com/janzeg/mini-scada-plc-controller)** – PLC controller (CODESYS) for the process control


## Table of contents
* [Technologies](#technologies)
* [Architecture overview](#architecture-overview)
* [Features](#features)
* [Screenshots](#screenshots)
* [Author](#author)


## Technologies
### Backend
* Java: 21  
* Spring Boot: 3.5.6  
* Eclipse Milo (OPC UA Client SDK): 1.0.6
* MySQL: 8.0.42

### Frontend
* Angular: 20.3.2  
* TypeScript: 5.9.2  

### PLC Controller
* CODESYS V3.5.21.0


## Architecture overview
<img width="820" height="250" alt="Diagram drawio (5)" src="https://github.com/user-attachments/assets/e327bf69-b3d3-49c9-99e7-088ad03877f1" />


## Features
### Ready:
* Control and simulation of industrial process (CODESYS)
* Process visualization
* Real-time data exchange between PLC and backend via OPC UA
* Real-time data exchange between backend and frontend via WebSocket
* Displaying recipe table
* Creating and deleting recipes
* REST API for recipes
* Storing recipes in the database

### TO DO:
* Creation and selection of production orders (recipe collections)
* Sending production orders to the PLC
* Alarm display and logging
* History of completed production orders
* Visualization of process variables over time (charts)


## Screenshots
<img width="1500" height="845" alt="image" src="https://github.com/user-attachments/assets/f0118a92-0710-4a48-9286-3bfd49be4907" />

<img width="1500" height="557" alt="image" src="https://github.com/user-attachments/assets/bc92c5da-1167-4d01-ac60-d3ae137ec007" />

<img width="1500" height="557" alt="image" src="https://github.com/user-attachments/assets/d1f247ff-c78e-42b3-8995-650893106814" />


## Author
Created by Jan Zegarek
2025
