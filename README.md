# 🛠️ Gas Utility Services Application

Welcome to the Gas Utility Services Application! This Django application provides consumer services for gas utilities. Customers can submit service requests online, track the status of their requests, and view their account information. Customer support representatives also have tools to manage requests and provide support to customers.

## 📋 Features

- **Service Requests:** Customers can submit service requests online, including selecting the type of request, providing details, and attaching files.
- **Request Tracking:** Customers can track the status of their service requests, including submission and resolution timestamps.
- **Account Information:** Customers can view their account information.

## 🚀 Installation

Follow these steps to set up the Gas Utility Services Application:

### Prerequisites

- Python (3.6 or higher)
- Django (3.0 or higher)

### Clone the Repository

```bash
git clone https://github.com/your_username/gas-utility-services.git

````
```bash
cd gas-utility-services
````

## Installation

## Install Dependencies
```bash

pip install -r requirements.txt

````

### Run Migrations
```bash
python manage.py makemigrations

````
### Now Run This
```bash
python manage.py migrate

````

### Create a Superuser

```bash
python manage.py createsuperuser
````
### Start the Development Server
```bash
python manage.py runserver
```

### Here is the complete path for the reference 
```bash
gas-utility-services/
|-- gas_utility_app/
|   |-- gas_utility_app/
|   |   |-- __init__.py
|   |   |-- settings.py
|   |   |-- urls.py
|   |   |-- wsgi.py
|-- customer_services/
|   |-- migrations/
|   |-- templates/
|   |   |-- customer_services/
|   |       |-- submit_service_request.html
|   |       |-- track_service_request.html
|   |-- __init__.py
|   |-- admin.py
|   |-- apps.py
|   |-- forms.py
|   |-- models.py
|   |-- tests.py
|   |-- urls.py
|   |-- views.py
|-- manage.py
|-- README.md
|-- requirements.txt

```bash





