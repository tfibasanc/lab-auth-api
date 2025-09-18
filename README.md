# 📌 Project Overview
This project demonstrates a basic Authentication API built with Express.js and MySQL. It implements Signup, Login, Logout (token revocation), and a protected /profile endpoint using JWT. Passwords are securely stored as bcrypt hashes, and the API is tested using Postman with environment variables.

# ✨ Features
- User Signup (POST /auth/signup) with hashed passwords
- User Login (POST /auth/login) with JWT issuance
- User Logout (POST /auth/logout) with token revocation
- Protected Profile endpoint (GET /profile)
- MySQL integration for users and revoked_tokens
- Environment variables for configuration (.env)
- CORS-enabled API for browser requests
- Postman environment with {{baseUrl}}

# 📝 Conclusion
This lab helped me understand how to implement secure authentication using JWT and bcrypt in an Express.js API. I learned how to structure an Express project, connect it to MySQL, and protect routes with middleware. Testing the API with Postman reinforced how JWT tokens and password hashing work together to secure user data. Overall, this lab improved my understanding of building a complete authentication system from scratch.
