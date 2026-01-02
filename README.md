# Cloud-Monitoring-Pipeline
AWS Observability & Alerting Stack
This project demonstrates a complete monitoring pipeline deployed on an AWS EC2 instance. It uses Prometheus for metrics, Loki for logs, and Grafana for visualization, with an automated AWS SNS email alerting system.
Implementation Details
* Cloud Infrastructure: Deployed on an EC2 t3.micro instance in the eu-north-1 region.
* Metric Collection: Configured Prometheus to scrape hardware metrics via Node Exporter.
* Log Aggregation: Integrated Grafana Loki to centralize system logs.
* Automated Alerting: Established a threshold-based alert system using AWS SNS to notify via email when system limits are reached.
