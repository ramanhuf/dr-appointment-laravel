# Doctor Appointment Management System

This project is a Doctor Appointment Management System refactored to use the Laravel framework. The original project was developed by [PHPGurukul](https://phpgurukul.com/) and can be found [here](https://phpgurukul.com/doctor-appointment-management-system-using-php-and-mysql/).

## Project Description

The Doctor Appointment Management System is a web application that allows patients to book appointments with doctors. It also enables doctors to manage their appointments and schedules efficiently. The main objective of the “Doctor Appointment Management System” project is to provide easier doctor appointment and gets appointment online which save lots of time. The original project was built using native PHP and MySQL.

## Features

- **User Module:**
  - Home Page: In this section, user can view the welcome page of the web application.
  - Book: In this section, user can sent the appointment request.
  - Check Appointment: In this section, user can search appointment with the help of user appointment number/Name/Mobile Number

- **Doctor Module:**
  - Dashboard:  In this section, the doctor can briefly view the total number of new appointment, total approved appointment,s and total canceled appointments.
  - Appointment: In this section, the doctor views the appointment details and they have also the right to change application status according to the current status.
  - Reports: In this section doctor can view the appointment details in a particular period.
  - Search: In this section, doctor can search appointments with the help of user appointment number/Name/Mobile Number
  Doctor can also update his profile, change the password and recover the password.

## Refactoring to Laravel

The project has been refactored to follow the Laravel framework structure. The refactored structure separates the code into:

- **Models:** Handling data and database interactions.
- **Views:** Managing the presentation layer using Blade templates.
- **Controllers:** Handling the application logic and user input.
- **Migrations:** Handling database schema.
- **Routes:** Defining the application routes.

## Getting Started

### Prerequisites

- XAMPP or any compatible local server environment.
- Composer (Dependency Manager for PHP).
- Web browser.
- Basic knowledge of PHP and Laravel.

### Installation

1. **Clone the Repository:**

   - Clone this repository to your local machine or download the ZIP file and extract it.

     ```bash
     git clone git@github.com:khalidalghifari/Kelompok_2_4_Laravel.git
     ```
   
2. **Install Composer Dependencies:**

   ```bash
   composer install
   ```

3. **Generate Application Key:**
 
   ```bash
   php artisan key:generate
   ```

4. **Run Migrations**
   
   ```bash
   php artisan migrate --seed
   ```

### Running the Projects

1. **Open terminal and run this following command:**
   
   ```bash
   php artisan serve
   ```

2. **Open the Application in Your Browser:**
  - Navigate to `http://localhost:8000`.


## Project Structure

### Laravel Structure

The project follows the Laravel framework structure with the following directories:

- `app/Models`: Contains all the model classes for database interaction.
- `resources/views`: Contains all the view files for rendering the user interface.
- `app/Http/Controllers`: Contains all the controller classes for handling the logic and user input.
- `database/migrations`: Contains all the migration files for creating database schemas.
- `routes`: Contains all the application routes.
- `public`: Contains publicly accessible files such as index.php and assets (CSS, JS, images).
