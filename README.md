## **Python-GUI using Tkinter**

### **Project Title: CRMS - Cloth Rental Management System** 

- The Cloth Rental Management System (CRMS) is a Python-based application  designed to efficiently manage cloth rentals, user details, rental  amounts, and due dates. The system incorporates a graphical user interface (GUI) developed using the `tkinter` library and employs the `mysql.connector` library to connect to a MySQL database for seamless data storage and retrieval.

- *Schema for MySQL table creation:*

```mysql
CREATE table clothes(
    customerId varchar(10),
    idc varchar(10),
    mtype varchar(10),
    clothAmount int,
    clothSize varchar(5),
    deposit int,
    firstName varchar(12),
    lastName varchar(12),
    gender varchar(10),
    dateBorrowed varchar(15),
    dateOverDue varchar(15),
    dueDate varchar(15)
);
```
