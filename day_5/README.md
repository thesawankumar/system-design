# SOLID Principles

## What is SOLID?
SOLID is a set of five object-oriented design principles used to build clean, scalable, and maintainable software systems.

---

# SOLID Principles

## S - Single Responsibility Principle
A class should have only one reason to change.

## O - Open Closed Principle
Open for extension, closed for modification.

## L - Liskov Substitution Principle
Child classes should replace parent classes without breaking behavior.

## I - Interface Segregation Principle
Do not force classes to implement unused methods.

## D - Dependency Inversion Principle
Depend on abstractions, not concrete implementations.

---

# Why SOLID?
- Cleaner code
- Better scalability
- Loose coupling
- Easier maintenance
- Better testing

---

# Real World Usage
Used heavily in:
- Spring Boot
- Backend systems
- Microservices
- Enterprise applications

---

# Interview Questions
1. What is SOLID?
2. Difference between tight and loose coupling?
3. Which SOLID principle is most important?
4. Explain DIP with real-world example.

# Understanding Interfaces, Abstraction, and Persistence

## What is Persistence?
Persistence means storing data permanently in:
- Databases
- Files
- Cloud storage

---

# Why Use Interfaces?

Interfaces help achieve:
- Abstraction
- Loose coupling
- Scalability
- Flexibility

---

# Example

interface Persistence {
    void save(ShoppingCart cart);
}

Implementations:
- SQLPersistence
- MongoPersistence
- FilePersistence

---

# Benefits
- Easy to extend
- No modification of old code
- Follows Open Closed Principle
- Better maintainability

---

# Interface vs Abstract Class

| Interface | Abstract Class |
|---|---|
| Contract | Partial implementation |
| Flexible | Shared base behavior |

---

# SOLID Principles Used
- SRP
- OCP
- DIP

---

# Real World Usage
Used in:
- Spring Boot
- Payment gateways
- Repository layer
- Enterprise applications

# Liskov Substitution Principle (LSP)

## What is LSP?
LSP states that child classes should be replaceable with parent classes without breaking application behavior.

---

# Banking Example

Different account types support different operations:

| Account Type | Deposit | Withdraw |
|---|---|
| Savings Account | Yes | Yes |
| Current Account | Yes | Yes |
| Fixed Term Account | Yes | No |

---

# Interfaces

## DepositOnlyAccount
Supports only deposits.

## WithdrawableAccount
Supports deposits and withdrawals.

---

# Why This Design?
- Prevents invalid operations
- Models real-world behavior correctly
- Avoids runtime exceptions
- Follows clean OOP design

---

# SOLID Principles Used
- LSP
- ISP
- SRP

---

# Advantages
- Scalable architecture
- Loose coupling
- Flexible system design
- Better maintainability

---

# Real World Usage
Used in:
- Banking systems
- Payment systems
- Enterprise applications