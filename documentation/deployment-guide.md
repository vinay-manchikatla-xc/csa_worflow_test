# Deployment Guide

## Prerequisites

- Node.js 18+
- PostgreSQL database
- Redis instance

## Steps

1. Clone the repository
2. Install dependencies: `npm install`
3. Configure environment variables
4. Run migrations
5. Start the application

## Environment Variables

```
DATABASE_URL=postgresql://localhost:5432/csa
REDIS_URL=redis://localhost:6379
GITHUB_WEBHOOK_SECRET=your_secret_here
```
