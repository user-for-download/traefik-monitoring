# traefik-monitoring
- image: traefik:v2.8.0
- image: portainer/portainer-ce:2.14.0
- image: prom/prometheus:v2.36.2
- image: prom/node-exporter:v1.3.1
- image: prom/pushgateway:v1.4.3
- image: gcr.io/cadvisor/cadvisor:v0.44.0
- image: grafana/grafana:9.0.2

source:
- https://github.com/traefik/traefik
- https://github.com/portainer/portainer
- https://github.com/grafana/grafana
- https://github.com/prometheus/prometheus

config:
- https://github.com/stefanprodan/dockprom
- https://github.com/abmruman/traefik-docker-compose
