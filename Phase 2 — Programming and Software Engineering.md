# Phase 2 — Programming and Software Engineering
## AI Engineering Product School Curriculum

Phase 2 focuses on **transforming computational literacy into practical software engineering capability**.

The goal of this phase is to train engineers who can:

- write reliable software
- design maintainable systems
- build scalable backend services
- engineer production-ready applications

While Phase 1 establishes how computers work internally, **Phase 2 teaches engineers how to command computers through software**.

The emphasis is not on writing small scripts or isolated applications.  
The emphasis is on building **robust software systems that can support real technology products**.

---

# Table of Contents

1. Phase Objectives  
2. Engineering Philosophy  
3. Programming Foundations  
4. Data Structures  
5. Algorithms  
6. Software Engineering Principles  
7. Object-Oriented Programming  
8. Functional Programming  
9. Error Handling and Defensive Programming  
10. Testing and Quality Assurance  
11. Software Architecture Fundamentals  
12. API Development  
13. Databases and Data Persistence  
14. Asynchronous Programming  
15. Performance Optimization  
16. Secure Software Development  
17. Software Debugging and Profiling  
18. Documentation and Code Clarity  
19. Engineering Labs  
20. Product Engineering Projects  
21. Competencies After Phase 2

---

# 1. Phase Objectives

Phase 2 aims to build **professional-level programming and software engineering capability**.

By the end of this phase engineers will be able to:

- write structured and maintainable code
- build backend services
- design APIs
- manage persistent data systems
- implement algorithms efficiently
- build scalable application components
- structure large codebases

The outcome is an engineer capable of building **the software core of technology products**.

---

# 2. Engineering Philosophy

Programming is not merely writing code.

Programming is **systematic problem solving through software construction**.

The engineering mindset includes:

```

Problem Analysis
↓
System Design
↓
Algorithm Selection
↓
Code Implementation
↓
Testing and Validation
↓
Deployment and Monitoring

```

Engineers trained in this phase develop **structured reasoning before writing code**.

---

# 3. Programming Foundations

Programming fundamentals form the basis for all advanced software systems.

Primary language focus typically includes:

- Python
- JavaScript
- Go
- Java or C++

Python is often emphasized due to its strong role in **AI engineering and backend development**.

### Core Programming Concepts

Engineers must master:

Variables  
Data types  
Expressions  
Control flow  
Functions  
Modules  
Input and output  

Example structure:

```

Variable
Condition
Loop
Function

````

Example in Python:

```python
def calculate_average(numbers):
    total = sum(numbers)
    return total / len(numbers)
````

Students learn how to structure code **clearly and logically**.

---

# 4. Data Structures

Data structures determine **how information is stored and manipulated**.

Efficient software systems depend heavily on correct data structures.

### Core Data Structures

Arrays
Linked lists
Stacks
Queues
Hash tables
Trees
Graphs

### Engineering Importance

Choosing the correct data structure determines:

* speed
* scalability
* memory efficiency

Example:

Hash tables allow **constant-time lookup**.

---

# 5. Algorithms

Algorithms define **how problems are solved computationally**.

Engineers learn how to construct and analyze algorithms.

### Core Algorithm Categories

Searching algorithms
Sorting algorithms
Graph traversal algorithms
Dynamic programming
Greedy algorithms

### Complexity Analysis

Engineers learn **time and space complexity**.

Examples:

```
O(1)  constant time
O(n)  linear time
O(log n) logarithmic time
O(n²) quadratic time
```

Understanding complexity is essential for **building scalable systems**.

---

# 6. Software Engineering Principles

Professional engineering requires **structured software development practices**.

Core principles include:

### Modularity

Large programs are broken into smaller components.

Example structure:

```
Application
│
├── Authentication Module
├── Data Processing Module
├── API Module
└── Analytics Module
```

### Separation of Concerns

Each component performs **one clearly defined responsibility**.

### Maintainability

Code must be understandable and modifiable by other engineers.

---

# 7. Object-Oriented Programming

Object-oriented programming organizes software into **objects representing real-world entities**.

### Core Concepts

Classes
Objects
Encapsulation
Inheritance
Polymorphism

Example:

```python
class User:
    def __init__(self, name, email):
        self.name = name
        self.email = email

    def display(self):
        return f"{self.name} - {self.email}"
```

This paradigm enables **structured system modeling**.

---

# 8. Functional Programming

Functional programming emphasizes **pure functions and immutability**.

Key concepts include:

Pure functions
Immutability
Higher-order functions
Function composition

Benefits:

* predictable code behavior
* reduced side effects
* improved reliability

Functional concepts appear heavily in **data pipelines and AI workflows**.

---

# 9. Error Handling and Defensive Programming

