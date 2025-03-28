# 📚 Book Reviews API (Projeto Avaliações de Livros - DevInHouse)

## 📌 About the Project
Book Reviews is a backend REST API application for managing user-submitted book reviews. It supports CRUD operations and basic validation for creating and listing reviews with book details and reviewer information.

## 💡 Features
- CRUD operations for book reviews
- Review attributes: title, description, rating, reviewer
- Data validation
- In-memory H2 database

## 🛠️ Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Lombok

## 📁 Folder Structure
```
├── src
│   └── main
│       ├── java
│       │   └── com.bookreviews
│       └── resources
│           └── application.properties
```

## 🚀 Getting Started
1. Clone the repository
2. Open in your IDE (e.g., IntelliJ)
3. Run `BookReviewsApplication.java`
4. Access `http://localhost:8080` to begin testing via Postman or Swagger UI

```bash
git clone https://github.com/Lucasvdalves/ProjetoAvaliacoesDeLivrosDevInHouse.git
```

## 🔍 API Endpoints
- `GET /reviews`
- `POST /reviews`
- `PUT /reviews/{id}`
- `DELETE /reviews/{id}`

## 🎯 Future Improvements
- Add user authentication
- Connect to persistent database (PostgreSQL/MySQL)
- Frontend integration

## 📄 License
MIT License

