PublisherAPI

🧾 Syfte  
Detta projekt är ett REST API byggt i ASP.NET Core som hanterar en enkel förlagsmodell. Det syftar till att demonstrera grunderna i hur man skapar ett Web API med .NET, samt hur man använder Entity Framework Core med Code First-metoden.

⚙️ Funktioner  
- Skapa, hämta, uppdatera och ta bort förlag (CRUD)
- Använder Entity Framework Core med Code First-metoden
- InMemory-databas för enkel testning
- Swagger UI för att testa API:et visuellt

 🧱 Tekniker  
- ASP.NET Core Web API  
- Entity Framework Core (Code First)  
- InMemory Database  
- Swagger (Swashbuckle)  
- C#  
- .NET 8

 ▶️ Så här kör du projektet  
1. Klona repot:  
   `git clone https://github.com/Addee23/PublisherAPI.git`  
2. Öppna lösningen i Visual Studio  
3. Kör projektet – API:et startar automatiskt i Swagger (t.ex. `https://localhost:port/swagger`)

 📸 Exempel på endpoints  
- `GET /api/publishers` – Hämta alla förlag  
- `GET /api/publishers/{id}` – Hämta ett specifikt förlag  
- `POST /api/publishers` – Skapa nytt förlag  
- `PUT /api/publishers/{id}` – Uppdatera ett förlag  
- `DELETE /api/publishers/{id}` – Ta bort ett förlag  

🧪 Testning  
Swagger UI aktiveras automatiskt när du kör projektet, vilket gör det enkelt att testa dina endpoints direkt i webbläsaren.

---

 PublisherAPI

 🧾 Purpose  
This project is a REST API built in ASP.NET Core that manages a simple publisher model. It aims to demonstrate the basics of creating a Web API using .NET, as well as using Entity Framework Core with the Code First approach.

⚙️ Features  
- Create, read, update, and delete publishers (CRUD)  
- Uses Entity Framework Core with Code First approach  
- InMemory database for simple testing  
- Swagger UI for visual API testing

🧱 Technologies  
- ASP.NET Core Web API  
- Entity Framework Core (Code First)  
- InMemory Database  
- Swagger (Swashbuckle)  
- C#  
- .NET 8

▶️ How to run  
1. Clone the repo:  
   `git clone https://github.com/Addee23/PublisherAPI.git`  
2. Open the solution in Visual Studio  
3. Run the project – the API will launch with Swagger UI (e.g., `https://localhost:port/swagger`)

📸 Example endpoints  
- `GET /api/publishers` – Get all publishers  
- `GET /api/publishers/{id}` – Get a specific publisher  
- `POST /api/publishers` – Create new publisher  
- `PUT /api/publishers/{id}` – Update a publisher  
- `DELETE /api/publishers/{id}` – Delete a publisher

🧪 Testing  
Swagger UI is automatically enabled when running the project, making it easy to test your endpoints directly in the browser.
