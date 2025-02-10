# 🍽️ Food Ordering System

A modern food ordering system built with Vue.js and Spring Boot.

## 🚀 Features

- 🔐 User Authentication & Authorization
- 🍕 Menu Management
- 🛒 Order Processing
- 💬 Customer Reviews
- 📊 Admin Dashboard
- 🏪 Restaurant Management

## 🛠️ Tech Stack

- Frontend:
  - Vue.js 2.6.14
  - Element UI
  - SCSS
  - Axios

- Backend:
  - Spring Boot 2.2.2
  - MySQL
  - MyBatis-Plus
  - Shiro

## 📋 Prerequisites

- Node.js (v14.21.3 recommended)
- JDK 1.8
- MySQL 5.7+
- Maven 3.6+

## 🔧 Installation & Setup

### Backend Setup

1. Clone the repository:
```bash
git clone https://github.com/MilesSG/food-ordering-system.git
cd food-ordering-system
```

2. Configure database:
   - Create a MySQL database
   - Update `application.yml` with your database credentials

3. Build and run the backend:
```bash
cd springboot1mi5m
mvn clean install
mvn spring-boot:run
```

### Frontend Setup

1. Install dependencies for admin panel:
```bash
cd admin
npm install
```

2. Start the development server:
```bash
npm run serve
```

## 🌟 Usage

1. Access the admin panel:
   - URL: `http://localhost:8080/admin`
   - Default admin credentials:
     - Username: admin
     - Password: admin

2. Configure restaurant settings:
   - Add menu categories
   - Upload food items
   - Set prices and availability

3. Monitor orders and manage customers

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Miles SG - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspired by modern food delivery platforms
- Built with love for restaurant owners and customers 