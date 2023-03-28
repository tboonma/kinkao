# Kin Kao

A Software Development Security assignment. Kin Kao is a web-based restaurant application that offers various 
authorization methods to secure its customers' data and ensure their privacy.

### Labs

This is a completed version for lab 1-3, if you want to see this assignment in each lab, you can view them in each branch.    
[Spring Security 1 - Basic Authentication](https://github.com/tboonma/kinkao/tree/lab1)    
[Spring Security 2 - OpenID](https://github.com/tboonma/kinkao/tree/lab2)    
[Spring Security 3 - Env, UUID, DTO](https://github.com/tboonma/kinkao/tree/lab3)

## Getting Started

### Requirements
| Name     | Recommended version(s) |   
|----------|------------------------|
| Java SDK | 17                     |

### Installation

1. Clone this project and make sure you have all dependencies
2. Define Environment Variables
```
GITHUB_CLIENT_ID=your-client-id
GITHUB_CLIENT_SECRET=your-client-secret
GOOGLE_CLIENT_ID=your-client-id
GOOGLE_CLIENT_SECRET=your-client-secret
```

3. If you are using IntelliJ prior to 2020.3, you will need to install a Lombok IntelliJ plugin by following these steps.
   https://projectlombok.org/setup/intellij


4. Run the application
```shell
mvn spring-boot:run
```

5. Go to http://localhost:8090
