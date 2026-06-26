# Aligo C2 Framework

An educational software architecture project developed for the **Aligo Defensores Informáticos Hackathon**. 

The goal of this project is to design and implement a functional Command and Control (C2) system capable of coordinating remote endpoints from a central server within a closed, authorized laboratory environment.

---

## Conceptual Architecture

The project is divided into three distinct logical components:

1. **Agent (`/agent`):** The software designed to run on the target system. It is responsible for establishing a connection with the server, receiving instructions, executing them locally, and returning the output.
2. **Server (`/server`):** The central hub of the architecture. It listens for incoming connections from agents, manages the queue of pending tasks, and coordinates the flow of information.
3. **Operator Interface (`/interface`):** The control panel used by the operator to monitor connected agents, issue commands, and view execution results.

---

## Team Roles & Responsibilities

* **Pablo:** Project Management, System Planning & Pitch Design
* **Natalia:** Operator Interface & Feature Integration
* **Jose:** Agent Development & Endpoint Logic
* **Alex:** Server Development & Security Protocols
