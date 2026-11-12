# Protein Firebox Ordering Platform

An online food ordering platform for **Protein Firebox**, a takeaway business specialising in freshly prepared meals.

The application will allow **anyone to order without creating an account**. Customers can browse meals, customise their choices, add items to a basket, pay securely, and request delivery or collection. It will also help Protein Firebox staff manage menus and incoming orders in one place, reducing reliance on third-party food delivery marketplaces.

## Project Goals

- Make it quick and easy for anyone to order directly from Protein Firebox.
- Provide a mobile-friendly, accessible ordering experience.
- Support secure checkout and clear order confirmation.
- Give staff a simple way to manage meals, availability, and order progress.
- Build a foundation that can grow as the business expands.

## Front-End Plan

The front end will provide the customer-facing ordering experience and a separate staff administration interface.

- **Responsive design:** Create a clean website that works on phones, tablets, and desktops.
- **Menu browsing:** Show food photos, descriptions, prices, and relevant nutritional information, such as protein content.
- **Meal customisation:** Let customers choose available options and add-ons.
- **Basket and checkout:** Allow users to review quantities, totals, and order details before paying.
- **Guest ordering:** Let anyone place an order without registration or sign-in.
- **Delivery or collection:** Provide a choice of fulfilment methods, subject to availability.
- **Order confirmation:** Display an order number and confirmation after a successful order.
- **Staff dashboard:** Provide pages for viewing orders, updating order statuses, and maintaining the menu.
- **Proposed technology:** React, HTML, CSS, and JavaScript (or TypeScript), with accessible UI components.

## Back-End Plan

The back end will handle business rules, data storage, security, payments, and communication between the website and staff tools.

- **REST API:** Expose endpoints for menu items, basket pricing, orders, and order status.
- **Database:** Store meals, prices, customisation options, availability, orders, order items, and fulfilment details.
- **Order processing:** Validate item availability, calculate totals on the server, and record submitted orders.
- **Payments:** Integrate a secure payment provider such as Stripe; do not store card details on the application server.
- **Staff access:** Protect administrative actions with authentication and role-based authorisation; guest customers do not need accounts.
- **Order management:** Allow staff to accept, prepare, complete, or cancel orders, with appropriate checks.
- **Notifications:** Send order confirmations and status updates by email, with SMS as a possible future enhancement.
- **Security and reliability:** Validate inputs, protect customer information, handle errors, and log important events.
- **Proposed technology:** ASP.NET Core Web API (C#) and SQL Server.

## Initial Development Phases

1. **Plan and design:** Confirm ordering rules, menu details, delivery/collection options, and page layouts.
2. **Build the menu and basket:** Implement responsive browsing, meal customisation, and basket management.
3. **Build the API and database:** Implement menu management, server-side pricing, and order storage.
4. **Add checkout and staff tools:** Integrate payments and create the order management dashboard.
5. **Test and launch:** Test ordering flows, mobile usability, payment handling, and security before deployment.

## Initial Scope

The first version will focus on **guest ordering, menu browsing, checkout, order confirmation, and basic staff order management**. Customer accounts, loyalty rewards, advanced promotions, and delivery tracking may be added later.

> **Status:** Planning. Technologies and features listed above are proposals and may change during development.
