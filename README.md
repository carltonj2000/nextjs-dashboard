## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Code Creation Information

```bash
npm i @vercel/postgres
```

### Carlton's Log

- 12/21/23 - Cloned and started course
  - 8:10 AM - completed ch1 - getting started
  - 8:32 AM - completed ch2 - css styling
  - 9:17 AM - completed ch3 - optimizing fonts and images
  - 9:40 AM - completed ch4 - creating layouts and pages
  - 9:59 AM - completed ch5 - navigating between pages
  - 10:39 AM - completed ch6 - setup db
  - 4:35 PM - completed ch7 - fetching data
  - 4:55 PM - completed ch8 - static and dynamic rendering
  - 6:05 PM - completed ch9 - streaming

### SQL Information

```sql
SELECT invoices.amount, customers.name
FROM invoices
JOIN customers ON invoices.customer_id = customers.id
WHERE invoices.amount = 666;
```
