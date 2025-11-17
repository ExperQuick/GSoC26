# Scalable PyLabFlow for Multi-Researcher Collaboration

**Description:**  
Currently, PyLabFlow is designed for a single researcher using SQLite3.  
This project will make it scalable for multiple researchers by implementing a SQL server backend with concurrency control.

**Motivation:**  
In real-world research, multiple researchers often work on different aspects of the same project. A scalable database backend is required for collaboration.

**Skills Required:**  
- Python  
- SQL (PostgreSQL/MySQL)  
- Concurrency control  
- PyLabFlow internals  

**Deliverables:**  
- SQL server backend replacing SQLite3  
- Concurrency handling for multiple users  
- Testing of multi-user workflow  

**Suggested Milestones:**  
1. **SQL server integration:** Replace SQLite3 with PostgreSQL/MySQL backend.  
2. **Concurrency control:** Implement row-level locks or transactions for multi-user safety.  
3. **Workflow testing:** Validate multi-researcher workflow with sample components and experiments.  

**Mentors:** To be assigned

**References:**  
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)  
- [SQLite vs SQL Server](https://www.geeksforgeeks.org/difference-between-sqlite-and-mysql/)
