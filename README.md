# Observability Stack with Docker Compose

This project sets up an observability stack using Docker Compose. It includes Prometheus for metrics collection, Grafana for visualization, Jaeger for tracing, and Loki for log aggregation. Additionally, it runs a simple Flask application with custom logging.

## Project Structure

- **docker-compose.yml**: Configuration for the entire observability stack.
- **flask.py**: A simple Flask app with custom logging.
- **loki/**: Configuration files for Loki log aggregation.
- **monitoring_screenshots/**: Contains screenshots of metrics, logs, and traces for report purposes.
- **Insights.pdf**: A report providing insights and analysis of the project.

## Getting Started

Follow the steps below to build and start the containers:

### Prerequisites

- Ensure you have Docker and Docker Compose installed on your system.

### Build and Start the Containers

```bash
docker-compose up -d
```

### Accessing the Services

Once the containers are up and running, you can access the following services:

- **Prometheus**: [http://localhost:9090](http://localhost:9090)
- **Grafana**: [http://localhost:3000](http://localhost:3000)
- **Jaeger**: [http://localhost:5775](http://localhost:5775)

### Checking Logs and Metrics

1. **Grafana Dashboard**: Use Grafana to view metrics and logs collected from the Flask application.
2. **Jaeger Traces**: View traces and spans for the application in Jaeger.

## Monitoring Insights

- Navigate to the `monitoring_screenshots/` directory to view screenshots showcasing the metrics, logs, and traces captured during the monitoring process.
- For more detailed insights and analysis, refer to the `Insights.pdf` report.

## Contribution

Contributions to improve this project are welcome. Feel free to open issues or create pull requests.


