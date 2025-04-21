# angular-with-cookie-based-authentication-and-guards
Secure Angular Apps with Cookie-Based Authentication &amp; Role Guards

This project demonstrates Authentication, Role-Based Authorization, and Route Protection using Cookies in Angular 18. It includes features like login, logout, protected routes, and role-based access control.



## Features

1. Authentication:
   - Login with username and password.
   - Logout functionality.
   - Session persistence using cookies.

2. Role-Based Authorization:
   - Two roles: `admin` and `user`.
   - Admin users can access the `/admin` route.
   - Regular users cannot access the `/admin` route and are redirected to an "Unauthorized" page.

3. Route Protection:
   - Auth Guard: Protects routes from unauthorized access.
   - Role Guard: Restricts access to routes based on user roles.

4. UI Design:
   - Built using Bootstrap for a clean and responsive design.`.


## Usage

 Login Credentials

- Admin User:
  - Username: `admin`
  - Password: `admin`

- Regular User:
  - Username: `user`
  - Password: `user`

 Routes

- Login Page: `/login`
- Dashboard: `/dashboard` (protected by `AuthGuard`)
- Admin Page: `/admin` (protected by `RoleGuard`)
- Unauthorized Page: `/unauthorized`


