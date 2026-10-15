# Sensor Integration into the Asset Administration Shell via OPC UA for a Milling Machine as a Foundation for Predictive Maintenance

**Bachelor Thesis – B.Eng. Computer Engineering (Embedded Systems)**  
**Berlin University of Applied Sciences and Technology (BHT) · Fraunhofer IPK · 2026**

## Overview

This bachelor thesis investigates the integration of heterogeneous industrial machine and sensor data into a modular Digital Twin architecture.

The implemented system combines machine-internal data accessed via **OPC UA** with external sensor streams and provides live monitoring, persistent time-series storage and semantic representation using the **Asset Administration Shell (AAS)**.

The objective was to establish a reliable and extensible data foundation for future applications such as condition monitoring and predictive maintenance.

## Key Technologies

- Python
- OPC UA
- Asset Administration Shell (AAS)
- Eclipse BaSyx
- FastAPI
- JSONata
- MongoDB
- WebSockets
- React
- Chart.js
- Docker & Docker Compose

## System Architecture

The solution follows a modular architecture consisting of:

1. **Data acquisition** – machine signals via OPC UA and external sensor data
2. **Backend integration** – resilient communication services and data processing
3. **Semantic integration** – mapping selected OPC UA values into AAS submodels using Eclipse BaSyx
4. **Data persistence** – time-series storage in MongoDB
5. **Visualization** – web-based live monitoring of machine and sensor data

## My Contribution

My work included:

- Designing and implementing the data acquisition and integration pipeline
- Integrating external industrial sensor systems
- Developing backend communication services
- Building a unified interface for live monitoring
- Integrating selected OPC UA machine signals into AAS submodels
- Containerising the system for reproducible deployment
- Evaluating system behaviour under nominal, stress and fault scenarios

## Scope

The project focuses on reliable data acquisition, system integration and semantic representation.

Predictive-maintenance algorithms and machine-learning models were intentionally outside the scope of the thesis. The developed architecture instead provides the technical foundation required for future analytics and condition-monitoring applications.

## Repository Status

This repository is a **public portfolio version** of the bachelor thesis project.

Selected documentation, architecture material and non-confidential implementation examples will be added progressively. Internal infrastructure details, credentials and institution-specific configuration are intentionally excluded.
