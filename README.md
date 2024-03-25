## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Code Creation Information

```bash
npm i @vercel/postgres
npm i use-debounce
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
  - 6:35 PM - completed ch10 - partial prerendering
- 12/22/23 - continued course
  - 12:30 PM - completed ch11 - search and pagination
- 03/22/24 - continued course
  - 10:00 AM - completed ch12 - mutating data
  - 1:00 PM - completed ch13 - handling errors
  - 3:00 PM - completed ch14 - improving accessibility
- 03/25/24 - continued course
  - 10:37 AM - completed ch15 - authentication

### SQL Information

```sql
SELECT invoices.amount, customers.name
FROM invoices
JOIN customers ON invoices.customer_id = customers.id
WHERE invoices.amount = 666;
```
