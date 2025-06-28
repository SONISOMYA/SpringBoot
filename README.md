HIREORBIT!!


## PROJECT STRUCTURE
hire-orbit
 └── src
      └── main
           ├── java
           │    └── com.yourname.hireorbit
           │           ├── HireOrbitApplication.java
           │           ├── config
           │           │     ├── SecurityConfig.java
           │           │     ├── JwtAuthenticationFilter.java
           │           │     ├── JwtProvider.java
           │           ├── controller
           │           │     ├── AuthController.java
           │           │     ├── ApplicationController.java
           │           ├── entity
           │           │     ├── User.java
           │           │     ├── Application.java
           │           ├── repository
           │           │     ├── UserRepository.java
           │           │     ├── ApplicationRepository.java
           │           ├── service
           │           │     ├── UserService.java
           │           │     ├── AuthService.java
           │           │     ├── ApplicationService.java
           │           ├── payload
           │           │     ├── LoginRequest.java
           │           │     ├── SignupRequest.java
           │           │     ├── JwtResponse.java
           │           │     ├── ApplicationRequest.java
           │           ├── exception
           │           │     ├── GlobalExceptionHandler.java
           │           │     ├── CustomException.java
           │           └── util
           │                 ├── JwtUtil.java
           │                 ├── Constants.java
           └── resources
                ├── application.properties
                
