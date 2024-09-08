<h1 align="center">Welcome to BulkyWeb! 📚</h1>
<h3 align="center">An Online Bookstore built with ASP.NET Core and Entity Framework</h3>
<h4 align="center">Build With</h4>
<p align="center">
    <!-- Languages & Frameworks -->
    <img src="https://img.shields.io/badge/C%23-00599C?style=for-the-badge&logo=csharp&logoColor=white" alt="C# Badge" />
    <img src="https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Badge" />
    <img src="https://img.shields.io/badge/Razor_Pages-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="Razor Pages Badge" />
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge" />
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap Badge" />
</p>
 
---

## About Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ravi-ramani-65a12017b/)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/RamaniRavi)
[![Website](https://img.shields.io/badge/Website-green?style=for-the-badge&logo=netlify)](https://ravi-ramani.netlify.app/)

---

## 📖 About BulkyWeb

BulkyWeb is an online bookstore where users can browse, buy, and review books. The application features two main roles: **Admin** and **User**.

- **Admin Role**: Admins can manage books and categories:
  - Add new books via `Content management > Product > Create New Product`
  - Update and delete existing books
  - Manage categories of books by adding, updating, and deleting categories through `Content management > Category`
  
- **User Role**: Users can:
  - View the list of available books on the homepage
  - See book details, including price, description, and availability
  - Add books to the shopping cart and proceed to checkout to purchase books

## 📸 Project Screenshots

### Home Page
![Home Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/homepage.png)

### Book Details Page
![Book Details Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/book-details.png)

### Category List Page
![Category List Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/category-list.png)

### Category Edit Page
![Category Edit Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/category-edit.png)

### Product List Page
![Product List Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/product-list.png)

### Create Product Page
![Create Product Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/create-product.png)

### Update Product Page
![Update Product Page](https://github.com/RamaniRavi/BulkyWeb/blob/main/Demo/update-product.png)

## 🛠️ Tech Stack

- **Languages & Frameworks:**
  - ![C#](https://img.shields.io/badge/-C%23-00599C?style=flat-square&logo=csharp)
  - ![ASP.NET](https://img.shields.io/badge/-ASP.NET-512BD4?style=flat-square&logo=.net)
  - ![Razor Pages](https://img.shields.io/badge/-Razor_Pages-512BD4?style=flat-square&logo=.net)

- **Database:**  
  - ![SQL Server](https://img.shields.io/badge/-SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server)

- **Tools:**  
  - ![Entity Framework](https://img.shields.io/badge/-Entity_Framework-512BD4?style=flat-square&logo=.net)
  - ![Visual Studio](https://img.shields.io/badge/-Visual_Studio-5C2D91?style=flat-square&logo=visualstudio)
  - ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)

---

## ⚙️ How to Set Up

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/BulkyWeb.git
    ```
2. Navigate to the project directory:
    ```bash
    cd BulkyWeb
    ```
3. Restore the dependencies:
    ```bash
    dotnet restore
    ```
4. Apply the database migrations:
    ```bash
    dotnet ef database update
    ```
5. Run the application:
    ```bash
    dotnet run
    ```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT License](LICENSE)
