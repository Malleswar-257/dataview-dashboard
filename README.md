# dataview-dashboard

An analytics platform for displaying KPIs, visual reports, and interactive charts.

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: FastAPI + SQLAlchemy
- **Design**: Figma ([View Design](https://www.figma.com/design/fzvMscSRhEdiO9Cqj77mcv/30--Chart-UI-Components-%7C-BRIX-Templates--Community-?node-id=15-4&t=r0tdqiHATOC6zXDN-1))

## Project Structure

```
dataview-dashboard/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- KPI and report visualization
- Interactive charts and reports
- Customizable dashboard
- User management and permissions
- Data export and import

## API Endpoints

- `POST /api/login` - Login endpoint for users to authenticate with the platform.
- `GET /api/dashboard` - Endpoint to retrieve the user's personalized dashboard.
- `GET /api/reports` - Endpoint to retrieve a list of available reports.
- `GET /api/reports/{report_id}` - Endpoint to retrieve a specific report by ID.
- `POST /api/widgets` - Endpoint to add a new widget to the user's dashboard.

## License

MIT
