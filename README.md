# Observability with Prometheus, Loki, Jaeger, and Grafana

This project demonstrates the integration of **Prometheus**, **Loki**, **Jaeger**, and **Grafana** for monitoring and logging in a containerized environment. It includes a Flask application with custom logs, along with the necessary configurations for scraping metrics, tracing requests, and visualizing logs and metrics on Grafana dashboards.

## Project Overview

The project includes:
- A sample Flask application with custom logging.
- Prometheus for scraping metrics.
- Loki for log aggregation and visualization.
- Jaeger for tracing HTTP requests.
- Grafana dashboards to display metrics and logs.



## Getting Started

To get the project up and running locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/GOURIDO/observability.git
   cd observability
Build and start the containers using Docker Compose:


docker-compose up -d
Access the following services:

Prometheus: http://localhost:9090

Grafana: http://localhost:3000

Jaeger: http://localhost:5775

Check the logs and metrics from the Grafana dashboard, and view traces on Jaeger.

Project Structure
docker-compose.yml: Configuration for the entire observability stack.

flask.py: A simple Flask app with custom logging.

loki/: Configuration for Loki log aggregation.

monitoring_screenshots/: Screenshots of metrics, logs, and traces for report purposes.

Insights.pdf: Report containing insights and analysis of the project.
