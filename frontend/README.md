# Bookstore Backend (Spring Boot)
This is a generated skeleton for the full backend (Option B) for your Online Bookstore project.
Features included:
- CRUD for Books
- User registration & login (JWT)
- Cart (basic)
- Orders (basic)
- Razorpay order creation endpoint

## Setup
1. Edit `src/main/resources/application.properties` - set your MySQL credentials and a secure `jwt.secret`.
2. Optionally set Razorpay keys in `application.properties`:
```
razorpay.key=YOUR_KEY
razorpay.secret=YOUR_SECRET
```
3. Build & run:
```
mvn clean package
mvn spring-boot:run
```

## Important notes
- This is a skeleton and intended to be extended. Passwords are stored hashed using BCrypt.
- JWT secret must be at least 32 characters for HS256 HMAC key generation.
- For quick testing you can use H2 or local MySQL server.
