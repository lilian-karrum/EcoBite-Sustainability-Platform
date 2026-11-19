# 🌱 EcoBite — Smart Food Sustainability Platform

EcoBite is a software engineering project exploring how a digital platform can support food-waste reduction, food redistribution, and sustainable habits. The project includes a browser-based interactive dashboard prototype and supporting system-design documentation.

## Overview

The EcoBite concept brings together different participants in the food ecosystem, including households, restaurants, food banks, and farmers. The dashboard prototype demonstrates role-specific features and ways to engage users in sustainable practices.

## Features demonstrated

- **Role-based dashboards:** Select a restaurant, household, food bank, or farmer role to view relevant features.
- **Food sustainability workflows:** Role-specific options for food donations, inventory tracking, resource discovery, distribution coordination, and produce listings.
- **EcoPoints tracker:** Simulated earning and redeeming of reward points, with balances and activity history.
- **Crop-health monitoring:** Displays sample agricultural sensor readings and flags abnormal conditions, including low soil moisture, unusual temperatures, and missing pH values.
- **Interactive interface:** Responsive dashboard, navigation, and modal dialogs.

> **Prototype note:** This repository showcases a front-end demonstration. Authentication is simulated, sensor readings are embedded sample data, and the points system runs locally in the page. It is not a production service or a live sensor integration. Crop-condition explanations use rule-based checks, not a trained machine-learning model.

## Technologies

- HTML5
- JavaScript
- Tailwind CSS (via CDN)
- Font Awesome (via CDN)
- Typed.js (via CDN)

## Run locally

1. Download or clone this repository.
2. Open `EcoBite.html` in a modern web browser.
3. Sign in with the **demo credentials displayed on the login page**.
4. Select a user role and explore the dashboard, EcoPoints, and crop monitoring views.

An internet connection may be needed to load the external CSS, icon, and animation libraries from their CDNs. No database or backend installation is required for this prototype.

## System architecture and documentation

The project documentation includes a conceptual three-layer architecture:

1. **Presentation layer:** User-facing application interface.
2. **Application layer:** User-request handling and business rules.
3. **Data layer:** Conceptual data storage and retrieval.

This architecture represents the **proposed system design**, rather than a claim that the HTML prototype deploys a separate application server and database.

If included in this repository, see `docs/System_Architecture.png` for the diagram and the project reports for additional design and testing work.

## Project scope

EcoBite was developed as an academic software engineering project involving requirements, interface design, architecture modeling, and testing. The code in this repository represents the interactive dashboard prototype; additional features described in project documentation may be conceptual rather than fully implemented.

## Contributors

A collaborative university project. See the accompanying project documentation for team details and responsibilities.

## Future improvements

- Replace mock authentication with secure user accounts.
- Connect dashboards to a backend and persistent database.
- Integrate real inventory, donation, and pickup workflows.
- Connect crop monitoring to live sensor data.
- Add automated tests and deployment instructions.
