# MOHAB AI ERP Database

## Tables

### users
- id
- name
- phone
- password
- role

### customers
- id
- name
- phone
- address
- status
- notes

### sales
- id
- customer_id
- total
- payment_type
- date

### installments
- id
- sale_id
- due_date
- amount
- status

### production_orders
- id
- customer_id
- product_name
- stage
- delivery_date

### inventory
- id
- item_name
- quantity
- minimum_stock

### employees
- id
- name
- position
- salary
- commission

### expenses
- id
- category
- amount
- date
