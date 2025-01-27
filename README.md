# Hospital Management System 🏥🚀

## Overview
A robust MERN-based system for hospitals featuring authentication & authorization, multiple JSON Web Tokens (JWTs), dual frontends (user and admin), and a scalable architecture. This system is designed to simplify hospital operations, providing seamless management for both users and administrators.

---

## Features
- **Authentication & Authorization:**
  - Secure user authentication with JWT.
  - Role-based access control (user and admin).
- **Dual Frontends:**
  - User-friendly interfaces for users and admins.
- **Scalable Architecture:**
  - Built to handle large-scale data and operations efficiently.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhey-afk/hospital-management-system.git
   cd hospital-management-system
   ```

2. Install dependencies for both server and client:
   ```bash
   # For server
   cd server
   npm install

   # For client
   cd ../client
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `server` directory with the following keys:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     PORT=5000
     ```

4. Start the application:
   ```bash
   # Start the server
   cd server
   npm start

   # Start the client
   cd ../client
   npm start
   ```

5. Access the application:
   - User frontend: `http://localhost:3000`
   - Admin dashboard: `http://localhost:3000/admin`

---

## Project Structure

```
├── client
│   ├── public
│   ├── src
│       ├── components
│       ├── pages
│       ├── redux
│       ├── App.js
│       ├── index.js
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── server.js
```

---

## Screenshots
Add screenshots of your application here.
Use an image hosting service like [Imgur](https://imgur.com/upload) or [Cloudinary](https://cloudinary.com/) to upload images and embed them using Markdown:
```md
![Screenshot Description](image_url)
```

---

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For queries, reach out at:
- GitHub: [@abhey-afk](https://github.com/abhey-afk)
