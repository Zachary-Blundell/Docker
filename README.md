# Docker Repository

This repository contains Docker Compose configurations for various self-hosted applications.

## 📁 Directory Structure

```
├── pi-hole/              # DNS & Ad-blocking server
├── stirling-pdf/         # PDF processing tool with OCR
├── homepage/             # Dashboard service
├── open-webui/           # Web-based AI chat interface
├── nextcloud/            # File hosting and collaboration
│   ├── nextcloud/        # Main Nextcloud instance
│   ├── onlyoffice/       # Document editor
│   └── whiteboard/       # Collaborative whiteboard
├── monitoring/           # Observability stack
│   ├── grafana/          # Visualization dashboard
│   ├── prometheus/       # Metrics collection
│   └── cadvisor/         # Container resource metrics
├── guacamole/            # Remote desktop gateway
├── portainer/            # Docker management UI
└── proxy/                # Proxy configuration

```

## 🚀 Quick Start

### Pihole (DNS & Ad-blocking)

```bash
cd pi-hole
docker compose up -d
```

- **Port**: `192.168.1.101` → DNS (53), API (8081)
- **Network mode**: Host

### Stirling-PDF

```bash
cd stirling-pdf
docker compose up -d
```

- **Port**: `8881`
- Features: Split, rotate, rename PDFs, OCR, prepare for email

### Homepage

```bash
cd homepage
docker compose up -d
```

- **Port**: `3001`
- Displays status of all Docker containers

### Open-WebUI

```bash
cd open-webui
docker compose up -d
```

- **Port**: `8088`
- AI-powered web chat interface

### Nextcloud

```bash
cd nextcloud/nextcloud
docker compose up -d
# Configure onlyoffice or whiteboard sub-services similarly
```

### Monitoring Stack

```bash
cd monitoring
docker compose up -d
# Configures Grafana, Prometheus, and cadvisor for container monitoring
```

## 🔧 Environment Variables & Configuration

Each service defines its own environment variables in the respective `compose.*` files. Common patterns:

- Docker volumes for persistent data
- Internal ports mapped to host IPs (e.g., `192.168.1.101`)
- Restart policies set to `unless-stopped` or `always`

## 📝 Additional Notes

- Use `.env.example` files where available for environment customization
- Volume mounts use relative paths from repo root
- Network ports should be updated if using different IP addresses
