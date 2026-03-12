# AI Powered Shipment Delay Prediction System

## Project Description
This project is a backend system developed using Spring Boot that manages shipment data and predicts potential delivery delays using an AI model. The system analyzes logistics factors like distance, traffic, weather, and vehicle type to estimate possible shipment delays.

The goal of this system is to help logistics companies identify delivery risks early and improve shipment efficiency.

---

## Features
- Create shipment records
- Retrieve shipment details
- Predict shipment delay using AI
- REST API based backend
- Microservice architecture

---

## Technologies Used
- Spring Boot
- Java
- H2 Database
- FastAPI (Python AI service)
- Postman for API testing

---

## API Endpoints

### Create Shipment
POST /shipments

### Get All Shipments
GET /shipments

### Predict Delay
GET /shipments/predict

---

## Example Shipment JSON

```json
{
 "origin": "Delhi",
 "destination": "Mumbai",
 "distanceKm": 1400,
 "weather": "Rain",
 "traffic": "High",
 "vehicleType": "Truck",
 "dayOfWeek": "Monday",
 "slaHours": 48,
 "carrier": "BlueDart"
}

