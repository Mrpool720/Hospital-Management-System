# Hospital-Management-System
The System Consists of the following Java Classes: <br>
1. HOSPITALMANAGENMENTSYSTEM: This is the main class that interacts with the user through the console. It provides options to add patients, view doctors, and book appointments.
2. PATIENT: Manages operations related to patients such as adding a new patient and viewing existing patients.
3. DOCTOR: Manage operations related to doctors such as viewing available doctors.<br>

JDBC Connection
The System establishes a JDBC connection to MySQL database using the following parameters:<br>
-> URL: `jdbc:mysql://localhost:3306/hospital`<br>
-> Username: `root`<br>
-> Password: `root`<br>
Note: Ensure that the MySQL JDBC driver(`mysql-connector-j`) is available in your projects's classpath.<br>

Usage:
1. Adding a Patient:
     * Choose option "1" from the main menu.
     * Enter patient details when prompted(name, age, gender).
2. Viewing Patient:
     * Choose option "2" from the main menu.
     * Displays a list of all patients stored in the database.
3. Viewing Doctors:
     * Choose option "3" from the main menu.
     * Displays a list of all doctors and their specializations.
4. Booking an Appointment:
     * Choose option "4" from the main menu.
     * Enter patient ID, doctor ID, and appointment date to book an appointment.
     * Check if the doctor is available on the specified date before booking.
5. Exist the system:
   * Choose the option "5" to exit the system.
<br>
Error Handling:<br>
-> Exceptions related to database connectivity, SQL, queries, and user input are handled using try-catch blocks.<br>
-> Proper error messages are displayed to guide the user in case of failure.
