# docconnect
Create a medical clinic website for efficient appointment scheduling, time management, and patient care. Streamline the process, manage doctor schedules, and allow patients to view and manage their appointments. Cost-effective and user-friendly solution for the clinic and patients.
Functional Requirements
Patients can register / log in to the web application and can:

Book an appointment/doctor consultation online.
Video consultation with Doctors.
Hassle-free payments for the booked services.
Doctors can log in to the web application and can:

Accept appointments
View Appointments
The system should be giving minimal and relevant data only to the users

Use Case Flow
1. Register User
Preconditions: None
Main flow:
The use case starts when a user indicates that he wants to register.
The system requests a name, email, phone, and password.
The user enters a name, email, phone, and password.
On user click/enter action, the server checks if this user is already registered.
If yes, an error message is thrown.
If no,then the user is registered successfully and the system starts a login session and displays the welcome page.
Alternative Flows:
If the email already exists, then the system displays a message and the use case goes back to step 2.
If the user does not enter a required field, a message is displayed and the use case repeats step 3.
2. Login User
Preconditions: The user is registered.
Main flow:
The use case starts when a user indicates that he wants to login.
The system requests the email and password.
The user enters email and password.
The system verifies the id, email and password against all registered users.
The system starts a login session.
Alternative Flows
If the username is invalid, the use case goes back to step 2.
If the password is invalid the system requests that the user re-enter the password. When the user enters another password the use case continues with step 4 using the original username and new password.
3. Search Appointments and Consultations
Preconditions: The user needs to be registered and Logged In.
Main Flow:
User heads to the home page where he can search for Booking Physical Appointments or Online Chat and Video Consultations under two different tabs.
The User is First prompted to enter his Location (City).
The search can be executed by clicking on common predefined Symptoms for Consultations and Specialities for Bookings or can search for Clinics / Doctors / Symptoms / Specialities through the search bar.
A list of most relevant responses is Outputted which the user can click and book appointments, consultations.
4 Book Appointment
Preconditions: The user needs to be registered, Logged in and the User should have provided the Location in the initial prompt.

Main Flow:

The user has two choices for which kind of appointment he wants.
The user either clicks ‘Consult Doctors’ or ‘Book appointment’
The user is then redirected to the ‘consult doctors’ page.
Users are asked to enter the date and time of appointment.
Users are then prompted to the payment gateway for successful completion of the booking.
Now the user has successfully booked the appointment.
