# Bookstore Management Using SQL

---

## Database Structure

1. Tabel "Books":
- Columns:
book_id (Primary Key)
title
author_id (Foreign Key ke tabel Authors)
category_id (Foreign Key ke tabel Categories)
price
stock_quantity

2. Tabel "Authors":
- Columns:
author_id (Primary Key)
author_name

3. Tabel "Categories":
- Columns:
category_id (Primary Key)
category_name

4. Tabel "Transactions":
- Columns:
transaction_id (Primary Key)
book_id (Foreign Key ke tabel Books)
transaction_date
quantity
total_price

---

Tabel Authors
INSERT INTO Authors (author_id, author_name) VALUES
(1, 'J.K. Rowling'),
(2, 'George Orwell'),
(3, 'Harper Lee'),
(4, 'J.R.R. Tolkien');

Tabel Categories
INSERT INTO Categories (category_id, category_name) VALUES
(1, 'Fiction'),
(2, 'Non-Fiction'),
(3, 'Fantasy'),
(4, 'Science Fiction');

Tabel Books
INSERT INTO Books (book_id, title, author_id, category_id, price, stock_quantity) VALUES
(1, 'Harry Potter and the Philosopher''s Stone', 1, 1, 12.99, 50),
(2, '1984', 2, 1, 9.99, 30),
(3, 'To Kill a Mockingbird', 3, 1, 8.99, 40),
(4, 'The Hobbit', 4, 3, 11.99, 25),
(5, 'Harry Potter and the Chamber of Secrets', 1, 1, 14.99, 45),
(6, 'Animal Farm', 2, 1, 7.99, 35),
(7, 'The Fellowship of the Ring', 4, 3, 10.99, 20);

Tabel Transactions
INSERT INTO Transactions (transaction_id, book_id, transaction_date, quantity, total_price) VALUES
(1, 1, '2024-02-10', 3, 38.97),
(2, 3, '2024-02-11', 2, 17.98),
(3, 5, '2024-02-12', 1, 14.99),
(4, 2, '2024-02-13', 5, 49.95),
(5, 4, '2024-02-14', 2, 23.98),
(6, 7, '2024-02-15', 3, 32.97);

---

## Displays all book information along with the author and category.

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/551ff779-e98a-4897-b2dd-27fdcddd43ac)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/cf9eb9b0-6105-47a1-92d7-8ca098180f26)

---

## Displays the total revenue from book sales per category.

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/8d429fc9-756c-4dde-b9df-1982b3bcb031)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/b2589ef5-d69a-4bb7-ac8f-c56012941b14)

---

## Displays the top 5 bestsellers (based on the number of sales)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/6e853616-f69c-47e7-af38-371410491110)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/4f2bf3f3-44e3-4b29-8714-6a95d990ea4f)

---

## Displays a list of authors who have more than one book in the catalog.

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/733d5f8a-9caa-4848-aae4-f9c167a799ac)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/22d6789a-29d2-4902-856a-1b0ab24cb6f2)

---

## Displays the total revenue from sales per month.

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/5d9ca033-f64e-406c-9ef6-a5ab31bb8a42)

![image](https://github.com/abijabohdan/Python-Projects/assets/114718852/af10c07f-d342-45a0-9ce9-f7dbf30c5f86)

---
