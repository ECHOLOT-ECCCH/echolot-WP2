# ECHOLOT - C4 Management Model (Architecture Description)

This document describes the system architecture using the C4 model.

---

## C1 – System Context

**Goal:** Show the big picture – what the system is and how it interacts with the world.

### Description

- **Purpose**
  - Why the system exists
  - Key goals and expected outcomes

- **System Scope & Context**
  - Where the system fits (organization, ecosystem)
  - High-level environment overview

- **Actors (Users & External Systems)**
  - Users (roles and goals)
  - External systems (e.g. ECCCH Cloud, Europeana)

- **Inputs & Outputs**
  - Inputs: data sources, repositories
  - Outputs: data, services, user capabilities

- **Dependencies & Constraints**
  - External services
  - Standards and interoperability requirements

### Diagram

- System overview with:
  - Users
  - External systems
  - Data flows

---

## C2 – Containers

**Goal:** Show the high-level architecture (applications, services, databases).

### Description

Main building blocks of the system:
- Web applications
- APIs / backend services
- Databases
- External integrations

### For each container

- **Responsibility** – what it does
- **Inputs / Outputs**
- **Relationships** – interactions with other containers
- **Technology** (optional)

### Diagram

- Containers and their interactions (no internal details)

---

## C3 – Components

**Goal:** Show the internal structure of a single container.

### Description

Inside one selected container:
- Components (modules/services)
- Responsibilities
- Interfaces (APIs)
- Data flow between components

### For each component

- **Responsibility**
- **Inputs / Outputs**
- **Relationships** (within the container)
- **Technology** (optional)

### Diagram

- Components within a single container and their interactions

---

## C4 – Code (Classes)

**Goal:** Show implementation details.

### Description

- Classes
- Modules / packages
- Interfaces
- Key logic

### Artifacts

- Source code (primary)
- Code documentation
- UML diagrams (optional)

---

## Summary

- **C1:** Who uses the system and why  
- **C2:** What applications/services exist  
- **C3:** How a single application/service is structured  
- **C4:** How it is implemented in code  

