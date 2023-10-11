<img src="https://austindevs.com/images/austin devs.png" style="width: 100px; height: auto">

<img src="https://www.paycove.io/hubfs/Imported%20images/paycove_logo_explore_nautical_wide-08.svg" style="width: 200px; height: auto">

# Adjustable Amount

## Simple Usage
* `account_id` **required*
* `adjustable_amount=true` **required* 

https://feature.paycove.io/checkout-builder-form?account_id=4ed8191f5a087c037a54205f03b5239a&adjustable_amount=true

## Fill Name and/or Email
* `account_id` **required*
* `adjustable_amount=true` **required* 
* `full_name`
* `email`

https://feature.paycove.io/checkout-builder-form?account_id=4ed8191f5a087c037a54205f03b5239a&adjustable_amount=true&email=kevin@paycove.com&full_name=Kevin%20Colten

## Fill Amount Information
* `account_id` **required*
* `adjustable_amount=true` **required* 
* `line_items[0][name]`
* `line_items[0][price]`

https://feature.paycove.io/checkout-builder-form?account_id=4ed8191f5a087c037a54205f03b5239a&adjustable_amount=true&line_items[0][name]=Item+Name&line_items[0][price]=1234

## Optional Quantity
* `account_id` **required*
* `adjustable_amount=true` **required* 
* `line_items[0][name]`
* `line_items[0][price]`
* `line_items[0][quantity]` default: 1

https://feature.paycove.io/checkout-builder-form?account_id=4ed8191f5a087c037a54205f03b5239a&adjustable_amount=true&line_items[0][name]=Item+Name&line_items[0][price]=1234&line_items[0][quantity]=2
