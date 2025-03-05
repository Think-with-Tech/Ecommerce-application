# E-Commerce Application

# This simple E-Commerce app is built with Flask and Docker.

## Features
- Home page
- Products listing
- Checkout page
- Green background UI
- Dockerized for easy deployment

## Installation
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python app/app.py
   ```

## Docker Build & Run
1. Build the Docker image:
   ```
   docker build -t ecommerce-app .
   ```

2. Run the container:
   ```
   docker run -p 5000:5000 ecommerce-app
   ```

3. Open in browser:
   [http://localhost:5000](http://localhost:5000)

