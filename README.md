#  Hi, I'm Stanley

Backend Engineer | Golang | Node.js | Distributed Systems & Payments

---

##  About Me
I build scalable backend systems focused on reliability, performance, and real-world production challenges.

- 🔧 Golang & Node.js specialist  
- 💳 Payment systems (Flutterwave, Paystack, escrow)  
- ⚙️ Distributed systems & job queues   
- 🔄 Webhooks, retries, reconciliation systems  

---

##  What I’m Working On
- Distributed job processing systems  
- Payment reconciliation engine with retry & backoff  
- Webhook reliability systems (idempotency + recovery)  
- Scalable booking & reservation backend  

---

##  Tech Stack
- Languages: Go, JavaScript (Node.js)  
- Frameworks: Gin, Express  
- Databases: MongoDB, PostgreSQL, MySQL, Redis  

---

##  Featured Projects

---

###  Distributed Job Queue Service (Go)

A distributed job processing system demonstrating queue-based architecture, horizontal scaling, and fault-tolerant design.

####  Overview
- Accepts jobs via REST API  
- Queues jobs in Redis  
- Processes asynchronously using worker pools  
- Exposes system metrics for monitoring  

####  Architecture
Client → Nginx → API Instances → Redis Queue → Workers → Results  

#### Features
- REST API for job submission & tracking  
- Redis-backed queue  
- Concurrent worker pools  
- Horizontal scaling (API + workers)  
- Load balancing with Nginx (round-robin)  
- Retry mechanism for failed jobs  
- Dead Letter Queue (DLQ)  
- Metrics endpoint for observability  

####  Tech Stack
Go • Gin • Redis • Nginx • Docker  

---

###  Smart URL Shortener

A full-stack system with caching, analytics, and real-time monitoring.

####  Features
- URL shortening with persistent storage  
- Redis caching for fast redirects  
- Analytics tracking (click insights)  
- Live system monitoring:
  - API health  
  - DB + Redis status  
  - Response time  
  - Memory usage  
  - Uptime  

####  Tech Stack
Next.js • Express • MySQL • Redis • Tailwind  

---

###  Rate-Limited File Uploader API

Production-style API with streaming processing and built-in rate limiting.

####  Features
- Upload .txt and .csv files  
- Rate limiting (5 uploads/min/IP)  
- Streaming file processing (memory efficient)  
- File metadata extraction  
- Structured logging (Winston)  
- Clean architecture (controller/service/middleware)  

####  Architecture
Client → Express → Middleware → Controller → Service → File System  

🔗 Live API: https://rate-limited-uploader.onrender.com/api/upload  

---

###  Anochem Group Platform

Full-stack product management system for a cosmetics company.

####  Features
- REST API for product management  
- MongoDB + Redis integration  
- Modular backend architecture  
- Responsive frontend with dynamic data fetching  

####  Tech Stack
Node.js • Express • MongoDB • Redis • React • TypeScript  

---

###  Hotel Booking System
Backend system with payments, booking logic, and webhook handling  

#### Key Features
- Payment integration (Flutterwave/Paystack)  
- Idempotent webhook handling  
- Retry + reconciliation system  
- Booking lifecycle management  

---

##  Engineering Focus

I focus on solving real backend problems:

- Distributed system design  
- Fault tolerance & retries  
- Idempotent APIs  
- Background job processing  
- System observability & metrics  

---

##  Contact Me
- Email: iam8nd9@gmail.com
