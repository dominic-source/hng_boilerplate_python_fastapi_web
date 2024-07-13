# FASTAPI
FastAPI boilerplate

## Setup

1. Create a virtual environment.
 ```sh
    python3 -m venv .venv
 ```
2. Activate virtual environment.
```sh
    source /path/to/venv/bin/activate`
```
3. Install project dependencies `pip install -r requirements.txt`
4. Create a .env file by copying the .env.sample file
`cp .env.sample .env`

5. Start server.
 ```sh
 python main.py
```

# Comprehensive API

This API provides comprehensive features for managing users, organizations, payments, and more.

## Features

* **Authentication:**
    * Social authentication
    * Magic link authentication
    * In-app authentication screens (e.g., change password)
* **Messaging (Email):**
    * Default templates
    * Background processes for sending emails
* **Payments:**
    * Integration with Stripe, Flutterwave, and LemonSqueezy
    * Internal and external payments
* **Users & Organizations:**
    * Manage users
    * Superadmin interface for users, organizations, payments, and activity logs
* **Settings:**
    * Profile settings
* **Landing Pages:**
    * Privacy policy
    * About us
* **Contact Us**
* **GDPR Cookies**
* **Dashboard:**
    * Basic dashboard with widgets
* **Waitlist (Coming Soon)**
* **Squeeze / Marketing Page**
* **Invite Flow**
* **User Data Export**
* **Random Data:**
    * Random data associated with users
    * List of random data on the dashboard (e.g., widgets)
    * View of single data (e.g., a single widget)
* **Other Data Management:**
    * List with search and sorting functionalities
* **Charting:**
    * Page with charts of user data
* **Content Editing:**
    * Edit page for content
* **Notifications**
* **Blog**
* **Invite Links**
* **Language and Region Support**
* **Email Template Management (Superadmin):** Manage HTML email templates

## Documentation

* **Swagger API Documentation:** [Swagger API](https://app.swaggerhub.com/apis/AKINNUOYET/comprehensive-api/1.0.0#/)
* **ERD Design:** [ERD Design](https://drive.google.com/file/d/1r0I6Bnyu6nVxgZakJdivvnL7aQ0GAvB_/view?usp=sharing)

This API is still under development, and some features may be marked as "Coming Soon." 


