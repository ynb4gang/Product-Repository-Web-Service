# Product Catalogue

The **Product Catalogue** is a Spring Boot application designed to manage a collection of products, allowing users to browse, add to cart, and manage their shopping cart. The application provides a user-friendly interface for viewing featured products, creating new products, and managing the shopping cart. It also includes basic contact form functionality for user inquiries.

## Features

- **Product Management**: View a list of all products, including featured products on the homepage.
- **Shopping Cart**: Add products to the cart, remove items, and clear the cart.
- **Contact Form**: Submit inquiries via a simple contact form.
- **Session Management**: The shopping cart is managed within a user session, ensuring a seamless shopping experience.

## Technologies Used

- **Spring Boot**: For building the application and managing dependencies.
- **Thymeleaf**: For server-side rendering of HTML templates.
- **JPA (Java Persistence API)**: For managing product data and database interactions.
- **H2 Database**: An in-memory database for development purposes (can be replaced with other databases like MySQL or PostgreSQL).

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ynb4gang/Product-Repository-Web-Service.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   ./mvnw clean install
   ```
3. **Build the Project**:
   ```bash
   ./mvnw spring-boot:run
   ```
4. **Run the Application**:
   ```bash
   git clone https://github.com/your-username/product-catalogue.git
   ```

## Access the Application

Open your browser and navigate to [http://localhost:8080](http://localhost:8080).

## Usage

- **Homepage**: The homepage displays featured products. You can browse through the list of products and add them to your cart.
- **Product List**: View all available products in the system.
- **Shopping Cart**: Manage your shopping cart by adding, removing, or clearing items.
- **Contact Form**: Submit your inquiries via the contact form.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch and submit a pull request.
