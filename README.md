# Airbnb Platform with some Improvements

## 📚 Introduction

My name is **Stefano Caramagno**, and I'm pleased to present this repository containing a project on creation of **Airbnb platform with some improvements**. <br>
This project was completed as part of a **Databases and Web Programming** course during my **Bachelor's Degree in Computer Science and Engineering** at the **University of Catania**.

## ✨ Features 

- **Responsive UI Design**: Ensures an adaptable interface optimized for both web and desktop screens.   
- **Software Architecture**: Implements the MVC pattern for modular and maintainable development.  
- **Database Management**: Stores and manages data efficiently through a structured database system.  
- **Database Abstraction Layer**: Leverages ORM for efficient interaction with the database.  
- **RESTful API Integration**: Offers scalable APIs following REST principles for client-server communication.  
- **Secure User Authentication**: Implements a login and registration system for users.  
- **User Account Access**: Restricts users to their data, preventing unauthorized viewing or modification.  
- **Property Listings Browsing**: Allows users to explore properties by filtering accommodation types.  
- **Detailed Property Pages**: Provides users with dedicated pages for each property.
- **Favorite Properties**: Enables users to mark properties as favorites for quick reference.  
- **Remove Favorite Properties**: Gives users the option to unmark properties from their favorites list.  
- **Google Maps Integration**: Displays users view an interactive map using the Google Maps API.  
- **Weather Forecast**: Allows users to check the weather for a chosen city and date via the OpenWeatherMap API.  
- **Holiday Calendar**: Lets users view holidays for a selected city and year using the Calendarific API.  
- **Spotify Artist Search**: Allows users to find artists and see their top songs via the Spotify API.  
- **Add Favorite Music Tracks**: Lets users save an artist’s top songs to their favorite list.  
- **Remove Favorite Music Tracks**: Enables users to delete songs from their favorite tracks list.  

## 🛠️ Tech Stack

- **Frontend Development**:  
  - **HTML** for structuring and organizing web content.  
  - **CSS** for styling, layout, and responsive design.  
  - **JavaScript** for handling user interactions and making requests to APIs.  
- **Backend Development**:  
  - **PHP** for implementing server-side logic and processing data.  
  - **Laravel** for creating and managing API endpoints to handle client requests.  
- **Database Management**: MySQL for structured and efficient data storage.    
- **Dependency Management**: Composer for installing and managing project dependencies.  
- **IDE**: Visual Studio Code for development and debugging.  
- **Version Control**: Git for tracking changes and managing project versions.  
- **Repository Hosting**: GitHub for storing, sharing, and maintaining the project repository.  

## 🚀 Getting Started

### Prerequisites

Ensure you have the following tools installed on your system before proceeding:

- **PHP**: Version 8.0 or later, required to run the application.  
- **Composer**: Used to install required dependencies. 
- **XAMPP**: Required to provide a local server environment with MySQL and Apache.  
- **IDE**: Required to read and understand code efficiently.  
- **Git**: Used to clone the repository.

### Installation Steps

1. **Clone the Repository**

   To download the repository and navigate to its directory:

   ```sh
   git clone https://github.com/stefanocaramagno/Airbnb_clone_with_improvements.git
   ```

2. **Move to htdocs**

   To move the project folder to the `htdocs` directory:

      - **Windows**  

         ```sh
         move Airbnb_clone_with_improvements C:\xampp\htdocs\
         ```

      - **Linux**  

         ```sh
         mv Airbnb_clone_with_improvements /opt/lampp/htdocs/
         ```

      - **macOS** 

         ```sh
         mv Airbnb_clone_with_improvements /opt/lampp/htdocs/
         ```

3. **Start MySQL Server**

   To launch the MySQL server using XAMPP:

      - **Windows**

         ```sh
         C:\xampp\mysql\bin\mysqld --console
         ```

      - **Linux**

         ```sh
         sudo /opt/lampp/bin/mysql.server start
         ```

      - **macOS**

         ```sh
         sudo /opt/lampp/bin/mysql.server start
         ```

4. **Access MySQL CLI**

   To log into MySQL and access the command-line interface:

      - **Windows**

         ```sh
         C:\xampp\mysql\bin\mysql -u root -p
         ```

      - **Linux**

         ```sh
         /opt/lampp/bin/mysql -u root -p
         ```

      - **macOS**

         ```sh
         /opt/lampp/bin/mysql -u root -p
         ```

5. **Create the Database**

   To create a new database:

   ```sh
   CREATE DATABASE airbnbclone_database;
   ```

6. **Configure Database Connection**

   Update the database configuration in the `.env` file, located in the project root.
   Replace `your_username` and `your_password` with your MySQL credentials:

   ```sh
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=airbnbclone_database
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   ```

7. **Install Dependencies**

   To install all required dependencies:

   ```sh
   composer install
   ```

### Running the Application

1. **Start the Server**

   To start the application:

   - **Windows**  

      ```sh
      C:\xampp\apache\bin\httpd.exe
      ```

   - **Linux**

      ```sh
      sudo /opt/lampp/lampp startapache
      ```

   - **macOS**

      ```sh
      sudo /opt/lampp/lampp startapache
      ```

2. **Access the Application**

   To open the application in your browser:

   ```
   http://localhost/Airbnb_clone_with_improvements/public
   ```

   This will take you to the homepage of the Airbnb Platform some Improvements.

##  🌐 Connect with Me

Feel free to explore my professional journey, check out my projects, or get in touch through the following platforms:

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stefano.caramagno@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%2300A36C?style=for-the-badge&logo=buffer&logoColor=white)](https://stefanocaramagno.vercel.app)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stefanocaramagno)
[![Indeed](https://img.shields.io/badge/Indeed-%2300A4CC?style=for-the-badge&logo=indeed&logoColor=white)](https://profile.indeed.com/p/stefanoc-4cl1mmq)
[![GitHub](https://img.shields.io/badge/GitHub-%232F2F2F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stefanocaramagno)
[![YouTube](https://img.shields.io/badge/YouTube-D14836?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@stefanocaramagno)

## ⚖️ License

© **Stefano Caramagno**

**Personal and Educational Use Only**  
All content in this repository is provided for personal and educational purposes only. <br>
Unauthorized actions without explicit permission from the author are prohibited, including but not limited to:

- **Commercial Use**: Using any part of the content for commercial purposes.
- **Distribution**: Sharing or distributing the content to third parties.
- **Modification**: Altering, transforming, or building upon the content.
- **Resale**: Selling or licensing the content or any derivatives.

For permissions beyond the scope of this license, please contact the author.

**Disclaimer**  
The content is provided "*as is*" without warranty of any kind, express or implied. <br>
The author shall not be liable for any claims, damages, or other liabilities arising from its use.