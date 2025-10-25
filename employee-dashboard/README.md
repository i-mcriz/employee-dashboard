# Employee Dashboard

A React-based Employee Management Dashboard application with employee listing and form functionality.

## Features

- **Navbar**: Navigation bar with links to Home and Employee Form pages
- **Home/Dashboard**: Displays employee data fetched from an external API in a table format
- **Employee Form**: Form to add new employee details with validation
- **Responsive Design**: Mobile-friendly interface using Bootstrap
- **Routing**: Seamless navigation between pages using React Router

## Technologies Used

- **React**: Frontend library for building user interfaces
- **React Router DOM**: For client-side routing
- **Bootstrap**: CSS framework for responsive design
- **Vite**: Fast build tool and development server
- **Fetch API**: For making HTTP requests to external API

## API Integration

The application fetches employee data from:
```
https://jsonplaceholder.typicode.com/users
```

Displays the following fields:
- ID
- Name
- Email

## Employee Form Fields

The form includes the following fields with validation:
- **Name** (Required)
- **Designation** (Required)
- **Location** (Required)
- **Salary** (Required, must be a valid number)

## Project Structure

```
employee-dashboard/
├── src/
│   ├── components/
│   │   └── Navbar.jsx          # Navigation component
│   ├── pages/
│   │   ├── Home.jsx            # Dashboard/Home page
│   │   └── EmployeeForm.jsx    # Employee form page
│   ├── App.jsx                 # Main app with routing
│   ├── App.css                 # App-specific styles
│   └── index.css               # Global styles
├── package.json
└── README.md
```

## Installation

1. Navigate to the project directory:
```bash
cd employee-dashboard
```

2. Install dependencies:
```bash
npm install
```

## Running the Application

Start the development server:
```bash
npm run dev
```

The application will open at `http://localhost:5173/`

## Available Routes

- `/` - Home/Dashboard page (displays employee list)
- `/employee-form` - Employee Form page

## Features Implemented

✅ Navbar with Home and Employee Form links
✅ Home page displaying data from external API
✅ Table view with ID, Name, and Email fields
✅ Employee form with Name, Designation, Location, and Salary
✅ React Router for navigation
✅ Bootstrap for styling
✅ Form validation
✅ Loading states and error handling
✅ Responsive design
✅ No data posting (as per requirements)

## Notes

- The form does not post data to any backend as per requirements
- Form submission displays a success message and resets after 3 seconds
- The application includes error handling for API failures
- Bootstrap is used for consistent and professional styling

