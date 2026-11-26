# CarCareOps 🚗✨

AI-powered car wash management system with plate recognition and monthly business insights.

## The Problem
Small car wash businesses track bookings on paper, struggle to tell owners when their car is ready, and have no easy way to see how the business is performing.

## Features
- **Two dashboards:** Manager and User
- **Authentication:** team login, plus guest access (guests can erase their data)
- **Car registration:** store car and owner details (phone, email)
- **Daily booking list:** shows only today's cars and resets each day
- **Worker management:** register workers with photo and details, assign one to each car
- **Cleaner updates:** cleaners update a car's status so owners know when to collect it
- **SMS/email notification** when a car is ready
- **Monthly analytics:** charts and statistics

### AI Features
- **Number plate reading:** upload a photo and the car is identified or pre-registered automatically (the cleaner confirms before saving)
- **Monthly insights:** the backend calculates the numbers, and AI writes a short summary with suggestions

## Tech Stack
| Layer | Technology |
|-------|------------|
| Frontend | React |
| Backend | Python, FastAPI |
| Database | PostgreSQL |
| AI | Claude API (vision + text) |
| Auth | JWT |

## Database Tables (planned)
| Table | Purpose |
|-------|---------|
| users | Login accounts and roles (manager, cleaner, guest) |
| owners | Car owners' contact details |
| cars | Plate number, make, model, colour, owner |
| workers | Staff details and photo |
| bookings | Car, assigned worker, status, service, date |
| insights | Saved monthly AI summaries |

## Project Structure
- `backend/` – FastAPI API and AI logic
- `frontend/` – React app

## Status
🚧 In development. React prototype exists; Python backend in progress.

## Roadmap
- [ ] Database design and setup
- [ ] Authentication and roles
- [ ] Car, owner and worker endpoints
- [ ] Bookings and status updates
- [ ] Connect React frontend to API
- [ ] Number plate reading
- [ ] Monthly analytics and AI insights
- [ ] Deploy

## Author
Sphesihle Mdlalose ([@madlula03](https://github.com/madlula03))