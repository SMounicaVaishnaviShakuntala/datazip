CREATE TABLE orders (
  id INT PRIMARY KEY,
  customer_name VARCHAR(50),
  product VARCHAR(50),
  quantity INT,
  order_date DATE
);

INSERT INTO orders VALUES
(1, 'Rohan Khanna', 'Laptop', 1, '2024-04-01'),
(2, 'Priya Sharma', 'Smartphone', 2, '2024-04-02'),
(3, 'Amit Verma', 'Tablet', 1, '2024-04-03'),
(4, 'Sneha Gupta', 'Monitor', 2, '2024-04-04'),
(5, 'Rajeev Singh', 'Keyboard', 3, '2024-04-05'),
(6, 'Pooja Yadav', 'Mouse', 2, '2024-04-06'),
(7, 'Manish Agarwal', 'Printer', 1, '2024-04-07'),
(8, 'Anjali Mehta', 'Camera', 1, '2024-04-08'),
(9, 'Vikram Chauhan', 'Smartwatch', 2, '2024-04-09'),
(10, 'Neha Bansal', 'Headphones', 4, '2024-04-10');
