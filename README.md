# rs-ddd-simple-test

## Entities

- Manager
  - id
- ProductStock
  - id
  - size?
  - color?
  - quantity
  - minQuantity
  - createdAt
  - updatedAt
- SingleProduct
  - id
  - size?
  - color?
  - status
  - createdAt
  - updatedAt
- ProductStockHistory
  - date
  - product
  - createdAt
  - updatedAt
- Alert
  - id
  - email
  - notification
  - product
- Order/Sale
  - id
  - value
  - products
  - status
  - createdAt
  - updatedAt

## Use Cases

- Add product
- Remove product
- Update product stock
- Track single product
- Get/Set minimum stock quantity
- Send alert (when out of stock)
- Create order
- Update order
- Get orders history
  - product sold on a period of time
  - profit generated on a period of time by product
- Get stock history
  - get quantity of product on a period of time (e.g. daily product quantity)
- Update delivery deadline 
