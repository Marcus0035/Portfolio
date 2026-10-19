
# 💼 Marek Dvořáček – Developer Portfolio

Welcome to my developer portfolio. Here you'll find my most important projects covering automation, full-stack development, cross-platform tools, and music-related applications.

---

## ⚓ BattleShips API

Tech: ASP.NET Core (.NET 8), EF Core, SQL Server, Swagger, Docker, Docker Compose, xUnit

Backend REST API for a Battleships game implemented in ASP.NET Core. Handles game creation, player management, game state, and shooting logic. Supports both database-backed and in-memory repositories, includes automated tests, Swagger documentation, and a fully containerized setup using Docker and Docker Compose.

📎 [Repository](https://github.com/Marcus0035/BattleShips)

---

## 🚗 Fun Cars
**Tech:** HTML, CSS, JavaScript, Google Calendar API  
Developed and deployed a responsive presentation website for **fun-cars.cz** using pure HTML, CSS, and JavaScript.  
The site displays available days connected to a Google Calendar and includes an email contact form for inquiries. 

📎 [fun-cars.cz](https://fun-cars.cz/)


---

## 🔔 FL Studio Price Checker

**Tech:** .NET 9, Playwright, MailKit, Docker  
Automatically monitors the FL Studio price and sends HTML email notifications when the price drops. Supports Docker, retry logic, logging, and Gmail SMTP.  

📎 [Repository](https://github.com/Marcus0035/FlChecker2)

---

## 🧾 Order Management System
**Tech:** .NET 6, Blazor, MudBlazor, MSSQL  
Internal order management system with login, database access via EF Core, and modern UI components using MudBlazor.  

📎 [Repository](https://github.com/Marcus0035/OrderManagement)

---

## 🎼 KeyChordFinder
**Tech:** ASP.NET Core (.NET 10), PostgreSQL, EF Core, Redis, TypeScript (Vite, no framework), Web Audio API, xUnit, Vitest, Docker Compose, Caddy, GitHub Actions  

A free web app for musicians, live at **[keychordfinder.com](https://keychordfinder.com)**.

I make all kinds of music, from acoustic and electric guitars and bass to EDM like techno and liquid, and I wanted one place for chords, scales and ear training instead of five different sites. I could not find one, so I built it, from the database to the server it runs on.

**What it does**
- **Chord Finder** – click keys on a piano and see which chord they form, inversions included
- **Progression Builder** – every chord of a key and scale on piano or guitar, dragged onto a timeline, played on repeat, with arpeggios (pattern, speed, octaves) and MIDI export for a DAW
- **Ear Training** – guess notes, intervals, scales and chords, only the ones you choose, with statistics and favourite exercises
- **Theory** – all scales and chords with their steps and intervals, ready to listen to
- **Tuner, Singing and Metronome** – microphone pitch detection in the browser, singing practice and a metronome with accents, subdivisions and seven sounds
- **My own collection** – custom chords, scales and arpeggios saved to the account
- **Real instrument sounds** – piano, acoustic, nylon and electric guitar, bass, harp, cello, violin, flute, xylophone and organ, played with the Web Audio API
- **Achievements** – two groups of goals that unlock colours, instruments and the collection

**Backend**
- Layered solution: API, Services (domain logic, caching, e-mail), Data (EF Core, migrations, seed data) and a test project (44 xUnit tests)
- Accounts on ASP.NET Core Identity with e-mail confirmation, password reset, lockout, JWT access tokens and rotating refresh tokens in an `HttpOnly` cookie (stored only as SHA-256 hashes)
- Rate limiting of endpoints that send e-mail, Redis (HybridCache) caching, typed TypeScript client generated from the OpenAPI document

**Hosting and DevOps**
- Self-hosted on a Hetzner VPS with Docker Compose: Caddy with automatic HTTPS (Let's Encrypt), Postgres and Redis in a network without internet access, read-only API container, dropped capabilities and memory limits
- GitHub Actions deploys every merge to `main` over a restricted SSH key; nightly `pg_dump` backups with rotation

📎 [keychordfinder.com](https://keychordfinder.com)

---

## 💰 Volleyball Payment
**Tech:** Blazor, MAUI, SQLite, MudBlazor
Personal project focused on payment after trainings.  

📎 [Repository](https://github.com/Marcus0035/PlatiKrab)

---

📬 Contact: marek.dvoracek606@gmail.com  
🌐 GitHub: [github.com/Marcus0035](https://github.com/Marcus0035)
"# portfolio" 
