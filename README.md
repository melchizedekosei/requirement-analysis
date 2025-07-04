# Requirement Analysis in Software Development
This repository is for learning and practicing how to understand what software needs to do before we build it.
It will contain examples, templates, and notes about requirement analysis.
# Requirement Analysis in Software Development

This repository is for learning and practicing how to understand what software needs to do before we build it.
It will contain examples, templates, and notes about requirement analysis.

## What is Requirement Analysis?

Requirement Analysis is like making a shopping list before going to the supermarket 🛒. It's when we:

- Talk to people to understand what they want in the software (like asking Mom what groceries we need)
- Write down all the important things the software must do (like listing milk, eggs, and bread)
- Organize the requirements so programmers understand (like grouping frozen foods together)

### Why is it important? 🌟
Just like you wouldn't build a treehouse without a plan, we don't build software without requirements because:

1. It helps avoid mistakes (like forgetting the milk!)
2. Saves time and money
3. Makes sure everyone agrees on what to build
4. Helps testers know what to check later

It's one of the first and most important steps when making new software!

## What is Requirement Analysis?

Requirement Analysis is the critical first phase in the Software Development Life Cycle (SDLC) where developers and stakeholders identify, analyze, document, and validate the needs and constraints of a software system. It serves as the foundation for all subsequent development stages.

### Key Aspects of Requirement Analysis:

1. **Elicitation**: Gathering requirements from stakeholders through interviews, surveys, workshops, and observation
2. **Documentation**: Creating clear, unambiguous specifications (typically in SRS documents or user stories)
3. **Analysis**: Evaluating requirements for completeness, consistency, and feasibility
4. **Validation**: Ensuring requirements accurately represent stakeholder needs
5. **Management**: Tracking changes and maintaining requirement traceability

### Importance in SDLC:

- **Reduces project risks** by identifying potential issues early
- **Prevents costly rework** by establishing clear expectations
- **Aligns stakeholders** around a common understanding
- **Guides design decisions** and architecture planning
- **Forms the basis for testing** and quality assurance
- **Improves estimation accuracy** for timelines and resources

### Types of Requirements:

1. **Functional Requirements**: What the system should do (features, behaviors)
2. **Non-Functional Requirements**: How the system should perform (security, scalability, usability)
3. **Business Requirements**: High-level organizational goals
4. **User Requirements**: End-user needs and expectations
5. **System Requirements**: Technical specifications and constraints

Effective requirement analysis bridges the gap between business objectives and technical implementation, ensuring the final product delivers real value to its users.

## What is Requirement Analysis?

Requirement Analysis is the critical first phase in the Software Development Life Cycle (SDLC) where developers and stakeholders identify, analyze, document, and validate the needs and constraints of a software system. It serves as the foundation for all subsequent development stages.

### Key Aspects of Requirement Analysis:

1. **Elicitation**: Gathering requirements from stakeholders through interviews, surveys, workshops, and observation
2. **Documentation**: Creating clear, unambiguous specifications (typically in SRS documents or user stories)
3. **Analysis**: Evaluating requirements for completeness, consistency, and feasibility
4. **Validation**: Ensuring requirements accurately represent stakeholder needs
5. **Management**: Tracking changes and maintaining requirement traceability

### Importance in SDLC:

- **Reduces project risks** by identifying potential issues early
- **Prevents costly rework** by establishing clear expectations
- **Aligns stakeholders** around a common understanding
- **Guides design decisions** and architecture planning
- **Forms the basis for testing** and quality assurance
- **Improves estimation accuracy** for timelines and resources

### Types of Requirements:

1. **Functional Requirements**: What the system should do (features, behaviors)
2. **Non-Functional Requirements**: How the system should perform (security, scalability, usability)
3. **Business Requirements**: High-level organizational goals
4. **User Requirements**: End-user needs and expectations
5. **System Requirements**: Technical specifications and constraints

   ## Why is Requirement Analysis Important?

Requirement Analysis is the foundation of successful software development. Here’s why it’s indispensable:

### 1. **Prevents Costly Mistakes**
   - Identifies ambiguities and contradictions early, avoiding expensive rework later.
   - Studies show that fixing errors in requirements is **100x cheaper** than fixing them in production.

### 2. **Aligns Stakeholders**
   - Bridges gaps between business teams, developers, and end-users.
   - Ensures everyone shares the same vision of the final product.

### 3. **Guides Development**
   - Provides a clear roadmap for designers, developers, and testers.
   - Helps prioritize features based on business value and technical feasibility.

### 4. **Reduces Project Risks**
   - Minimizes scope creep by defining boundaries upfront.
   - Improves estimation accuracy for timelines, budgets, and resources.

### 5. **Ensures Quality**
   - Forms the basis for testing criteria and acceptance standards.
   - Addresses non-functional needs (performance, security, usability) from the start.

