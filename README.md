# Eduverse Academy

Eduverse Academy is built with React.js for the frontend, Spring Boot for the backend, and MySQL as the database. It provides a comprehensive platform for managing online courses, user profiles, assessments, progress tracking, and more.

## Group No: 10

---

## Features

### User Management
- User registration and login functionality.
- User profiles with the ability to update information.

### Course Management
- Admin can add, edit, and manage courses.
- Course details include name, instructor, description, etc.

### Assessment
- Users can take assessments related to courses.
- Admin can create and manage assessment questions.

### Progress Tracking
- Monitor user progress and completion status.
- Visual representation of progress for users.

### Certificate Generation
- Automatic certificate generation upon course completion.
- Personalized certificates with user details.

### Discussion Forum
- Course-specific discussion forums for users.
- Interaction between users and instructors.

### Admin Dashboard
- For course addition and assessment question addition.
- Tracking of students, courses, and enrollments.

---

## Technologies Used

### Frontend
- React.js
- Styled with CSS

### Backend
- Spring Boot
- RESTful API architecture

### Database
- MySQL  
  - Tables: `course`, `learning`, `progress`, `discussion`, `feedback`, `question`, `user`, `assessment`

---

## Setup Instructions

### Clone the Repository
```bash
# Step 1: Clone the repository
git clone https://github.com/akxat26/LEARNING_MANAGEMNT_SYSTEM.git

# Step 2: Navigate into the project folder
cd Learning-Management-System
```

---

### Backend Setup (Spring Boot)
```bash
# Step 3: Navigate to the backend folder
cd backend

# Step 4: Import the project in your preferred IDE (IntelliJ, Eclipse, etc.)

# Step 5: Configure application.properties (see below)

# Step 6: Run the application
# Option 1: Using IDE (Run the main class)
# Option 2: Using terminal
./mvnw spring-boot:run
```

#### application.properties
```properties
# Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/lms
spring.datasource.username=root
spring.datasource.password=1812
spring.jpa.hibernate.ddl-auto=update

# Server Port
server.port=8080
```

---

### Frontend Setup (React)
```bash
# Step 7: Navigate to the frontend folder
cd ../frontend

# Step 8: Install dependencies
npm install
# or
yarn install

# Step 9: Create a .env file (see structure below)

# Step 10: Start the frontend
npm start
# or
yarn start
```

#### .env File Structure
```env
REACT_APP_API_BASE_URL=http://localhost:8080
```

---

### Optional: Database Credentials (if used separately)
```env
DB_URL=jdbc:mysql://localhost:3306/lms
DB_USERNAME=root
DB_PASSWORD=1812
```

---

## You're all set!
The frontend will be available at `http://localhost:3000` and will communicate with the backend on `http://localhost:8080`.

---
