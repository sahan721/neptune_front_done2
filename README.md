# Neptune — Collection Management System

A full-stack collection management system designed to support administrative operations, collection workflows, reporting, and role-based access.

The project consists of a React frontend and a separate TypeScript backend connected to a PostgreSQL database.

## Live Demo

**Frontend:** [Open Neptune](https://neptunefrontdone2.vercel.app)

## Related Repository

- **Frontend:** [neptune_front_done2](https://github.com/sahan721/neptune_front_done2)
- **Backend:** [neptune-backend](https://github.com/sahan721/neptune-backend)

## Key Features

- **Administrative dashboard** — Monitoring and operational insights.
- **User authentication** — Sign-in and access management.
- **Role-based access** — Access controls for different user roles.
- **Collection management** — Manage collection requests and assignments.
- **Record management** — Work with vehicle, collector, and rider records.
- **Reporting** — Access administrative reports.
- **Notifications** — Toast notifications and web push notification support.

*Feature availability depends on the implemented and configured application modules.*

## Technology Stack

### Frontend

- React
- TypeScript
- Vite
- React Router
- Lucide React

### Backend

- Node.js
- TypeScript
- PostgreSQL
- Prisma ORM

## Architecture

Neptune separates its user interface from its backend services.

1. The React frontend provides the administrative interface.
2. The frontend communicates with backend APIs.
3. The backend handles application workflows, authentication, authorization, and data operations.
4. PostgreSQL stores application data through Prisma.
5. Notification services support relevant user alerts.

## Running the Frontend Locally

### Prerequisites

- Node.js and npm
- Access to a configured Neptune backend

### Installation

```bash
git clone https://github.com/sahan721/neptune_front_done2.git
cd neptune_front_done2
npm install
```

### Environment Configuration

Configure the backend API URL using the environment variable expected by the application. Check the existing environment configuration and API client before setting the variable name.

Do not commit secrets or private credentials.

### Start the Development Server

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Type Checking

```bash
npm run typecheck
```

## Project Structure

The frontend is organized around application routing, pages, shared services, authentication, and API communication. Refer to the source directory for the current implementation.

## Future Improvements

- Expand automated testing.
- Improve technical documentation.
- Strengthen accessibility and responsive design.
- Document deployment and environment configuration.

## Author

**Sahan Nimnaka**

[GitHub Profile](https://github.com/sahan721)

---

This repository contains the frontend component of Neptune. Refer to the related backend repository for server-side implementation details.
