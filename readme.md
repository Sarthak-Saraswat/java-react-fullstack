Java React FullStack E-Commerce App

About-
A full-stack e-commerce platform built with Spring Boot (Java) for the backend and React.js for the frontend, integrated with MySQL. The application supports user registration/login, product browsing, cart management, order placement, and an optional admin panel for inventory management. It demonstrates modern web development practices, including RESTful APIs, JWT-based authentication, and Dockerized deployment, designed to showcase full-stack development skills.

🚀 Tech Stack-
»Backend: Spring Boot, Java 17+, Maven
»Frontend: React.js, Axios, Bootstrap
»Database: MySQL (H2 for development)
»Deployment: Docker, Vercel/Netlify (frontend), Render/Railway (backend), PlanetScale/Railway MySQL (database)

🎯 Features-
»User Registration & Login: Secure user authentication with [JWT or basic auth, specify based on implementation].
»Product Listing: Browse and filter products with a responsive UI.
»Cart and Order Module: Add products to cart and place orders with transaction management.
»Admin Panel: [Optional/In progress, e.g., "Basic product management implemented"].
»Performance: Optimized database queries with indexing for product searches.
»Deployment: Dockerized backend for consistent deployment; frontend hosted on [Vercel/Netlify].

🖼️ Screenshots-


<img width="742" height="1672" alt="1" src="https://github.com/user-attachments/assets/f796b1de-76fe-43b7-b7d7-2893dff2cfde" />

<img width="1150" height="976" alt="2" src="https://github.com/user-attachments/assets/0f440bea-3482-45c7-8ed2-c69fb33de04d" />

<img width="1400" height="723" alt="3" src="https://github.com/user-attachments/assets/ac824893-fd60-4165-98d0-ad9d720376a6" />

<img width="1400" height="680" alt="4" src="https://github.com/user-attachments/assets/25a7006a-f4b4-4f36-9c8f-2b775a4d049d" />

<img width="1400" height="722" alt="5" src="https://github.com/user-attachments/assets/b0c2c043-0829-4c73-9e20-cb0aaa84b741" />

<img width="1400" height="568" alt="6" src="https://github.com/user-attachments/assets/69491c5a-b71b-49e4-8437-b99c66704d3c" />

<img width="1400" height="309" alt="7" src="https://github.com/user-attachments/assets/299dba26-e8e2-4924-a2e1-f8488bbf218e" />


🧑‍💻 How to Run Locally
Prerequisites-
»Java 17+
»Maven 3.8+
»Node.js 16+ and npm
»MySQL 8.0+ (or H2 for development)
»Docker (optional, for containerized deployment)

🎈Backend Setup-
1.Navigate to the backend directory:
cd backend

2.Configure the database in src/main/resources/application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3.Start the Spring Boot application:
./mvnw spring-boot:run
The backend runs on http://localhost:8080.

🎈Frontend Setup-
1.Navigate to the frontend directory:
cd client

2.Install dependencies:
npm install

3.Start the React application:
npm start
The frontend runs on http://localhost:3000.

🏗️ Project Structure-
Backend (backend/):
  »src/main/java: Contains controllers (UserController, ProductController), services 
  (UserService, OrderService), models (User, Product), and repositories (ProductRepository).

  »src/main/resources: Configuration files like application.properties.

Frontend (client/):
   »src/components: Reusable React components (e.g., Header, ProductCard).
   »src/pages: Page-level components (e.g., LoginPage, CartPage).
   »src/context: Context API for state management (e.g., cart, user).

🔌 API Endpoints-
 Key REST APIs include:
    »POST /api/users/register: Register a new user (e.g., { "email": "user@example.com", "password": "pass123" }).
    »POST /api/users/login: Authenticate and return a JWT token.
    »GET /api/products: Retrieve all products.
    »POST /api/orders: Create an order with items from the cart.


📈 Achievements-
»Optimized product listing queries with MySQL indexing, reducing response time.
»Implemented secure user authentication with [JWT or basic auth], ensuring safe API access.
»Supports [e.g., 100+ products, 50+ concurrent users].


👨‍💻 Author

Sarthak Saraswat
GitHub: Sarthak-Saraswat


📽️ Video Walkthrough-

https://github.com/user-attachments/assets/36d6ba85-4865-4e8e-92f2-32e9c5d1ff90













