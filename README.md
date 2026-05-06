# jua kali connect
## Overview

Jua kali connect is a full-stack digital platform designeed to empower artisan,small-scale fabricators and internal sector businesses (jua kali) by providing tools for managing operations connecting with customers and streamlining processes.

The system bridges the gap between traditional craftsmanship and modern technology by offering features such as job trcking, customer management, inventory control, and digital payments.

## Features

### User Management
 User registration and authentication
- Role-based access (Admin, Artisan, Customer)
- Profile management

### Invetory Management
- Track raw materials and finished goods
- Low stock alerts
- Category-based organization
### Order & Job Tracking
- Create and manage customer orders
- Track job progress (Pending → In Progress → Completed)
- Assign jobs to artisans

### Payments Integration
 M-Pesa integration for seamless payments
- Payment status tracking
- Transaction history

### Communication
- Real-time chat between customers and artisans
- Notifications for updates and messages

### Dashboard & Analytics
- Admin dashboard with system overview
- Business insights (sales, orders, revenue)
- Activity logs
 
 ## Tech Stack

 **Frontend**
 - React.js
 - Tailwindcss
 - Axos
 - Redux

**Backend**
- Django
- django Rest Framework
PostgreSQL

**DevOps & Deplotment**
- docker
- Github Actions (CI/CD)
- CloudHosting(AWS/Render/Azure)


## Project structure
```
text
jua-kali-connect/
│
├── frontend/                # React application
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/                # Django application
│   ├── apps/
│   ├── models/
│   ├── views/
│   └── api/
│
├── docker/                 # Docker configurations
├── docs/                   # Documentation
├── .env.example            # Environment variables template
├── requirements.txt
├── package.json
└── README.md
```

## Istallation & Setup


```bash
git clone https://github.com/aishawanjiru/jua-kali-connect.git

cd jua-kali-connect
```
open `index.html` in any modern browser and view your site
```


### Prequisites
- node.js
- python 
- postgreSQL

## API Endpoints

| **Methods** | **Endpoints** | **Description** | 
| -------- | -------- | -------- | 
| POST | `api/auth/registry/` | Register user | 
| POST | `api/auth/registry/` | Register user | 
| GET  | `api/auth/registry/` | Login user | 
| POST | `api/auth/registry/` | Register user | 
| GET  | `api/auth/registry/` | View Inventory |

## Environment Variables

