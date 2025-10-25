# Agent Instructions

This repository is being built by AI agents. Follow these guidelines:

## Architecture

**Frontend**: React + TypeScript + Tailwind CSS + Vite + React Query + Leaflet + Chart.js + PWA
**Backend**: Node.js + Express + PostgreSQL + Redis + Bull Queue
**Database**: PostgreSQL (Railway)

## Project Structure

```
/
├── frontend/       # React + TypeScript + Tailwind CSS + Vite + React Query + Leaflet + Chart.js + PWA
├── backend/        # Node.js + Express + PostgreSQL + Redis + Bull Queue
├── README.md       # Project documentation
└── AGENTS.md       # This file
```

## Development Guidelines

### Code Quality
- Write clean, idiomatic code for the chosen language
- Include TypeScript types (if applicable)
- Add error handling for all operations
- Write comments for complex logic
- Follow best practices for the framework

### Testing
- Write unit tests for business logic
- Write integration tests for API endpoints
- Ensure all tests pass before merging
- Test error scenarios

### Git Workflow
1. Create feature branch: `feature/feature-name`
2. Implement feature with tests
3. Commit with clear messages
4. Push to branch
5. AI will test and merge to main

### API Guidelines
- RESTful endpoints
- Proper HTTP status codes
- JSON responses
- Error responses with helpful messages
- Input validation

### Database
- Use migrations for schema changes
- Index frequently queried fields
- Use foreign keys for relationships
- Validate data before saving

## Vision

Progressive Web App with real-time weather visualization, interactive maps, customizable alerts, and data-rich dashboards for current conditions, forecasts, and historical trends

API aggregation layer that fetches weather data from multiple providers, handles geocoding, manages user preferences and saved locations, implements caching strategies for rate limit optimization, and provides webhook support for real-time alert notifications

## Requirements

- User authentication required
- Multi-user support required

- External APIs: OpenWeatherMap API, WeatherAPI.com, National Weather Service API, Google Maps Geocoding API, Mapbox Geocoding API, AirVisual API

## Deployment

This project will be automatically deployed to Railway when merged to main.

---

*This file is used by AI agents to understand the project architecture and coding standards.*
