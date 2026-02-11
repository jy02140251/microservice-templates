# Microservice Templates

Templates for building microservices.

## Architecture Patterns

### API Gateway
Central entry point for all clients.

### Service Mesh
Sidecar proxy for service communication.

### Event-Driven
Async communication via message queues.

## Service Template

Each service should have:

- /src - Source code
- /tests - Unit and integration tests
- /docs - API documentation
- Dockerfile - Container build
- docker-compose.yml - Local dev
- README.md - Service docs

## Communication

### Sync
- REST API
- gRPC

### Async
- RabbitMQ
- Apache Kafka
- Redis Pub/Sub

## Deployment

- Kubernetes recommended
- Use Helm charts
- GitOps with ArgoCD