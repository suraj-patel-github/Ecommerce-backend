# Ecommerce-backend

ecommerce-backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/ecommerce/
│   │   │       ├── EcommerceApplication.java     # Main class
│   │   │
│   │   │       ├── config/
│   │   │       │   ├── SecurityConfig.java
│   │   │       │   ├── RedisConfig.java
│   │   │       │   └── SwaggerConfig.java
│   │   │
│   │   │       ├── controller/
│   │   │       │   ├── AuthController.java
│   │   │       │   ├── ProductController.java
│   │   │       │   ├── CartController.java
│   │   │       │   └── OrderController.java
│   │   │
│   │   │       ├── dto/
│   │   │       │   ├── AuthRequest.java
│   │   │       │   ├── AuthResponse.java
│   │   │       │   ├── ProductDTO.java
│   │   │       │   └── OrderDTO.java
│   │   │
│   │   │       ├── entity/
│   │   │       │   ├── User.java
│   │   │       │   ├── Product.java
│   │   │       │   ├── CartItem.java
│   │   │       │   └── Order.java
│   │   │
│   │   │       ├── exception/
│   │   │       │   ├── GlobalExceptionHandler.java
│   │   │       │   ├── ResourceNotFoundException.java
│   │   │       │   └── UnauthorizedException.java
│   │   │
│   │   │       ├── middleware/
│   │   │       │   └── JwtFilter.java
│   │   │
│   │   │       ├── repository/
│   │   │       │   ├── UserRepository.java
│   │   │       │   ├── ProductRepository.java
│   │   │       │   └── OrderRepository.java
│   │   │
│   │   │       ├── security/
│   │   │       │   ├── JwtUtil.java
│   │   │       │   ├── CustomUserDetailsService.java
│   │   │       │   └── JwtAuthenticationEntryPoint.java
│   │   │
│   │   │       ├── service/
│   │   │       │   ├── AuthService.java
│   │   │       │   ├── ProductService.java
│   │   │       │   ├── CartService.java
│   │   │       │   └── OrderService.java
│   │   │
│   │   │       └── util/
│   │   │           └── ResponseUtil.java
│   │   |
│   │   └── resources/
│   │       ├── application.yml
│   │       ├── logback-spring.xml
│   │       └── static/
│   │           └── (optional)
│
├── test/
│   └── java/com/example/ecommerce/
│       ├── AuthServiceTest.java
│       ├── ProductServiceTest.java
│       └── OrderServiceTest.java
│
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── README.md
├── pom.xml
