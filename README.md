# Fish Farm Management System - Pesca Milagrosa

## Overview
The **Fish Farm Management System** is designed to streamline and automate the day-to-day operations of the Pesca Milagrosa fish farm. This system focuses exclusively on fish-related activities, ensuring efficient management of resources, improved fish health monitoring, and data-driven decision-making.

---

## Features

### 1. **Fish Growth Tracking**
- Records and monitors fish growth metrics (e.g., size, weight, species).
- Allows users to set growth targets and track progress.

### 2. **Health Monitoring**
- Logs fish health information, including illnesses and treatments.
- Provides alerts for any irregularities detected in fish health.

### 3. **Feed Schedule Management**
- Maintains a daily schedule for feeding the fish.
- Tracks feed quantities and types for different tanks or fish groups.

### 4. **Water Quality Monitoring**
- Logs daily water quality parameters such as pH, temperature, and dissolved oxygen levels.
- Generates alerts if any parameter goes out of the safe range.

### 5. **Inventory and Automated Purchase Orders**
- Tracks stock levels of essential supplies like fish food, molasses, and salt.
- Automatically generates purchase orders when supplies reach a predefined threshold.

### 6. **Report Generation**
- Produces detailed reports on fish growth, health, and farm performance.
- Allows exporting reports for record-keeping and analysis.

### 7. **Database Management**
- Stores all farm data securely in a structured database.
- Supports CRUD operations (Create, Read, Update, Delete) for all entities in the system.

---

## Database Schema

### Entities and Relationships
- **Fish**: Tracks species, growth metrics, and health data.
- **Feed Schedule**: Manages feeding times, types, and quantities.
- **Water Quality**: Logs daily readings of key water parameters.
- **Supplies**: Manages inventory levels and purchase orders.
- **Reports**: Stores and retrieves farm performance data.

### Example Tables:
- `fish`: Contains details like species, weight, size, and health status.
- `feed_schedule`: Tracks feeding times, feed type, and quantity.
- `water_quality`: Logs pH, temperature, and oxygen levels.
- `supplies`: Monitors inventory and triggers purchase orders.
- `reports`: Stores daily and monthly performance data.

---

## Usage

1. **Input Data**: 
   - Add fish growth metrics, health logs, and feeding schedules via the system.
2. **Monitor Water Quality**:
   - Enter water parameter readings daily to track tank conditions.
3. **Track Supplies**:
   - Use the inventory management feature to prevent stock shortages.
4. **Generate Reports**:
   - Generate and review reports to evaluate farm performance and take action.

---

## Technology Stack

- **Frontend**: Designed with a user-friendly interface for easy data entry and monitoring.
- **Backend**: Handles data processing and logic for managing farm operations.
- **Database**: Stores and organizes all farm-related data securely.
- **APIs**: Enables smooth communication between the frontend and backend.

---

## Future Enchancements

1. **Iot**: 
Integration with IoT devices for real-time water quality monitoring.
2. **Analytics**: 
Advanced analytics for predictive insights on fish growth and health.
3. **Multi-language**: 
Multi-language support for ease of use across regions.
