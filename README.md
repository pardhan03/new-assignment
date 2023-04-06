CREATE DATABASE work;
SHOW DATABASES;
USE work;

CREATE TABLE products (
  product_id INT PRIMARY KEY,
  product_name VARCHAR(50),
  category VARCHAR(50),
  price DECIMAL(10,2)
);

INSERT INTO products (product_id, product_name, category, price) VALUES 
  (1, 'T-Shirt', 'Clothing', 10.99),
  (2, 'Socks', 'Clothing', 4.99),
  (3, 'Hat', 'Accessories', 12.99),
  (4, 'Shoes', 'Footwear', 59.99),
  (5, 'Backpack', 'Accessories', 29.99),
  (6, 'Pants', 'Clothing', 24.99);
  
  
  
  SELECT DISTINCT category FROM products;
