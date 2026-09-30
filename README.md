# VeriFund Backend

Squad Hackathon backend for cooperative transparency, contribution collection, and controlled withdrawals. Microservices architecture with Docker.

## Architecture

- **api-gateway** - API routing and authentication
- **member-service** - Member registration and management
- **cooperative-service** - Cooperative creation and management
- **contribution-service** - Contribution collection
- **withdrawal-service** - Controlled withdrawal processing
- **notification-service** - Notifications
- **ai-service** - AI/ML integration
- **frontend** - Web frontend

## Tech Stack

- Python (FastAPI)
- Docker + Docker Compose
- PostgreSQL
- Railway/Render deployment

## Getting Started

```bash
docker-compose up --build
```

See [AI_INTEGRATION_AND_HOSTING.md](AI_INTEGRATION_AND_HOSTING.md) and [FRONTEND_ROUTES.md](FRONTEND_ROUTES.md) for details.

## Environment Variables

See [.env.example](.env.example).