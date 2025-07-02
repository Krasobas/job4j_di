# Spring Dependency Injection Learning Project

## Project Overview
This educational project demonstrates Dependency Injection (DI) principles in Spring Boot. It serves as a practical guide to understanding core DI concepts through simple, commented examples.

## Key Learning Objectives
- Understanding Dependency Injection fundamentals
- Spring's Inversion of Control (IoC) container
- Different types of dependency injection:
    - Constructor-based
    - Setter-based
    - Field-based
- Working with Spring stereotypes:
    - `@Component`
    - `@Service`
    - `@Repository`
    - `@Controller`

## Project Structure
```
src/
├── main/
│   ├── java/com/example/dilearning/
│   │   ├── config/        # Configuration classes
│   │   ├── controllers/   # Demonstration controllers
│   │   ├── services/      # Service layer examples
│   │   ├── repositories/  # Repository examples
│   │   └── components/    # Various components
│   └── resources/
│       └── application.properties
└── test/                  # Test cases demonstrating DI
```

## Core Examples Included

### 1. Basic DI Examples
- Constructor injection
- Setter injection
- Field injection
- Qualifier usage

### 2. Advanced Scenarios
- Conditional bean registration
- Primary beans
- Lazy initialization
- Bean lifecycle callbacks

### 3. Practical Implementations
- Service layer with repository dependency
- Controller with service dependency
- Configuration classes

## How to Use This Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/spring-di-learning.git
```

2. Explore different branches for specific topics:
```bash
git branch -a  # Shows available learning modules
git checkout basic-constructor-injection
```

3. Run the application:
```bash
mvn spring-boot:run
```

## Running Tests
The project includes test cases demonstrating DI:
```bash
mvn test
```

## Configuration Examples
See `src/main/resources/application.properties` for:
- Bean scope configurations
- Profile-specific settings
- Lazy initialization control

## Learning Path Suggestions

1. Start with `basic-constructor-injection` branch
2. Proceed to `qualifier-examples`
3. Explore `profile-based-beans`
4. Finish with `conditional-bean-registration`

## Best Practices Demonstrated
- Preferring constructor injection
- Proper component scoping
- Interface-based programming
- Testing with mocked dependencies

## Dependencies
- Spring Boot 3.x
- Spring Test (for test examples)
- Lombok (for boilerplate reduction)

## Contribution
This project welcomes educational contributions:
- Add more commented examples
- Improve documentation
- Suggest better practice demonstrations