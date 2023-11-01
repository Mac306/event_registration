# Event Management System

An Event Management System built with PHP and MySQL.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Event Management System is a web application designed to help event organizers plan, manage, and promote their events efficiently. It provides tools for creating and managing events, handling registrations, and more. This system simplifies the event management process and enhances the attendee experience.

## Features

- User authentication and authorization.
- Event creation and management.
- Registration and ticketing system.
- Attendee management.
- Event promotion and marketing.
- Reporting and analytics.

## Getting Started

To get started with the Event Management System on your local machine, follow the steps below:

### Prerequisites

- [PHP](https://www.php.net/downloads.php)
- [MySQL](https://dev.mysql.com/downloads/)
- A web server (e.g., [Apache](https://httpd.apache.org/download.cgi) or [XAMPP](https://www.apachefriends.org/index.html))
- [Composer](https://getcomposer.org/download/) for managing PHP dependencies.

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/event-management-system.git
1. cd event-management-system
2. composer install
3. Create a MySQL database named "event_db" for the project.
4. // config.php

$conn = new mysqli('localhost', 'root', '', 'event_db');
if ($conn->connect_error) {
    die("Could not connect to MySQL: " . $conn->connect_error);
}

5. Start your local web server (e.g., Apache) and ensure PHP is running.
6. http://localhost:8080/event-management-system
Usage
Open the application in your web browser.
Sign in with the default admin credentials or create a new account.
Start creating and managing events, handling registrations, and utilizing the system's features.
Please note that the default database connection assumes a MySQL server running on localhost with the 'root' user and no password. Make sure your local MySQL server is configured accordingly.

Contributing
We welcome contributions from the community. To contribute to the project:

Fork the repository on GitHub.
Clone your fork locally.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive commit messages.
Push your changes to your fork.
Create a pull request on the original repository's GitHub page.
We appreciate your contributions and will review your pull request as soon as possible.

License
This project is licensed under the MIT License.
