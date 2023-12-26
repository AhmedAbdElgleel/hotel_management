# Hotel Management System (HMS) - Software Requirements Specifications (SRS)

## Table of Contents
1. [Introduction](#introduction)
    - [Purpose](#purpose)
    - [Problem Definition](#problem-definition)
    - [Scope](#scope)
    - [Glossary](#glossary)
2. [System Requirements](#system-requirements)
    - [Functional Requirements](#functional-requirements)
    - [Non-Functional Requirements](#non-functional-requirements)
    - [Constraints](#constraints)
    - [System Users](#system-users)
3. [System Architecture](#system-architecture)
    - [Presentation Layer](#presentation-layer)
    - [Application Layer](#application-layer)
    - [Data Layer (Database)](#data-layer-database)
    - [Security Layer](#security-layer)
    - [Admin Console](#admin-console)
    - [Infrastructure Layer](#infrastructure-layer)
4. [Software Requirements and Specifications](#software-requirements-and-specifications)
    - [System Overview](#system-overview)
    - [Login and Registration](#login-and-registration)
    - [Reservation](#reservation)
    - [Show Available Offers](#show-available-offers)
    - [Add Offers on Reservation](#add-offers-on-reservation)
    - [Show Requests](#show-requests)
    - [Payment Methods](#payment-methods)
    - [Add Rates](#add-rates)
    - [Checkout](#checkout)
5. [Diagrams](#diagrams)

6. [Future Work](#future-work)

## Introduction
### Purpose
Hotel Management System (HMS) is a crucial software application designed to streamline reservation, check-in/check-out, and administrative processes in the hotel industry. This document outlines the software requirements and specifications for the development of HMS.

#### Key Objectives
- Efficient Operations
- Enhanced Guest Experience
- Smart Resource Use
- Financial Management
- Time Savings

### Problem Definition
A problem in a Hotel Management System refers to any obstacle disrupting smooth operation, affecting reservations, check-ins, or data accuracy. These challenges may include software glitches, user interface difficulties, security concerns, or integration issues.

### Scope
The scope involves transitioning from traditional paper-based workflows to a sophisticated software application. This digital transformation aims to enhance efficiency, reduce costs, and save valuable time, resulting in increased productivity and a more competitive business environment.

### Glossary
- HMS: Hotel Management System
- SW: Software
- DB: Database

## System Requirements
### Functional Requirements
- **Performance:** The system should be responsive and efficient.
- **Reliability:** It must operate consistently and dependably.
- **Security:** Ensure protection against unauthorized access or tampering.
- **Maintenance:** Keep maintenance requirements low.
- **Availability:** The system should be available 24/7, with scheduled maintenance communicated in advance.
- **Usability:** The user interface should be intuitive, requiring minimal training for hotel staff.

### Non-Functional Requirements
#### Constraints
- **Budget Constraints:** Adhere to a predetermined budget for development, deployment, and maintenance.
- **Resource Limitations:**
  - Human Resources: Limited availability of skilled personnel may impact project timelines.
  - Time Constraints: Limitations may affect the speed of development, testing, and deployment.

### System Users
- Administrator
- Manager
- Customers
  - Housekeeper
  - Receptionist

## System Architecture
### Presentation Layer
The presentation layer consists of GUI elements handling user input, displaying information, and communicating with the application layer.

### Application Layer
The application layer contains core logic, processing user input, managing data, and interacting with the data layer.

### Data Layer (Database)
The data layer stores and retrieves data related to users, reservations, offers, rates, and other entities.

### Security Layer
Ensures security through authentication, authorization, and encryption mechanisms.

### Admin Console
An administrative console allows authorized personnel to manage system configurations.

### Infrastructure Layer
Includes hardware and software components supporting the desktop application.

## Software Requirements and Specifications
### System Overview
[Provide an overview of the system]

### Login and Registration
- Secure login for staff and guests.
- Staff and guest registration with necessary information.
- Authentication for staff and guests.

### Reservation
- Guests can reserve rooms and other services.
- Selection of check-in and check-out dates.
- Choosing room types and additional services.
- Viewing and modifying reservations.

### Show Available Offers
- Guests can view promotional offers.
- Displaying a list of current offers with details.
- Allowing guests to apply offers to reservations.

### Add Offers on Reservation
- Hotel staff can associate offers with guest reservations.
- Linking offers with specific reservations.
- Validating and applying offers during the reservation process.

### Show Requests
- Hotel staff and guests can view reservation request status.
- Displaying a history of reservation requests.

### Payment Methods
- Support multiple payment methods for settling bills.
- Displaying available payment options during checkout.

### Add Rates
- Associating rates with room types and services.

### Checkout
- Guests can review reservations, apply offers, and complete the checkout process.
- Displaying a summary of reservation details.
- Applying selected offers and discounts.
- Initiating and completing the checkout process.

## Diagrams
- You will find the diagrams in SRS

## Future Work
[Outline potential future enhancements and features for the Hotel Management System]
