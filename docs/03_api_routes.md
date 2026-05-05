# API Routes & Web Endpoints

*This document lists the URLs and routing structure for the Naut platform.*

## Core Routes
- `GET /` : Main dashboard overview (Hub)
- `GET /login` : Authentication
- `POST /auth/login` : Login handler

## Modules

### Finance Analitica
- `GET /finance` : Finance dashboard
- `GET /finance/ledger` : Full transaction list
- `POST /finance/transaction` : Manually log transaction

### Service Management
- `GET /services` : Calendar view
- `POST /services/book` : Create new booking
- `PUT /services/:id/status` : Update booking status

### Inventory Management
- `GET /inventory` : Asset tracking dashboard
- `POST /inventory/order` : Log new supply order
- `PUT /inventory/:id/deduct` : Deduct materials used
