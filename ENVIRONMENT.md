# Environment Configuration

This document lists environment variables used by the project.

## Local Environment Files

Recommended:

- `.env.example` - committed template with placeholder values
- `.env.local` - local overrides (not committed)

## Required Variables

Add final keys here once application services are defined.

| Variable | Required | Example | Description |
| --- | --- | --- | --- |
| `APP_ENV` | Yes | `development` | Runtime environment |
| `APP_PORT` | Yes | `3000` | Local server port |
| `API_BASE_URL` | Yes | `http://localhost:8080` | Backend API base URL |

## Security Notes

- Never commit real secrets.
- Use secret management for CI/CD and production.
- Rotate compromised tokens immediately.

## Per-Environment Guidance

- `development`: local debug values
- `staging`: integration testing endpoints
- `production`: managed secrets only
