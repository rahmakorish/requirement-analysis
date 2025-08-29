# Requirement Analysis in Software Development:

focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements. Through a series of well-defined tasks, learners will create a detailed blueprint of the requirement analysis phase for a booking management system. This project simulates a real-world development scenario, emphasizing clarity, precision, and structure in defining requirements to set the stage for successful project execution.

# What is Requirement Analysis?
It’s the process of gathering, analyzing, and documenting what the customer needs from the software system. it consists of 4 steps:
1- Requirement Gathering

Talking to stakeholders (clients, users, business analysts),Collecting information through interviews, questionnaires, workshops, observations.

2-Requirement Categorization

Functional Requirements → What the system should do (features, operations), Non-functional Requirements → How the system should behave (performance, security, scalability).

3-Requirement Analysis & Validation

Checking for completeness, consistency, and feasibility, Resolving conflicts between stakeholders.

4-Documentation

Writing down requirements in a Software Requirement Specification (SRS) document, This serves as a contract between clients and the development team.

# Why is Requirement Analysis Important?
1.Prevents misunderstandings between client & developers.

2.Reduces costly changes later in development.

3.Provides a clear roadmap for design & coding.

# Key Activities in Requirement Analysis.
1. Requirement Gathering 📋

What it is: Collecting all possible needs and expectations of stakeholders (clients, end-users, managers, etc.).

How it’s done:

Interviews

Questionnaires

Observations

Brainstorming sessions

Reviewing existing systems

Goal: Get a raw list of what users want.

Example: For an online food delivery app, stakeholders might say:

"I want to order food online."

"Restaurants should update their menus easily."

"Payment should be secure."

2. Requirement Elicitation 🧑‍🤝‍🧑

What it is: Digging deeper into requirements to clarify, refine, and prioritize them.

How it’s done:

Workshops

Prototyping

Use cases & user stories

Focus groups

Goal: Move from “what people say they want” → to clear, detailed requirements.

Example:

Instead of just “secure payment,” elicitation discovers:

"We need multiple payment methods (credit card, PayPal, wallet)."

"Transactions must be encrypted with SSL."

3. Requirement Documentation 📝

What it is: Writing requirements in a structured format so everyone (developers, testers, clients) understands.

Common output: SRS (Software Requirement Specification) document.

What’s included:

Functional requirements (features).

Non-functional requirements (performance, usability, security).

Constraints (time, budget, technology).

Example:
The SRS for the food app might state:

FR1: The system shall allow users to track their order in real-time.

NFR1: The system shall handle up to 10,000 orders per minute.

4. Requirement Analysis and Modeling 🧩

What it is: Examining requirements for feasibility, conflicts, and completeness, then modeling them visually.

Tools used:

UML diagrams (Use case, Class, Sequence, Activity).

Data flow diagrams (DFD).

Entity Relationship Diagrams (ERD).

Goal: Turn requirements into a blueprint for system design.

Example:

A Use Case Diagram showing "User → Place Order → Restaurant receives order → Delivery assigned."

5. Requirement Validation ✅

What it is: Checking that requirements are correct, clear, consistent, and meet user needs.

How it’s done:

Requirement reviews (stakeholders + team).

Prototypes / mockups for confirmation.

Test cases prepared based on requirements.

Goal: Ensure “we are building the right product.”

Example:

Stakeholders test a prototype of the ordering screen and confirm it matches what they expect.

Ambiguous requirement like “system should be fast” is clarified to: “Response time ≤ 2 seconds.”

# Types of Requirements:
1. Functional Requirements (FR)

Define what the system should do (features, functions, behaviors).

Focus on specific actions or tasks the software must perform.

Usually written as "The system shall..." statements.

Examples (Food Delivery App):

The system shall allow users to create an account.

The system shall allow users to search restaurants by location.

The system shall send an order confirmation email.

2. Non-Functional Requirements (NFR)

Define how the system should work (quality attributes, constraints).

They don’t describe specific features but affect user experience and performance.

Examples:

Performance: The system shall process payments within 2 seconds.

Scalability: The system shall support 10,000 concurrent users.

Security: All transactions must be encrypted using SSL.

Usability: The app should be easy to use with no more than 3 steps to checkout.

# Use Case Diagrams
https://github.com/rahmakorish/requirement-analysis/blob/main/alx-booking-uc.png.png

A Use Case Diagram is a visual representation used in UML (Unified Modeling Language) to show how users (actors) interact with a system.
Why Use Case Diagrams are Important

Show system scope clearly.

Help developers & stakeholders understand requirements visually.

Identify who does what in the system.

Serve as a blueprint for functional requirements.

# Acceptance Criteria:
Acceptance Criteria are the conditions that a software product must meet to be accepted by the client, user, or stakeholder. They are written as clear, testable statements that define “done” for a requirement or user story.
1. Ensures Clear Understanding

Removes ambiguity by telling developers exactly what needs to be delivered.

Example: Instead of saying “The system should be fast”, the AC would say:

“The system should return search results within 2 seconds for up to 1,000 users.”

2. Acts as a Communication Tool

Bridges the gap between stakeholders, developers, and testers.

Everyone knows what “success” looks like for a feature.

3. Supports Testing & Validation

QA/testers use AC to create test cases.

If the software meets all AC → requirement is considered done & validated.

4. Prevents Scope Creep

AC sets boundaries for features.

Developers won’t add extra functionality that wasn’t agreed on.

5. Improves Customer Satisfaction

Stakeholders sign off on AC before development starts.

This ensures the delivered product meets actual business needs.
