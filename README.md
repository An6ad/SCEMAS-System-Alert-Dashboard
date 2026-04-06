# SFWRENG 3A04 - Deliverable 4 - Group 3

## Team Members:

- Angad Chhabra
- Jerry Jing
- Danyal Yousuf
- Kristian Diana

This project is a full-stack Environmental Monitoring and Alert System that simulates real-time sensor data, processes it using a Blackboard architectural pattern, and generates alerts and advisories based on defined thresholds.

The backend is built with Flask and is responsible for ingesting sensor data (simulated or real), aggregating environmental metrics, evaluating alert conditions, and managing alerts, advisories, and audit logs. The system ensures that duplicate alerts are avoided by maintaining a single active alert per zone and metric combination.

The frontend is developed using React (Vite) and provides interfaces for viewing aggregated environmental data, monitoring active alerts, and performing operator actions such as acknowledging and resolving alerts.

Key features include:

Real-time sensor data simulation
Aggregated environmental metrics (average, min, max)
Threshold-based alert generation
Alert deduplication to prevent spam
Advisory generation for affected zones
Operator workflows (acknowledge/resolve alerts)
Audit logging for system actions
RESTful API design for frontend integration

This project demonstrates concepts in software architecture, including separation of concerns, modular design, and event-driven processing using a Blackboard model.
