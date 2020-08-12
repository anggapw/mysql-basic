```sql
CREATE TABLE transactions
(transaction_id int NOT NULL PRIMARY KEY AUTO_INCREMENT,
customer_id int,
product_id int,
FOREIGN KEY (customer_id) REFERENCES customers(id),
FOREIGN KEY (product_id) REFERENCES products(product_id));
```

```sql
INSERT INTO transactions (customer_id, product_id) VALUES (2,1);
INSERT INTO transactions (customer_id, product_id) VALUES (2,4);
INSERT INTO transactions (customer_id, product_id) VALUES (1,5);
```
