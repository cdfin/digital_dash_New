# Digital Dash

## Project Summary
Digital Dash is a React-based dashboard application designed to display various metrics and data visualizations. The project uses Material-UI for styling, Redux for state management, and Recharts for data visualization.

Key Features Implemented:

Basic project structure and routing
Theme setup using Material-UI
Redux integration for state management
KPI cards displaying key metrics
Line chart showing revenue trend
Bar chart displaying category distribution
Interactive buttons to update data in real-time
User Authentication (Login/Register)
Email Verification
Password Reset Functionality
Protected Routes
Dashboard with KPI Cards
Data Visualization (Line and Bar Charts)
Real-time Data Updates
Error Handling and Loading States


Project Structure
Copysrc/
├── components/
│   ├── Analytics/
│   │   └── AnalyticsPage.js
│   ├── Auth/
│   │   ├── EmailVerification.js
│   │   ├── ForgotPassword.js
│   │   ├── Login.js
│   │   ├── ProtectedRoute.js
│   │   ├── Register.js 
│   │   └── ResetPassword.js 
│   ├── Dashboard/
│   │   ├── BarChartCard.js
│   │   ├── ChartCard.js
│   │   ├── DashboardHome.js
│   │   └── KPICard.js
│   ├── Email/
│   │   └── EmailPage.js
│   ├── Layout/
│   │   ├── Header.js
│   │   └── Sidebar.js
│   └── ErrorBoundary.js
├── hooks/
│   └── UseDashboardData.js
├── redux/
│   ├── authSlice.js
│   ├── dashboardSlice.js
│   └── store.js
├── services/
│   ├── authService.js
│   └── api.js
├── styles/
│   └── theme.js
├── App.js
└── index.js


 ## Progress
- [x] Project setup
- [x] Routing implemented
- [x] Redux state management integrated
- [x] Basic dashboard layout created
- [x] KPI cards implemented
- [x] Line chart for revenue trend added
- [x] Bar chart for category distribution added
- [x] Interactive data updates implemented
- [x] API data fetching implemented
- [x] Loading and error states handled
- [x] Error Boundary added for robust error handling
- [x] User authentication implemented   
- [x] Protected routes added
- [x] Email verification implemented
- [x] Password reset functionality added
      
## Next Steps
- [ ] Ehance user profile management
- [ ] Implement role-based access control
- [ ] Implement data fetching from an API
- [ ] Create additional dashboard pages (Analytics, Email)
- [ ] Add more advanced chart types
- [ ] Implement caching strategies
- [ ] Add unit and integration tests
- [ ] Enhance responsive design
- [ ] Implement real-time data updates with websockets

## Setup
1. Clone the repository
2. Run `npm install` to install dependencies
3. Create a `.env` file in the root directory and add your API URL: [REACT_APP_API_URL=https://your-api-url.com]
4. Run `npm start` to start the development server

## Available Scripts
- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production

## Learn More
To learn more about the technologies used in this project, check out the following resources:
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Redux Toolkit Documentation](https://redux-toolkit.js.org/introduction/getting-started)
- [Material-UI Documentation](https://material-ui.com/getting-started/installation/)
- [Recharts Documentation](https://recharts.org/en-US/guide)
