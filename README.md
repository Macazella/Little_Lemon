Proyecto final Data Engineer Meta

https://github.com/Macazella/Little_Lemon

+----------------+          +----------------+
|   Employees    |          |   Bookings     |
+----------------+          +----------------+
| EmployeeID (PK)|<-------->| BookingID (PK) |
| Name           |          | TableNo        |
| Role           |          | GuestFirstName |
| Address        |          | GuestLastName  |
| Contact_Number |          | BookingSlot    |
| Email          |          | EmployeeID (FK)|
| Annual_Salary  |          +----------------+
+----------------+
                                  
                                  
+----------------+          +----------------+
|   Orders       |          |    Menus       |
+----------------+          +----------------+
| OrderID (PK)   |<-------->| MenuID (PK)    |
| TableNo        |          | ItemID (PK, FK)|
| MenuID (FK)    |          | Cuisine        |
| BookingID (FK) |          +----------------+
| BillAmount     |
| Quantity       |
+----------------+
                                  
+----------------+
|  MenuItems     |
+----------------+
| ItemID (PK)    |
| Name           |
| Type           |
| Price          |
+----------------+



