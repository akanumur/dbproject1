GROUP NAME : PAWSitively PURRfect
GROUP MEMBERS : Akshata Kanumuri , Leanne Peterson , Phyllis Jones , Lance Rhyne , Serah Haley


PROJECT DESCRIPTION :
We are a group of pet technicians creating a prototype relational database system using MySQL and MySQL Workbench for veterinarian, Dr. Patel, in Charlotte, North Carolina. Dr. Patel has an existing record of customers that we will use as the starting point for our project. Our system will cater to dog and cat owners that need assistance with pet care. The services will include: boarding, pet visitation, walking, feeding, day care, bathing, shopping, and medication administration. Our database will have the capacity to enter new information, edit existing information, and generate reports for Dr. Patel. This program will be available on the web for customers to request services


EXECUTIVE SUMMARY AND SCOPE :
Five PAWSitively PURRfect technicians will design, develop, and implement a relational database prototype using MySQL to manage pet services to clients in North Carolina. The services will include: boarding, visitation, walking, feeding, day care, bathing, shopping, and medication administration with a 10% discount for teachers. Information will be stored in independent relational tables titled: Pets, Services, Customers, Orders, Technicians, College and Students. The production of the database will be developed using four dated deliverables: 5/25/18, 6/11/18, 6/18/18 and 6/25/18, using a collaborative approach. The final date of 6/25/18 is the project completion date. The database will be constructed for veterinarian, Dr. William Patel, and will use existing client data for the prototype. New clients will be added after the database is completed and implemented. No cost is associated with using the free MySQL community server


BUSSINESS RULES :
> Customer Business Rules 
•	A single customer can have many pets 
•	A customer can be zero to one teacher
•	A customer can be zero to one student
•	Customers can be technicians and technicians can be customers
•	A customer can place zero to many orders
•	A customer can be specialized into a teacher, a college student and/or a technician 

> Pet Business Rules 
•	Each pet belongs to a single customer ( As Co-Parenting is not allowed )
•	A pet can have zero to many orders
•	A pet can belong to zero to one pet type

> Technician Business Rules 
•	Technician can be a customer and customer can be a technician
•	A technician can do one to many services

> Other Business Rules 
•	A service can have many technicians
•	There is a many to many relationship between services and orders

> Teacher Business Rules 
•	Teachers are the only customers who are eligible to get a discount

EERD and SCHEMA :
The EERD designed for the systems consists of 9 entities namely Customers, College_Students , Pets , Pet_Type , Technician , Teacher , Order , Order_has_Services, Services. Every entity is represented as Table in Database and they are associated with other entities which is shown in EERD. The notation 1 and M defines the participation constrains of the entity. We implemented specialization technique for Customer entity which has Technician, Teacher and College_Student. Everyone one of the sub entities share the same Primary Key of the parent entity. Each entity has a Primary Key associated with them which is unique attribute.
Attaching (Schema.jpg and EERD.pdf)


DATA DICTIONARY :
Information word reference is set of records which shows Meta (information of information). It speaks to the documents display, tables, relations, proprietor send and so forth introduce in the undertaking


VIEWS:
Documentation for VIEWS attached (Views.docx)


STORED PROCEDURES :
Documentation for STORED PROCEDURES attached (Stored Procedure.docx)

TRIGGER :
Documentation for TRIGGER attached (Trigger.docx)

TURN IN SQL DUMP WITH DATA:
PAWStively PURRfectly.sql
