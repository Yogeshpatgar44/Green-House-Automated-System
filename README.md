# Green-House-Automated-System

## Overview
This project automates a greenhouse system using three components:
1. **GreenHouse-Frontend**: Built using React.
2. **GreenHouse-Backend**: Developed with Python and Flask.
3. **GreenHouse-Arduino**: Controls the hardware using Arduino.

---

## How to Run the Project

### 1. GreenHouse-Frontend
The front end is built with **React**.

#### Steps to Run:
1. Navigate to the `GreenHouse-Front end` directory:
   ```bash
   cd GreenHouse-Front end
   ```
2. Install the necessary **node modules** using npm:
   ```bash
   npm install
   ```
3. Start the React development server:
   ```bash
   npm start
   ```

The React application should now be running at `http://localhost:3000`.

---

### 2. GreenHouse-Backend
The back end is built with **Python Flask**.

#### Steps to Run:
1. Navigate to the `GreenHouse-Backend` directory:
   ```bash
   cd GreenHouse-Backend
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   Make sure you have **Python** and **pip** installed.
3. Run the Flask app:
   ```bash
   python flask-app.py
   ```

The Flask backend should now be running, typically on `http://localhost:5000`.

---

### 3. GreenHouse-Arduino
The hardware component runs on **Arduino**.

#### Steps to Run:
1. Open the Arduino IDE.
2. Connect your Arduino board to the system.
3. Navigate to the `GreenHouse-Arduino` directory and upload the code to the Arduino board.

---

## Summary
Follow these steps sequentially:
1. Run the **frontend** React application.
2. Start the **backend** Flask server.
3. Upload the code to the **Arduino** hardware.

This will complete the setup for the **Green-House-Automated-System**.
