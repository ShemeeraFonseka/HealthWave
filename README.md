

# Health Wave - Healthcare Management System

## Introduction

**Health Wave** is an innovative healthcare management system designed to streamline the management of patient records, doctor appointments, medical histories, prescriptions, and more. The system provides a comprehensive solution for healthcare providers to manage patient data securely and efficiently, while allowing patients to interact with their health information and book appointments with doctors online.

## Features

### For Patients:
- Patient registration and login
- View and update personal information
- View and manage medical history
- Book new appointments with doctors
- View appointment history
- Download medical reports and prescriptions
- View available doctors and their details

### For Doctors:
- Doctor registration and login
- View patient details and medical history
- Manage and update appointments
- Create and manage prescriptions
- View channeled patients
- Manage patient lists

### For Admin:
- Admin login to manage the system
- Manage patient and doctor registrations
- View all patients, doctors, and appointments
- Generate and download reports
- Approve and manage appointments

## Technologies

This project is built using the following technologies:

- **Frontend**: 
  - HTML5, CSS3, JavaScript, React for building the user interface
- **Backend**: 
  - Java, Spring Boot for building the RESTful APIs
- **Database**: 
  - MySQL for data storage and management
- **JPA**: 
  - Java Persistence API for database interaction
- **REST API**: 
  - For secure communication between the frontend and backend

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ShemeeraFonseka/Healthwave.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Healthwave
   ```

3. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

4. Install backend dependencies:

   ```bash
   cd backend
   mvn clean install
   ```

5. Set up the MySQL database:
   - Import the SQL scripts provided in the repository to set up the database.
   - Update the database connection settings in the `application.properties` file under the `backend/src/main/resources` directory.

6. Run the backend server:

   ```bash
   mvn spring-boot:run
   ```

7. Run the frontend development server:

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000` for the frontend and `http://localhost:8080` for the backend.

## Usage

1. **Patient Portal**:
   - Register as a new patient or log in with existing credentials.
   - View personal information and update details.
   - Book an appointment with available doctors.
   - View your appointment history and download medical reports.

2. **Doctor Portal**:
   - Log in with doctor credentials.
   - View and manage patient lists and appointments.
   - Create, view, and update prescriptions for patients.

3. **Admin Portal**:
   - Manage patient and doctor registrations.
   - View all appointments and reports.
   - Approve or reject appointment requests.

## Contributing

If you wish to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-branch
   ```

3. Make your changes.
4. Commit your changes:

   ```bash
   git commit -m 'Add new feature'
   ```

5. Push to the branch:

   ```bash
   git push origin feature-branch
   ```

6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