Software must be built to handle unexpected conditions.

Engineers implement **robust error handling**.

Example:

```python
try:
    result = divide(a, b)
except ZeroDivisionError:
    print("Division by zero not allowed")
```

Defensive programming protects systems from:

* invalid inputs
* system failures
* unexpected runtime states

---

# 10. Testing and Quality Assurance

Professional software requires **systematic testing**.

### Types of Testing

Unit testing
Integration testing
System testing
End-to-end testing

Example using Python:

```python
def test_sum():
    assert sum([1,2,3]) == 6
```

Testing ensures:

* correctness
* stability
* maintainability

---

# 11. Software Architecture Fundamentals

Architecture defines **how large software systems are structured**.

### Common Architectural Styles

Monolithic architecture
Microservices architecture
Service-oriented architecture
Layered architecture

Example layered architecture:

```
Presentation Layer
Business Logic Layer
Data Access Layer
Database
```

Understanding architecture is essential for **large-scale product engineering**.

---

# 12. API Development

Modern software systems communicate using **Application Programming Interfaces (APIs)**.

APIs allow services to exchange data.

### Core Concepts

HTTP methods

```
GET
POST
PUT
DELETE
```

Example API endpoint:

```
GET /api/users
```

Engineers build APIs using frameworks such as:

* FastAPI
* Django
* Express.js
* Flask

APIs form the **backbone of modern digital platforms**.

---

# 13. Databases and Data Persistence

Most technology products require **persistent data storage**.

Engineers must understand database systems.

### Database Types

Relational databases

Examples:

* PostgreSQL
* MySQL

Non-relational databases

Examples:

* MongoDB
* Redis

### Core Database Concepts

Tables
Indexes
Queries
Transactions

Example SQL query:

```sql
SELECT name FROM users WHERE age > 25;
```

Database design determines **data reliability and performance**.

---

# 14. Asynchronous Programming

Modern applications handle **multiple tasks simultaneously**.

Asynchronous programming enables non-blocking execution.

Example:

```python
async def fetch_data():
    data = await api_call()
    return data
```

Benefits include:

* improved performance
* efficient resource usage
* responsiveness in high-load systems

---

# 15. Performance Optimization

Engineers must build systems that perform efficiently.

Optimization techniques include:

* algorithm improvements
* caching strategies
* efficient database queries
* concurrency management

Tools used include:

* profilers
* benchmarking frameworks

Performance engineering becomes essential in **large-scale systems**.

---

# 16. Secure Software Development

Security must be integrated into software design.

Key areas include:

* input validation
* authentication systems
* authorization control
* data encryption

Example vulnerability to prevent:

```
SQL Injection
```

Secure software protects both **users and system infrastructure**.

---

# 17. Software Debugging and Profiling

Engineers must diagnose software failures.

Debugging methods include:

* stack trace analysis
* log inspection
* runtime debugging tools

Profiling tools help identify:

* memory leaks
* CPU bottlenecks
* inefficient code paths

---

# 18. Documentation and Code Clarity

Clear documentation is essential for collaboration.

Engineers must produce:

* README files
* API documentation
* code comments
* architectural documentation

Example docstring:

```python
def calculate_tax(amount):
    """
    Calculate tax based on transaction amount.
    """
```

Well-documented systems are easier to maintain and scale.

---

# 19. Engineering Labs

Hands-on development sessions reinforce learning.

Example labs include:

### Lab 1 — Algorithm Implementation

Students implement sorting algorithms and analyze performance.

### Lab 2 — API Development

Build a REST API that performs CRUD operations.

### Lab 3 — Database Integration

Create an application that stores and retrieves structured data.

### Lab 4 — Asynchronous Service

Build a service capable of handling concurrent requests.

---

# 20. Product Engineering Projects

Students build complete software systems.

### Project 1 — Backend Service Platform

Build a backend service capable of:

* authentication
* user management
* database storage
* API endpoints

### Project 2 — Scalable Data Processing Tool

Develop a program capable of processing large datasets.

### Project 3 — Distributed API Service

Build a multi-service backend architecture.

---

# 21. Competencies After Phase 2

Engineers completing this phase possess strong programming capability.

### Software Construction

Ability to design and implement structured software systems.

### Algorithmic Thinking

Ability to choose efficient algorithms and data structures.

### Backend Development

Ability to build APIs and integrate databases.

### System Reliability

Ability to test, debug, and maintain software systems.

---

# Transition to Phase 3

Phase 2 produces engineers capable of building **robust software systems**.

The next stage focuses on:

**Phase 3 — Data Engineering and Artificial Intelligence Foundations**

This phase introduces:

* machine learning
* data pipelines
* large-scale data processing
* AI model deployment


