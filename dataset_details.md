# Project Dataset Documentation

**Dataset Link**: [Click here to access the dataset](https://drive.google.com/drive/folders/1fk9qwjRhxyO8AuwxWFcBdK_SGTHvzi7v?usp=sharing)

This project uses multiple `.csv` files containing customer, order, product, and location-related information. Below is the detailed description of each dataset and its respective columns.

---

## 📁 `customers.csv`

| Feature | Description |
|--------|-------------|
| `customer_id` | ID of the consumer who made the purchase |
| `customer_unique_id` | Unique ID of the consumer |
| `customer_zip_code_prefix` | Zip Code of consumer’s location |
| `customer_city` | Name of the City from where order is made |
| `customer_state` | State Code from where order is made (e.g., São Paulo - SP) |

---

## 📁 `sellers.csv`

| Feature | Description |
|--------|-------------|
| `seller_id` | Unique ID of the seller registered |
| `seller_zip_code_prefix` | Zip Code of the seller’s location |
| `seller_city` | Name of the City of the seller |
| `seller_state` | State Code (e.g., São Paulo - SP) |

---

## 📁 `order_items.csv`

| Feature | Description |
|--------|-------------|
| `order_id` | A Unique ID of order made by the consumers |
| `order_item_id` | A Unique ID given to each item ordered in the order |
| `product_id` | A Unique ID given to each product available on the site |
| `seller_id` | Unique ID of the seller registered in Target |
| `shipping_limit_date` | The date before which the ordered product must be shipped |
| `price` | Actual price of the products ordered |
| `freight_value` | Price rate at which a product is delivered from one point to another |

---

## 📁 `geolocations.csv`

| Feature | Description |
|--------|-------------|
| `geolocation_zip_code_prefix` | First 5 digits of Zip Code |
| `geolocation_lat` | Latitude |
| `geolocation_lng` | Longitude |
| `geolocation_city` | City |
| `geolocation_state` | State |

---

## 📁 `payments.csv`

| Feature | Description |
|--------|-------------|
| `order_id` | A Unique ID of order made by the consumers |
| `payment_sequential` | Sequences of the payments made in case of EMI |
| `payment_type` | Mode of payment used (e.g., Credit Card) |
| `payment_installments` | Number of installments in case of EMI purchase |
| `payment_value` | Total amount paid for the purchase order |

---

## 📁 `orders.csv`

| Feature | Description |
|--------|-------------|
| `order_id` | A Unique ID of order made by the consumers |
| `customer_id` | ID of the consumer who made the purchase |
| `order_status` | Status of the order made i.e., delivered, shipped, etc. |
| `order_purchase_timestamp` | Timestamp of the purchase |
| `order_delivered_carrier_date` | Delivery date at which carrier made the delivery |
| `order_delivered_customer_date` | Date at which customer got the product |
| `order_estimated_delivery_date` | Estimated delivery date of the products |

---

## 📁 `reviews.csv`

| Feature | Description |
|--------|-------------|
| `review_id` | ID of the review given on the product ordered by the order ID |
| `order_id` | A Unique ID of order made by the consumers |
| `review_score` | Review score given by the customer for each order on a scale of 1–5 |
| `review_comment_title` | Title of the review |
| `review_comment_message` | Review comments posted by the consumer for each order |
| `review_creation_date` | Timestamp of the review when it is created |
| `review_answer_timestamp` | Timestamp of the review answered |

---

## 📁 `products.csv`

| Feature | Description |
|--------|-------------|
| `product_id` | A Unique identifier for the proposed project |
| `product_category_name` | Name of the product category |
| `product_name_lenght` | Length of the string which specifies the name given to the products ordered |
| `product_description_lenght` | Length of the description written for each product ordered on the site |
| `product_photos_qty` | Number of photos of each product ordered available on the shopping portal |
| `product_weight_g` | Weight of the products ordered in grams |
| `product_length_cm` | Length of the products ordered in centimeters |
| `product_height_cm` | Height of the products ordered in centimeters |
| `product_width_cm` | Width of the product ordered in centimeters |

---

