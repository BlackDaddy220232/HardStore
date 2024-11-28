# PC Components Online Store

## Description
This is a web application for an online store specializing in PC components. The application provides the following functionality:
- **Homepage with filters**: Browse components by categories and filter by specifications (e.g., price, brand).
- **PC Configurator**: Build custom PCs and check component compatibility.
- **Shopping Cart**: Add, edit, or remove items and proceed to checkout.
- **Admin Dashboard**: Upload new products via CSV and view all orders.
- **User Authentication**: Register, log in, and access personal order history.

The backend is implemented in **Java EE**, running on **Tomcat**, and follows a RESTful architecture. A lightweight frontend is implemented using **HTML, CSS, and JavaScript**, with API integration.

---

## Features
1. **Homepage**:
   - Category-based navigation (e.g., motherboards, GPUs).
   - Advanced filters (price range, brand, specifications).
   - Pagination and sorting.

2. **PC Configurator**:
   - Interactive tool to select components and validate compatibility.
   - Automatic suggestions for compatible components.

3. **Shopping Cart**:
   - Persistent cart for authenticated users.
   - Dynamic cost calculation and order summary.
   - Integration with the checkout process.

4. **Admin Dashboard**:
   - CSV-based bulk upload of products.
   - View, filter, and sort all orders.

5. **User Management (Final Stage)**:
   - Authentication for secure login.
   - Role-based access (Admin/User).
   - Personal dashboard for order history.

---

## Development Timeline

| **Phase**                      | **Tasks**                                                    | **Dates**         | **Duration** |
|---------------------------------|-------------------------------------------------------------|-------------------|--------------|
| **Environment Setup**           | Configure Tomcat, database, and project structure           | Nov 29            | 1 days       |
| **Homepage with Filters**       | API for filtering, pagination, and frontend integration     | Nov 30 - Dec 1     | 2 days       |
| **PC Configurator**             | API for building PCs, compatibility checks, and frontend    | Dec 2 - Dec 4     | 3 days       |
| **Shopping Cart**               | CRUD for cart items and checkout integration                | Dec 5 - Dec 6     | 2 days       |
| **Admin Dashboard**             | CSV product upload and order management                     | Dec 7 - Dec 8   | 2 days       |
| **User Authentication**         | login, role management, and history retrieval               | Dec 9 - Dec 10           | 2 day        |
| **Simple Frontend**             | Simple Frontend                                             | Dec 11            | 2 day          |
| **Simple Frontend**             | Testing                                                     | Dec 12            | 2 day          |

**Note:** Some frontend work (basic layout and functionality) will be performed during the development of respective modules.

---
 
