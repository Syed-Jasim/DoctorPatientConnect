
# Doctor-Patient Connect

**Doctor-Patient Connect** is a web-based application that allows patients to book appointments with doctors and enables doctors to manage patient records and prescriptions. This project was developed as part of my learning journey in full-stack development.

## Features

- **Patient Features:**
  - Patient login and registration.
  - View available doctors and book appointments.
  - View appointment history.
  
- **Doctor Features:**
  - Doctor login and registration.
  - View patient details and appointment history.
  - Provide prescriptions to patients.

## Technologies Used

- **Java**: Used for the backend logic and business operations.
- **MySQL**: Used to store patient and doctor information, appointments, and prescriptions.
- **JSP (JavaServer Pages)**: Used for creating dynamic web pages that interact with the user.
- **Servlets**: Used to manage HTTP requests and responses for the application.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/Doctor-Patient-Connect.git
   ```

2. **Set up the MySQL database**:
   - Create a MySQL database and import the provided SQL schema file (`database.sql`) to create necessary tables.

3. **Configure the application**:
   - Set up your MySQL credentials in the project (in the `web.xml` file or database connection class).

4. **Run the application**:
   - Deploy the project on a servlet container like Apache Tomcat.
   - Open a browser and go to `http://localhost:8080/Doctor-Patient-Connect`.

## How It Works

1. **Patient Registration & Login**: Patients can create an account and log in to book appointments with available doctors.
2. **Doctor Registration & Login**: Doctors can create an account, log in, and view their patients' appointments and provide prescriptions.
3. **Appointment Booking**: Patients can select a doctor, view available time slots, and book an appointment.
4. **Prescription Management**: Doctors can access patient details and issue prescriptions.

## Contributing

Feel free to fork this repository, make improvements, and submit a pull request. Contributions are welcome!
                                                                                                                
  **-Syed Mahammad Jasim**
