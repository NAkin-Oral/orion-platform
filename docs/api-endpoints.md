# Orion Platform API Documentation

## Base URL
https://api.orion.novatech.com/v1

## Endpoints

### GET /health
Returns service health status.
Response: { status: 'ok', version: '1.0.0'}

### POST /auth/login
Authenticates user.
Body: { username: string, password: string }
Response: { token: string, expires_in: 3600 }
