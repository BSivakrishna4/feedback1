# College Feedback System

A React-based feedback system for college courses and faculty evaluation using localStorage for data persistence.

## Features

### Student Features
- **User Registration & Login**: Simple authentication system with localStorage
- **Submit Feedback**: Rate courses and faculty with comments
- **Feedback History**: View all previously submitted feedback
- **Responsive Design**: Works on desktop and mobile devices

### Admin Features
- **Admin Dashboard**: Comprehensive overview of all feedback
- **Statistics**: View total feedback count, average ratings, and course statistics
- **Filter & Search**: Filter feedback by course and rating
- **Course Analytics**: Individual course performance metrics

## Admin Access
- **Email**: admin@college.edu
- **Password**: admin123

## Available Courses
- AI Basics
- Machine Learning
- Deep Learning
- Data Science
- Web Development
- Database Management

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd feedback-system
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
src/
├── App.jsx              # Main app component with routing
├── LoginPage.jsx        # Login and registration page
├── HomePage.jsx         # Student dashboard and feedback form
├── AdminDashboard.jsx   # Admin panel for viewing all feedback
├── sampleData.js        # Sample data initialization
├── userManager.js       # User management utilities
├── main.jsx            # App entry point
├── LoginPage.css       # Login page styles
├── HomePage.css        # Home page styles
├── AdminDashboard.css  # Admin dashboard styles
└── index.css           # Global styles
```

## Technologies Used

- **React 19**: Frontend framework
- **React Router DOM**: Client-side routing
- **Vite**: Build tool and development server
- **CSS3**: Styling with responsive design
- **LocalStorage**: Data persistence (no backend required)

## How to Use

1. **Access the application** at `http://localhost:5173/`
2. **Create an account** by clicking "Sign up here"
3. **Login** with your credentials or use admin account
4. **Submit feedback** for courses and faculty
5. **View feedback history** in the "My Feedback" tab
6. **Admin users** can view all feedback and statistics

## Features in Detail

### Authentication System
- User registration with validation
- Simple login system
- Admin role management
- Session persistence with localStorage

### Feedback Management
- Course and faculty rating (1-5 stars)
- Optional comments (up to 500 characters)
- Feedback history tracking
- Real-time feedback summary

### Admin Analytics
- Total feedback statistics
- Average ratings per course
- Filtering by course and rating
- Comprehensive feedback overview

## Data Storage

The application uses localStorage for data persistence:
- `users`: Registered user accounts
- `loggedInUser`: Current session user
- `feedbackData`: All submitted feedback
- `sampleDataInitialized`: Flag for sample data

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Adding New Features

1. **New Courses**: Update the `courses` array in `HomePage.jsx` and `AdminDashboard.jsx`
2. **Additional Fields**: Modify the feedback form and data structure
3. **New User Roles**: Extend the authentication system in `LoginPage.jsx`

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is licensed under the MIT License.