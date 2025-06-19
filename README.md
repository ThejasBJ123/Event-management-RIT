# Event Management System (RIT)

An event management system designed for RIT (Rajiv Gandhi Institute of Technology) to streamline event coordination and management.

## Features

- Event Registration and Management
- Staff and Student Coordination
- User Authentication System
- Event Viewing and Updates
- Contact and About Us Pages

## Tech Stack

- Backend: PHP
- Database: MySQL
- Frontend: HTML, CSS

## Setup Instructions

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Database Setup:
   - Create a MySQL database
   - Import the database schema from `cems.sql`

3. Web Server Configuration:
   - Place the project files in your web server directory
   - Ensure PHP is properly configured
   - Update database connection settings in your PHP files

## Directory Structure

```
├── classes/          # PHP class files
├── css/             # Stylesheets
├── fonts/           # Font files
├── images/          # Image assets
├── utils/           # Utility files
├── *.php            # Main PHP files
└── cems.sql         # Database schema
```

## Key Files

- `index.php` - Main landing page
- `login_form.php` - User authentication
- `register.php` - User registration
- `createEventForm.php` - Event creation
- `events.php` - Event listing
- `adminPage.php` - Admin dashboard
- `Staff_cordinator.php` - Staff coordination
- `Stu_cordinator.php` - Student coordination

## Usage

1. Access the system through your web browser
2. Register or login using the credentials
3. Use the navigation menu to:
   - Create new events
   - View registered events
   - Manage staff and student coordination
   - Update event details
   - Contact the administration

## Security

- User authentication system
- Role-based access control
- Secure database connections

## Support

For support or issues, please contact the development team.
