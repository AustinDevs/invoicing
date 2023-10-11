
# Paycove Adjustable Amount

## Simple Usage
* `account_id` **required
* `adjustable_amount=true` **required* 

http://localhost:8000/checkout-builder-form?account_id=115a3bf20a99f0b64c1752de6ca51067&adjustable_amount=true

## Fill Full Name and/or Email
* `full_name`
* `email`

http://localhost:8000/checkout-builder-form?account_id=115a3bf20a99f0b64c1752de6ca51067&adjustable_amount=true&email=kevincolten@gmail.com&full_name=Kevin%20Colten

## Fill Amount Information

* `line_items[0][name]`
* `line_items[0][price]`

http://localhost:8000/checkout-builder-form?account_id=115a3bf20a99f0b64c1752de6ca51067&adjustable_amount=true&email=kevincolten@gmail.com&full_name=Kevin%20Colten&line_items[0][name]=Item+Name&line_items[0][price]=1234

## Optional Quantity

* `line_items[0][name]`
* `line_items[0][price]`
* `line_items[0][quantity]` default: 1

http://localhost:8000/checkout-builder-form?account_id=115a3bf20a99f0b64c1752de6ca51067&adjustable_amount=true&email=kevincolten@gmail.com&full_name=Kevin%20Colten&line_items[0][name]=Item+Name&line_items[0][price]=1234&line_items[0][quantity]=2
