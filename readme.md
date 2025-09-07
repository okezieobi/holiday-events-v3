# 🎉 HolidayHub – Discover Global Holidays with Ease

> A simple Spring Boot REST API that helps users explore public holidays across countries, set reminders, and share events. Built in under a week to showcase backend skills and clean architecture.

---

## 🚀 Project Overview

**HolidayHub** is a lightweight backend service that fetches holiday data from a public API, stores user reminders, and provides endpoints for sharing and trending events. It’s perfect for developers, planners, and anyone curious about global celebrations.

---

## 🧠 Why I Built This

As a Java developer with 2 years of experience, I wanted to create a project that:
- Demonstrates clean Spring Boot architecture
- Integrates with external APIs
- Is deployable and easy to test
- Can spark interest on LinkedIn and GitHub

---

## 🛠️ Tech Stack

| Layer        | Technology        |
|--------------|-------------------|
| Language     | Java 17           |
| Framework    | Spring Boot 3     |
| Database     | H2 (in-memory)    |
| API Client   | RestTemplate / WebClient |
| External API | [Calendarific](https://calendarific.com/) |
| Docs         | Swagger UI        |
| Deployment   | Render / Railway  |

---

## 📦 Features

- **Get Holidays by Country & Year**  
  `GET /api/holidays?country=NG&year=2025`

- **Search Holidays by Name or Type**  
  `GET /api/holidays/search?query=christmas`

- **Set Event Reminders**  
  `POST /api/reminders`  
  Body:
  ```json
  {
    "holidayId": "NG_2025_Christmas",
    "email": "user@example.com",
    "reminderDate": "2025-12-20"
  }
  ```

- **View Trending Holidays**  
  `GET /api/holidays/trending`

- **Generate Shareable Links**  
  `GET /api/holidays/share/{holidayId}`

---

## 🧪 Testing

- Unit tests using JUnit & Mockito
- Integration tests for API endpoints
- Swagger UI for live API testing

---

## 📅 Development Timeline

| Day | Task |
|-----|------|
| Day 1 | Project setup, API research, model design |
| Day 2 | Holiday API integration, basic endpoints |
| Day 3 | Reminder feature, database setup |
| Day 4 | Trending logic (mocked), shareable links |
| Day 5 | Swagger docs, testing, polish |
| Day 6 | Deployment, README, LinkedIn post |
| Day 7 | Buffer for bug fixes and feedback |

---

## 📸 Screenshots

> _Add Swagger UI screenshot, Postman test, or JSON response sample here_

---

## 🌐 Live Demo

> _Add your deployed API link or Postman collection here_

---

## 📣 How to Promote

Here’s a LinkedIn post idea to go with it:

> 🚀 Just built a Spring Boot project in under a week!  
> 🎉 HolidayHub lets you explore holidays worldwide, set reminders, and share events.  
> 🧠 Learned a lot about API integration, clean architecture, and rapid delivery.  
> 🔗 Check it out on GitHub: [your repo link]  
> #Java #SpringBoot #OpenSource #BackendDev #LinkedInDev

---

## 🧭 Future Improvements

- OAuth login for personalized reminders
- Frontend dashboard (React or Thymeleaf)
- Notifications via email or SMS
- Admin panel for managing holiday data

---

## 🤝 Contributing

Pull requests welcome! For major changes, please open an issue first.

---

## 📄 License

MIT License

---

Would you like me to generate the actual code structure or help you set up the GitHub repo next?