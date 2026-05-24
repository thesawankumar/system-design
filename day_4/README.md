# UML Diagram

## What is UML?
UML (Unified Modeling Language) is a visual language used to design and represent software systems.

---

# Why UML?
- Better software planning
- Improves communication
- Helps in interviews
- Reduces development mistakes

---

# Types of UML Diagrams

## Structural Diagrams
- Class Diagram
- Object Diagram
- Component Diagram

## Behavioral Diagrams
- Sequence Diagram
- Activity Diagram
- Use Case Diagram

---

# Class Diagram

Represents:
- Classes
- Attributes
- Methods
- Relationships

Example:

+----------------------+
|         Car          |
+----------------------+
| - brand : String     |
| - speed : int        |
+----------------------+
| + start()            |
| + stop()             |
+----------------------+

---

# UML Relationships

## Association
Teacher -------- Student

## Inheritance
Vehicle ← Car

## Aggregation
Department ◇---- Teacher

## Composition
House ◆---- Room

---

# Sequence Diagram Example

User → Frontend → Backend → Database

---

# Interview Questions
1. What is UML?
2. Difference between aggregation and composition?
3. Difference between class and sequence diagram?
4. Why is UML important?

---

# Real World Usage
Used in software architecture, LLD interviews, and backend system planning.


# Representing Class Structure and Associations in UML

## What is Class Structure?
Class structure represents:
- Attributes
- Methods
- Visibility
- Internal design of class

---

# Example

+----------------------+
|         Car          |
+----------------------+
| - brand : String     |
| - speed : int        |
+----------------------+
| + start()            |
| + stop()             |
+----------------------+

---

# What is Association?
Association represents relationship between classes.

Example:
Customer -------- Order

---

# Types of Associations

## Simple Association
Teacher -------- Student

## Bidirectional Association
Customer <-------> Order

## Aggregation
Department ◇---- Teacher

## Composition
House ◆---- Room

## Inheritance
Vehicle ← Car

---

# Multiplicity

1 -------- *
One-to-many relationship

Example:
One customer can place many orders.

---

# Why Important?
- Helps in LLD interviews
- Improves OOP understanding
- Used in real-world software design

---

# Interview Questions
1. Difference between aggregation and composition?
2. What is multiplicity?
3. What is association in UML?



# Sequence Diagram

## What is Sequence Diagram?
A Sequence Diagram is a UML behavioral diagram used to represent interaction between objects over time.

---

# Why Use Sequence Diagram?
- Understand request flow
- Visualize API communication
- Design backend interactions
- Improve system understanding

---

# Components
- Actor
- Lifeline
- Message
- Activation Bar
- Return Message

---

# Login Flow Example

User → Frontend → Backend → Database

---

# E-Commerce Order Flow

User → Order Service → Inventory Service → Payment Service

---

# Sequence Diagram vs Class Diagram

| Class Diagram | Sequence Diagram |
|---|---|
| Static structure | Dynamic behavior |
| Classes | Communication flow |

---

# Real World Usage
Used in:
- Backend systems
- Microservices
- API architecture
- System design interviews

---

# Interview Questions
1. What is Sequence Diagram?
2. Difference between synchronous and asynchronous messages?
3. Difference between sequence and activity diagrams?