# MOHAB AI ERP Database Schema V1

## Users

- id
- full_name
- phone
- email
- password_hash
- role
- is_active
- created_at

## Customers

- id
- customer_name
- phone
- address
- city
- source
- status
- notes
- created_at

## FollowUps

- id
- customer_id
- followup_date
- notes
- next_followup

## Products

- id
- name
- category
- cost_price
- selling_price
- stock_quantity

## Quotations

- id
- customer_id
- quotation_date
- total_amount
- status

## Sales

- id
- customer_id
- invoice_number
- total_amount
- payment_type
- created_at

## Installments

- id
- sale_id
- due_date
- amount
- payment_status

## ProductionOrders

- id
- customer_id
- product_id
- start_date
- delivery_date
- current_stage

## Inventory

- id
- item_name
- quantity
- minimum_quantity

## Employees

- id
- employee_name
- position
- salary
- commission_rate

## Expenses

- id
- category
- amount
- expense_date
