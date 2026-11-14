# Grant Matching Agent — Frontend

A web application developed as part of our capstone project at **Oregon State University** to help researchers discover relevant funding opportunities, explore faculty expertise, and find potential collaborators.

The application makes it easier for researchers to find grants that align with their work and build teams for collaborative proposals. This repository contains the React frontend, while the AI matching and data processing are handled by the backend.

**Backend:** [Grant Matching Agent](https://github.com/parnashri/GrantMatchingAgent)

## Features

- **Login and Signup:** User authentication with protected navigation.
- **Faculty Profiles:** View and update research profiles.
- **Grant Discovery:** Explore funding opportunities matched to faculty research interests.
- **Team Building:** Find collaborators, form research teams, and discover grants suited to a team.
- **AI-Assisted Workflows:** Chat-based interactions and streamed responses from the backend.
- **Role-Based UI:** Different profile and navigation options based on user permissions.

## Tech Stack

- React and TypeScript
- Vite
- Tailwind CSS
- React Router
- REST API integration

## Getting Started

Clone the repository:

```bash
git clone https://github.com/parnashri/GrantMatchingAgent-Frontend.git
cd GrantMatchingAgent-Frontend
```

Install dependencies:

```bash
npm ci
```

Start the development server:

```bash
npm run dev
```

Open `http://localhost:5173` or the URL displayed in your terminal.

**Note:** The frontend requires a compatible backend. Update the API proxy configuration in `vite.config.ts` to point to your backend server. Some application features require additional authentication, faculty, and team endpoints.
