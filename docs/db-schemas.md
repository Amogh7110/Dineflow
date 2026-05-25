# MongoDB Schemas

## User
- `name`, `email`, `password` (hashed), `role` (admin | staff | customer)

## Menu
- `name`, `description`, `price`, `category`, `image`, `available`

## Reservation
- `user`, `branch`, `date`, `time`, `partySize`, `status`

## Order
- `user`, `branch`, `items[]`, `total`, `status`, `paymentStatus`
