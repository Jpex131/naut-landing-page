# Database Schema

*This document maps out exactly what data goes in each table for the Relational DB (PostgreSQL/MySQL).*

## Core Tables (Planned)

### 1. `transactions` (Finance Analitica)
- `id` (PK)
- `type` (INCOME | EXPENSE)
- `amount`
- `description`
- `date`
- `source_module` (SERVICES | INVENTORY | MANUAL)
- `reference_id` (FK to Booking or Order)

### 2. `bookings` (Service Management)
- `id` (PK)
- `client_name`
- `service_date`
- `status` (PENDING | IN_PROGRESS | COMPLETED)
- `provider_id`
- `total_cost`

### 3. `inventory_items` (Product Manejo)
- `id` (PK)
- `item_name`
- `stock_level`
- `unit_cost`
- `supplier_info`

*(Schema to be expanded during Phase 1: Foundation & Data Modeling)*
