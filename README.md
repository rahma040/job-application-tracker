job Application Tracker
A modern Angular application for managing job applications with calendar integration and reactive state management.
Dashboard
<img width="1850" height="982" alt="Capture d&#39;écran 2026-01-14 141917" src="https://github.com/user-attachments/assets/3ad0c92c-438b-4891-a369-f819469df88c" />
Applications List
<img width="1847" height="482" alt="Capture d&#39;écran 2026-01-14 141933" src="https://github.com/user-attachments/assets/d02e0863-f1b7-4827-9eff-ae0b5ba56847" />
<img width="1839" height="980" alt="Capture d&#39;écran 2026-01-14 142018" src="https://github.com/user-attachments/assets/c14f12dc-6c9c-4a0d-bff7-9cd7832e8cff" />
calendar
<img width="1811" height="986" alt="Capture d&#39;écran 2026-01-14 141957" src="https://github.com/user-attachments/assets/d0c8bde7-34d6-4716-88a3-1df4e213df3e" />






Features

Dashboard with real-time statistics showing total applications, status breakdown, and upcoming interviews
Complete CRUD operations for managing job applications
Calendar view displaying interview dates and deadlines
Automatic data persistence using LocalStorage
Reactive state management powered by RxJS BehaviorSubject
Clean, modern Material Design interface with gradient cards and smooth animations

Technologies Used

Angular 20 with Standalone Components architecture
Angular Material for UI components
RxJS for reactive state management
FullCalendar library for calendar visualization
TypeScript for type safety and better development experience
LocalStorage API for client-side data persistence

installation and Setup

# Clone the repository
git clone https://github.com/rahma040/job-application-tracker.git

# Navigate to project directory
cd job-application-tracker

# Install dependencies
npm install

# Start development server
ng serve
```

Open your browser and navigate to `http://localhost:4200`

## Project Structure
```
src/app/
├── models/
│   └── job-application.ts          # TypeScript interfaces and types
├── services/
│   └── job-application.service.ts  # State management and business logic
├── components/
│   ├── dashboard/                  # Dashboard with statistics
│   ├── job-list/                   # List view with CRUD operations
│   ├── job-form/                   # Add/Edit form
│   └── calendar-view/              # Calendar integration
└── app.routes.ts                   # Application routing
