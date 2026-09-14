# Logging and Telemetry

This directory will contain the centralized logging-server configuration and deployment assets.

## Initial scope

- Docker or Portainer-managed deployment
- Candidate stack evaluation: Wazuh, Elastic/ELK, Zabbix, or a combination where justified
- Target, attacker, defender, network, and host telemetry ingestion
- Time synchronization and experiment correlation
- Retention and storage sizing

## Planned structure

```text
logging/
├── docker/
├── portainer/
├── wazuh/
├── elastic/
└── configs/
```

Do not commit raw logs, packet captures, secrets, or credentials. Store reproducible configuration and sanitized examples instead.
