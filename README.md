# Employee Management System

The Employee Management System is a comprehensive solution designed to streamline and enhance human resource operations within organizations. This system offers a user-friendly interface that facilitates efficient management of employee profiles, tracking of leave and attendance, task assignment, and performance evaluations. By centralizing these essential HR functions, the system empowers administrators to optimize workforce management, boost productivity, and ensure accurate data-driven decision-making.


## Technologies Used

The following technologies have been used in the development of Employee Management System (HRMS):

- **[Laravel](https://laravel.com/)** : A popular PHP web application framework known for its elegant syntax and feature-rich ecosystem.
- **[Laravel Blade](https://laravel.com/)** : The templating engine provided by Laravel for designing and rendering views.
- **MySQL** : The database management system used to store application data.
- **[Bootstrap](https://getbootstrap.com/)** : A CSS framework for creating responsive and attractive UI components.
- **[FontAwesome](https://fontawesome.com/)**: A popular icon library that provides a wide range of icons for web projects.


## Usage

01. Log in to access the admin dashboard.
02. Add employees and provide necessary details.
03. Manage leave requests, assign tasks, and perform other administrative functions.
04. Employees can log in to view their profiles, submit leave requests, and update task statuses.


## Features

##### **01. User Authentication**
Securely manage user access with a robust authentication system. Different user roles (admin, manager, hr etc) ensure appropriate permissions and access levels.

##### **02. Dashboard**
Upon logging in as an administrator, you will be welcomed to the Admin Dashboard. The dashboard provides an insightful overview of vital statistics, including the total count of employees, ongoing projects, and recent activities. This central hub offers swift access to critical sections of the Employee Management System, empowering you to efficiently oversee employee profiles, leave requests, task assignments, and more.

##### **03. Employee Profiles** 
Maintain detailed profiles for each employee, including personal information, contact details, job history, and more.

##### **04. Leave and Attendance**
Easily manage employee attendance and leave requests, allowing for accurate tracking and efficient planning.

##### **05. Performance Evaluation**
Conduct performance reviews and evaluations within the system, facilitating timely feedback and goal setting.

##### **06. Task Assignment**
Assign tasks and projects to employees, set deadlines, and track progress, enhancing collaboration and productivity.

##### **07. Payroll Management**
Streamline payroll processing by automating salary calculations, tax deductions, and generating paystubs.

##### **08. Reports and Analytics**
Generate insightful reports and analytics on various aspects of employee management, aiding data-driven decision-making.


## Getting Started

Follow these instructions to get a copy of the Employee Management System project up and running on your local machine for development and testing purposes.

#### Prerequisites

Before you proceed, ensure you have the following software installed:

- PHP (Version 8.2)
- Composer (Version 2.5)
- MySQL (Version 8.2)
- Laravel (Version 10.16)


#### Installation

01. Clone the **Employee Management System** repository to your local machine using the following command:
```bash
git clone https://github.com/MOHONA678/employee-management-system.git
```

02. Navigate to the project directory:
```bash
cd employee-management-system
```

03. Install the required `PHP` dependencies using Composer:
```bash
composer install
```

04. Install `Node.js` dependencies
###### Using npm:
```bash
npm install
```
or,
###### using Yarn:
```bash
yarn
```

05. Generate `Vite` serve manifest:
###### Using npm:
```bash
npm run build
```
or,
###### using Yarn:
```bash
yarn build
```

06. Create a new MySQL database for Employee Management System and update the `.env` file with your database credentials:
```bash
cp .env.example .env
```

07. Generate a unique application key:
```bash
php artisan key:generate
```

08. Run the database migrations and seed the database with initial data:
```bash
php artisan migrate --seed
```

09. Start the development server:
```bash
php artisan serve
```

Congratulations! Employee Management System should now be up and running at `http://localhost:8000`.
