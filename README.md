# 🏡 Villa Tracker

Villa Tracker is a full-stack web application designed to help site engineers and project managers manage villas and their associated data, including documents, images, maps, and metadata — all in one place.

## 🔧 Tech Stack

- **Backend:** ASP.NET Core Web API (.NET 8)
- **Frontend:** Blazor Server (C# UI)
- **Database:** SQL Server with Entity Framework Core
- **Authentication:** ASP.NET Identity (with Admin Role support)
- **File Handling:** Upload, preview, and download (images, PDFs, Office docs)
- **Location Integration:** Google Maps for villa locations

## 🚀 Features

- Secure login system with role support
- Create, edit, delete villas
- Upload and manage related files (PDF, images, Word, Excel, etc.)
- Preview images and PDFs inside the app
- Filter and search villas by name, date, or file size
- View villa location on Google Maps
- Scalable and easily deployable

## 📁 Project Structure

villa-tracker/
├── VillaManager.sln
├── VillaManager.API/        ← ASP.NET Core Web API (Backend)
├── VillaManager.Web/        ← Blazor Server (Frontend)
├── VillaManager.Core/       ← Shared Models & DTOs
├── README.md
├── .gitignore
