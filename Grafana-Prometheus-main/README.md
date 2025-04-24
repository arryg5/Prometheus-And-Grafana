# Grafana-Prometheus-main

<div align="center">
    <img src="assets/Grafana.png" alt="Grafana Logo" style="width: 200px; height: auto;">
    <img src="assets/Prometheus.png" alt="Prometheus Logo" style="width: 200px; height: auto;">
</div>

# Monitoring Stack with Prometheus and Grafana

Created by Aryaan Ghosal | SAP- 500105236

This project sets up a complete monitoring stack using Prometheus and Grafana with Node Exporter for system metrics collection.

## Architecture

-   **Prometheus**: Time-series database for metrics collection  
-   **Grafana**: Visualization platform for metrics  
-   **Node Exporter**: Collects system metrics from the host machine

## Prerequisites

-   Docker  
-   Docker Compose  

## Quick Start

1. Clone this repository  
2. Run the monitoring stack:

```bash
docker-compose up -d
