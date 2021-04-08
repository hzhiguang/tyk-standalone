# Tyk Standalone Gateway

## Pre-requisite - Redis
Host | Port
--- | ---
tyk-redis | 6379

## Mount Points
Mount Points | Description
--- | ---
/opt/tyk-gateway/tyk.conf | Tyk Configuration
/opt/tyk-gateway/apps | Tyk Application Directory
/opt/tyk-gateway/middleware | Tyk Middleware Directory
/opt/tyk-gateway/certs | Tyk Certification Directory

## Exposed Ports
Port | Description
--- | ---
8080 | Default HTTP Port