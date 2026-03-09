# Dive App Backend

Backend API server for the Seafolio Dive App

## Project Description

This backend provides REST API endpoints for the Dive App frontend, handling:
- User authentication (via Supabase Auth)
- Database operations for dive sites, trips, and user data
- Business logic and data validation

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** Supabase (PostgreSQL)
- **Authentication:** Supabase Auth
- **Language:** TypeScript

## Setup Instructions

### Prerequisites

- Node.js 18+ installed
- npm or yarn
- Supabase account and project

### Installation

1. Clone the repository:
```bash
git clone https://github.com/l3blonde/dive-app-backend.git
cd dive-app-backend
```

2. Install dependencies:
```bash
npm install
```

3. Create environment file:
```bash
cp .env.example .env
```

4. Configure environment variables in `.env`:
```
PORT=3001
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
```

5. Start development server:
```bash
npm run dev
```

## Git Workflow

### Branches
- `main` - Production-ready code
- `staging` - Pre-production testing
- `develop` - Active development

### Feature Development
```bash
git checkout develop
git pull origin develop
git checkout -b feature/your-feature-name
# Make changes
git add .
git commit -m "feat: description of changes"
git push origin feature/your-feature-name
# Create pull request to develop
```

## Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run linter
```

## Status

**In Development** - Basic structure set up, endpoints to be implemented.
