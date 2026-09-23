# School Payment Management System

## 1. Bounded Contexts and Entities

### Student Management
- Student
- Student ID
- Programme

### Payment Management
- Payment
- Payment Method
- Transaction

### Receipt Management
- Receipt
- Payment Confirmation
- Transaction ID

## 2. Context Map

```mermaid
flowchart LR
    A[Student Management] -->|Student Information| B[Payment Management]
    B -->|Payment Information| C[Receipt Management]
