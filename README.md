# 🏥 UKZN 3rd Year Project: Townbush Pharmacy Website

A web-based application developed as part of the **University of KwaZulu-Natal (UKZN) 3rd Year Software Development Project**.  
The project focuses on creating a **pharmacy website** with user registration, authentication, and prescription management features — built using **ASP.NET Web Forms**.

---

## 💡 About the Project

The **Townbush Pharmacy Website** was designed to provide customers with a convenient digital experience for:
- Browsing pharmacy products
- Creating user accounts and logging in securely
- Managing prescriptions and orders
- Enhancing user accessibility with a mobile-first design

---

## ⚙️ Project Status & Setup

> **Important Note:**  
> This project was originally linked to a **university-hosted MS SQL Server** database.  
> The database connection is **no longer active**, which means login and registration features will not function until a local database is configured.

**To run locally:**
1. Create a new database in **SQL Server 2019**.  
2. Update the connection string in `Web.config`:
   ```xml
   <connectionStrings>
       <add name="PharmacyDB"
            connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=YOUR_DATABASE_NAME;Integrated Security=True"
            providerName="System.Data.SqlClient" />
   </connectionStrings>
3. Build and run the project in Visual Studio.

### Screenshot

![](./Pictures/project-1.jpg)
![](./Pictures/project%20login.png)
![](./Pictures/project%20register%20new%20user.png)



### Built with

-Semantic HTML5 markup
-CSS custom properties for styling
-ASP.NET Web Forms Framework
-JavaScript for interactivity
-Mobile-first workflow for responsive design
-Visual Studio IDE

## Authors
-Mnqobi Thusi, 
-Mohammed Aqeel Ismail, 
-Tulliyah Pakarri, 
-Umar-Farooq, 
-Trineh
