# 🍔 Object-Oriented Programming Project: Foods Ordering System

## 📌 Project Summary
* **Course:** Object-Oriented Programming (SEC 02 | Sem 2, 2023/2024)
* **Academic Institution:** Universiti Teknologi Malaysia (UTM)
* **Core Technologies:** Java SE, Strict Object-Oriented Design Principles (SOLID), Stream Serialization (`orders.txt`, `users.txt`), Component-Driven Interface Logic.
* **Objective:** To architect an end-to-end multi-user food ordering and inventory lifecycle platform that transitions manual bakery/burger operations into a high-integrity, automated digital ecosystem.

The **Foods Ordering System** is a software framework engineered in Java that models the computational workflow of modern hospitality businesses. Shifting entirely away from simple procedural scripting, this application is constructed using rigorous OOP paradigms, including private encapsulation, polymorphism, state modeling, and abstract data inheritance boundaries. 

The application deploys a secure dual-interface environment:
1. **Interactive Customer Hub:** Allows customers to browse dynamic menu indices, construct multi-item orders, choose payment workflows (Card/Cash simulation paths), track real-time receipt generation, and write processed receipts to flat-file storage databases (`orders.txt`).
2. **Administrative Management Hub:** Grants operators secure backend controls to audit ongoing transactions, inspect consumer velocity, and scale menu inventories dynamically.

---

## 🛠️ System Architecture & Mechanics Deployed
* **State Preservation & Persistence Layer**: Manages file stream serialization to maintain consistent transactional history logs (`orders.txt`) and user profiles (`users.txt`) across application lifecycles.
* **Polymorphic Billing Framework**: Employs structural abstractions to handle dynamic billing pathways, adapting system behaviors automatically based on selected checkout configurations (Card validations vs. Cash logic checks).
* **Decoupled Verification Subsystems**: Enforces strong data isolation boundaries during registration and login stages to prevent unauthenticated access or state leakage across user environments.

---

## 🧠 Technical Reflection: Mastering Java Architecture & Component Design

### 1. What I Learnt
* Developing the *Foods Ordering System* in Java marked a major milestone in my growth as a programmer. It forced me to move beyond using object classes as simple data structures and start treating them as independent, interactive components. 

* Before building this system, concepts like **inheritance, polymorphism, and interface abstraction** felt purely theoretical. Designing a system that allows different entities—like customers and administrators—to share core login logic while executing completely separate runtime dashboards proved why clean inheritance hierarchies are necessary.

* The most challenging technical hurdle was managing real-time data calculations (such as tax additions, discount tiers, and multi-item totals) and writing that data cleanly to flat-file streams (`orders.txt`). 

 Structuring data flow so that individual class instances can write to a shared, append-only ledger file without corrupting the file's structure taught me how to write predictable, defensive code. This foundational experience directly shaped the approach I use today when structuring multi-tier web layers and database schemas.


The modular structures built into this food ordering terminal—where an individual order item forms a self-contained object that serializes into a text string—directly mirror how modern distributed systems handle streaming analytics data. Whether a script is transforming a single local transaction array inside a Java app or managing millions of live operational records inside **Microsoft Azure**, the core engineering goal remains identical: **data must be strictly validated, typed, and isolated to ensure complete pipeline reliability.**

This project successfully bridged the gap between academic programming syntax and true enterprise-ready software design. It proved that system reliability starts by building high-integrity code components that handle unpredictable human inputs gracefully and protect data state boundaries at every stage of execution.
