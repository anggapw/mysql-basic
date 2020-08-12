```sql
SELECT transactions.transaction_id, customers.fullname, customers.email, products.product_name, products.price
FROM (
    (transactions INNER JOIN customers ON transactions.customer_id = customers.id)
    INNER JOIN products ON transactions.product_id = products.product_id
    );
```