### 6. **Facilitates Compliance**
   - Documents regulatory/legal requirements for audit trails.
   - Critical for industries like healthcare (HIPAA) or finance (GDPR).

### 7. **Improves User Satisfaction**
   - Focuses on solving real user problems rather than assumed needs.
   - Increases adoption rates by delivering expected functionality.

> **Quote**: *"The hardest single part of building a software system is deciding what to build."* — Fred Brooks, Author of *The Mythical Man-Month*.

Without proper requirement analysis, projects risk:
- Budget overruns  
- Missed deadlines  
- Poor user adoption  
- Complete failure to meet business goals


## Key Activities in Requirement Analysis

Requirement Analysis involves five core activities that transform stakeholder needs into actionable specifications:

### 1. Requirement Gathering
- Identify all stakeholders (clients, users, regulators)
- Collect raw needs through:
  - Interviews and workshops
  - Surveys/questionnaires
  - Market research
  - Existing system documentation
- Capture both explicit and implicit requirements

### 2. Requirement Elicitation
- Extract deep insights using techniques:
  - User stories and use cases
  - Brainstorming sessions
  - Observation (job shadowing)
  - Prototyping
  - Scenario analysis
- Resolve conflicts between stakeholder groups
- Discover unstated expectations

### 3. Requirement Documentation
- Create structured artifacts:
  - Software Requirements Specification (SRS)
  - User stories (for Agile)
  - Process flows and diagrams
- Follow standards like IEEE 830 for SRS
- Include:
  - Functional requirements
  - Non-functional requirements
  - Constraints and assumptions

### 4. Requirement Analysis and Modeling
- Evaluate requirements for:
  - Completeness (no missing pieces)
  - Consistency (no contradictions)
  - Feasibility (technical/budget constraints)
- Use modeling techniques:
  - UML diagrams (use case, activity)
  - Data flow diagrams
  - Entity-relationship diagrams
- Prioritize requirements (MoSCoW method)

### 5. Requirement Validation
- Verify requirements with stakeholders:
  - Formal reviews/inspections
  - Prototype demonstrations
  - Sign-off meetings
- Check alignment with:
  - Business objectives
  - User needs
  - Technical capabilities
- Establish traceability matrices

## Types of Requirements

### 1. Functional Requirements (What the system DOES)
*Define the specific behaviors and features of the system.*

**Examples for Booking Management:**
- **User Authentication:**  
  - The system shall allow users to register/login using email and password.  
  - The system shall enable password recovery via email.  

- **Booking Management:**  
  - The system shall allow users to search for available rooms by date range and room type.  
  - The system shall display real-time availability status of rooms.  

- **Payment Processing:**  
  - The system shall integrate with PayPal/Stripe for credit card payments.  
  - The system shall generate invoices upon successful payment.  

- **Admin Functions:**  
  - The system shall allow admins to override bookings in exceptional cases.  
  - The system shall send confirmation emails to users after booking.  

---

### 2. Non-Functional Requirements (How the system PERFORMS)  
*Define the quality attributes and constraints of the system.*

**Examples for Booking Management:**  

- **Performance:**  
  - The system shall load search results within <2 seconds for 100 concurrent users.  

- **Security:**  
  - All payment transactions shall use TLS 1.2+ encryption.  
  - User passwords shall be stored using bcrypt hashing.  

- **Availability:**  
  - The system shall maintain 99.9% uptime during business hours (8AM-10PM).  

- **Usability:**  
  - The booking process shall be completable in ≤5 steps for first-time users.  

- **Compliance:**  
  - The system shall adhere to GDPR for EU customer data storage.  

- **Scalability:**  
  - The system shall handle 50% increased load during holiday seasons.
 
    ## Use Case Diagrams

### What are Use Case Diagrams?
Use Case Diagrams are visual representations of system functionality from a user's perspective. They show:
- **Actors**: Roles interacting with the system (users, external systems)
- **Use Cases**: Specific goals/actions the system performs
- **Relationships**: How actors interact with each use case

### Benefits in Requirement Analysis
- Clarify system scope and boundaries  
- Identify all user roles and their needs  
- Reveal missing requirements early  
- Serve as communication tools between stakeholders  

### Booking System Use Case Diagram
![Booking System Use Cases](alx-booking-uc.png)  
*(Click image to enlarge)*

**Key Elements Shown:**
1. **Actors**:
   - Guest (unauthenticated user)
   - Registered User
   - Admin
   - Payment Gateway (external system)

2. **Core Use Cases**:
   - Search Available Rooms
   - Book Room
   - Process Payment
   - Manage Bookings (Admin)

3. **Relationships**:
   - Extends: Specialized flows (e.g., "Apply Discount")
   - Includes: Mandatory sub-tasks (e.g., "Verify Payment") 
