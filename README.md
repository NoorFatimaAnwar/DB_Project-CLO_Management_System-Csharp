# 📌 CLO-Management-System-Csharp (C# & SQL Server)

## 📝 Description
The **CLO (Course Learning Outcome) Management System** is a desktop application built using **C# Windows Forms** and **SQL Server**.  
It was developed as part of a midterm lab exam and is connected to the provided **ProjectB** database without using Entity Framework.  

The system streamlines the **Outcome Based Education (OBE)** evaluation process by enabling instructors to manage and assess students against CLOs, rubrics, and assessments. It automates rubric-based evaluations and generates professional **PDF reports**.

---

## ✨ Key Features
- 👨‍🎓 Manage Students, CLOs, Rubrics, Assessments, and Rubric Levels  
- 📊 Record and evaluate student performance against CLOs  
- 🔢 Automatic calculation of marks based on rubric levels  
- 🖥️ Professional and user-friendly UI/UX with exception handling  
- 📄 Generate reports such as:  
  - CLO-wise class results  
  - Assessment-wise class results  
  - Additional customizable reports  

---

## 🛠️ Tech Stack
- **Language:** C#  
- **Framework:** .NET (Windows Forms)  
- **Database:** SQL Server (ProjectB schema)  
- **Reports:** PDF export (using iTextSharp or similar library)  

---

## ⚙️ Installation & Setup

### ✅ Prerequisites  
Make sure you have the following installed:  
- [Visual Studio (2019 or later)](https://visualstudio.microsoft.com/) with **.NET Desktop Development** workload  
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)  
- [SQL Server Management Studio (SSMS)](https://aka.ms/ssmsfullsetup)  
- `ProjectB` database (provided in scripts: [Download ProjectB DB](http://bit.ly/ProjectBDb))  

---

### 🚀 Steps to Run Locally  

#### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/CLO-Management-System.git
cd CLO-Management-System

