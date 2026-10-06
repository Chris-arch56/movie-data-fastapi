# RESTful API with FastAPI & Supabase

A backend web application featuring a robust **FastAPI backend** and cloud database integration using **Supabase**.

## 🚀 Features
* **Full CRUD Operations:** Implemented secure REST endpoints for creating, retrieving, updating, and deleting relational database records.
* **Cloud Database Integration:** Utilized Supabase (PostgreSQL) for remote data storage, user schema management, and persistent storage.
* **Security & Authentication:** Contains custom server authentication modules (`myserverauth.py`) to manage secure API endpoints.
* **API Documentation:** Automatically generated interactive API documentation using Swagger UI / OpenAPI.

## 🛠️ Tech Stack
* **Backend Framework:** Python, FastAPI
* **Database & Cloud Hosting:** Supabase, PostgreSQL
* **API Architecture:** REST APIs, HTTP protocols
* **Server Deployment:** Uvicorn ASGI server.

## 📦 Quick Start
1. Clone the repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the development server:
   ```bash
   uvicorn myserver:app --reload
   ```
