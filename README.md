# BookWeb.Api
CRUD operation asp.net Core Web API 
# README for Web API Project
# Product Web API (ASP.NET Core 8)

## Overview
Backend Web API built with ASP.NET Core 8 for CRUD operations on products. Demonstrates clean architecture, async operations, and JWT authentication. Designed for MVC apps, SPAs, or mobile clients.
## Features
  - Fully async CRUD operations ⚡
  -	EF Core (Database First)
  -	Service Layer for business logic isolation 🛠️
  -	Manual DTOs Mapping for API contracts for full control
  -	JWT authentication & authorization 🔒
  -	Centralized global exception handling 📝
    
## Architecture Overview
  - Frontend Client (MVC / SPA / Mobile) -> ASP.NET Core Web API -> Database (EF Core, SQL Server)

## Flow:
  -	Request JWT token
  -	API issues signed JWT 🔑
  - JWT used for CRUD requests
  - Validated in API
  -	CRUD handled asynchronously in Service Layer
  -	Global exception middleware ensures consistency
  -	
## Tech Stack 💻
  - ASP.NET Core Web API 8
  - C# 8, Async/Await ⚡
  - EF Core (Database First) 
  - JWT / Cookie Auth 🔒
  - SQL Server

## Architecture & Best Practices 🧩
- Layered structure: Controllers, Services, Data
- DTOs decouple API from DB
- Async for scalability
- Global exception handling
- Cloud-ready ☁️
- Clean, maintainable, test-friendly code ✅

## Repository link for Web API
master: [https://github.com/suhashiniPrjct/BooksWebAPISln.git]	
## Integration with MVC Application
This Web API is designed to be consumed by the Story Spot MVC application, which:
- Handles UI rendering and user interaction
- Delegates all data operations to this API
- Enforces a strict separation between presentation and backend logic
- This architecture mirrors enterprise-level application design commonly adopted across modern .NET solutions in UK-based organisations.
	
## Potential Enhancements 🚀
- Refresh token implementation 🔄
- API versioning 📌
- Unit and integration testing ✅
- Structured logging and monitoring 📊

## About the Developer 👨‍💻
I am an experienced .NET developer specialising in Microsoft technologies, including:
- C#
- ASP.NET Core & ASP.NET MVC
- ASP.NET Web API
- ASP.NET Framework
- Entity Framework Core
- LINQ & SQL Server
This API demonstrates my ability to design and implement secure, scalable backend services using current .NET frameworks and industry-standard best practices.

