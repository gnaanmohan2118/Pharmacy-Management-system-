# Pharmacy-Management-system-

1. Insurance(Insurance ID, Company Name, Start Date, End Date, Co-Insurance)

Insurance ID -> Company Name, Start Date, End Date, Co-Insurance

-------------------------------------------------------------------------------------------
2. Customer(SSN, First Name, Last Name, Phone, Gender, Address, Dateof Birth, Insurance ID)

SSN -> First Name, Last Name, Phone, Gender, Address, Date of Birth, Insurance ID

-------------------------------------------------------------------------------------------
3. Prescription(Prescription ID, SSN, Doctor ID, Prescribed Date)

Prescription ID -> SSN, Doctor ID, Prescribed Date

-------------------------------------------------------------------------------------------
4. Prescribed_Drugs(Prescription ID, Drug Name, Prescribed Quantity, Refill Limit)

Prescription ID, Drug Name -> Prescribed Quantity, Refill Limit

-------------------------------------------------------------------------------------------
5. Order(Order ID, Prescriptio ID, Employee ID, Order Date)

Order ID -> Prescriptio ID, Employee ID, Order Date

-------------------------------------------------------------------------------------------
6. Ordered Drugs(Order ID, Dug Name, Batch Number, Ordered Quantity, Price)

Order ID, Dug Name, Batch Number -> Ordered Quantity, Price

-------------------------------------------------------------------------------------------
7. Bill(Order ID, CustomerSSN, Total Amount, Customer Payment, Insurance Payment)

Order ID, CustomerSSN -> Total Amount, Customer Payment, Insurance Payment

-------------------------------------------------------------------------------------------
8. Employee(Employee ID, SSN, First Name, Last Name, Start Date, End Date, Role, Salary, Phone Number, Date of Birth)

Employee ID -> SSN, First Name, Last Name, Start Date, End Date, Role, Salary, Phone Number, Date of Birth

-------------------------------------------------------------------------------------------
9. Employee_Notification(Employee ID, Notification ID)

All Keys.

-------------------------------------------------------------------------------------------
10. Notification(Notification ID, Type, Message)

Notification ID -> Type, Message

-------------------------------------------------------------------------------------------
11. Employee_Disposed_Drugs(Employee ID, Drug Name, Batch Number, Disposal Date)

All Keys.

-------------------------------------------------------------------------------------------
12. Disposed Drugs(Drug Name, Batch Number, Quantity, Company)

Drug Name, Batch Number -> Quantity, Company

-------------------------------------------------------------------------------------------
13. Medicine(Drug Name, Batch Number, Medicine Type, Manufacturer, Stock Quantity, Expiry Date, Price)

Drug Name, Batch Number -> Medicine Type, Manufacturer, Stock Quantity, Expiry Date, Price

-------------------------------------------------------------------------------------------
