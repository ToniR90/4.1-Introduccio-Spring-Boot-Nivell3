# Spring Boot - Testing Spring Boot Projects with Postman

This task focuses on testing two previously developed Spring Boot projects (one using Maven, the other using Gradle) using **Postman environments and variables**.

---

## Goal

To test and validate the REST endpoints exposed by the Maven and Gradle Spring Boot projects using Postman by:

- Creating two environments in Postman
- Defining and using environment variables
- Making requests using those variables
- Verifying correct responses from the running applications

---

## Postman Environment Setup

### Environment 1: Maven Project

- **Environment name:** `Project Maven`
- **Variables:**
  - `server` → `http://localhost:`
  - `port` → `9000`

### Environment 2: Gradle Project

- **Environment name:** `Project Gradle`
- **Variables:**
  - `server` → `http://localhost:`
  - `port` → `9001`

---

## Example URL Using Postman Variables

```plaintext
{{server}}{{port}}/HelloWorld/Toni
```

---

## Useful resources

<u>**https://www.youtube.com/watch?v=7E60ZttwIpY**</u>

Postman: Installation & Requests


<u>**https://www.youtube.com/watch?v=9I9U5-WUrDo&t=1s**</u>

Postman enviroments and params


