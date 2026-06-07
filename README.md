# Nakasero Primary School Website

A complete multi-page school website with online admission management system.

## Features

- **Website Pages**: Home, About, Academics, Admissions, Gallery, News & Events, Contact
- **Online Admission System**: Complete student registration with document uploads
- **Admin Dashboard**: Manage applications, approve/reject admissions, send automated emails
- **Responsive Design**: Mobile, tablet, and desktop compatible
- **Modern UI**: Inspired by Believe Memphis Academy
- **Authentication**: Secure admin login with password hashing
- **Email Notifications**: Automated approval/rejection emails using PHPMailer

## Color Palette

- Green (#1B5E20) - Primary
- White (#FFFFFF) - Background
- Yellow (#FFD700) - Accents
- Red (#D32F2F) - Alerts/Highlights

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: PHP 8
- **Database**: MySQL 8
- **Email**: PHPMailer
- **Authentication**: PHP Sessions & Password Hashing

## Installation

1. Clone the repository
2. Import `database.sql` into MySQL
3. Configure `config/config.php` with your database credentials
4. Set up a web server (Apache/Nginx) with PHP 8 support
5. Ensure `uploads/` directory is writable
6. Access the website at `http://localhost/nacas`

## Directory Structure

```
nacas/
├── public/              # Public assets
│   ├── css/
│   ├── js/
│   └── images/
├── pages/               # Website pages
├── admin/               # Admin dashboard
├── admission/           # Admission system
├── api/                 # API endpoints
├── config/              # Configuration files
├── classes/             # PHP classes
├── uploads/             # Student documents
└── database.sql         # Database schema
```

## Default Admin Credentials

- **Username**: admin@nps.ug
- **Password**: Admin@2025 (Change on first login)

## Support

For issues or feature requests, please contact: info@nakasero.ug
