# Stanley Chidi

Backend Engineer — Go, Node.js, distributed systems, payments infrastructure

## About

I build backend systems — APIs, job queues, payment flows — and spend most of
my time thinking about what happens when things fail: a worker crashes
mid-job, a webhook arrives twice, a payment provider times out. Getting the
happy path working is the easy part; the interesting problems are in retries,
idempotency, and reconciliation.

Currently working in Go and Node.js, with Redis, PostgreSQL, and MySQL.

## Projects

### Distributed Job Queue (Go)

A queue-based job processing system: REST API for submitting jobs, Redis-backed
queue, worker pool for async processing, Nginx round-robin across API
instances. Includes retry logic and a dead-letter queue for jobs that fail
repeatedly, plus a metrics endpoint for observability.

`Go · Gin · Redis · Nginx · Docker`

### Hotel Booking System (Go, Next.js)

Full-stack booking backend built with clean architecture (repository pattern,
dependency injection, service-layer separation). Currently covers room
management — create/update/delete, availability status, pagination, filtering
— with unit tests around the service layer, including race-condition checks.
Booking/payment flow is in progress.

`Go · Next.js `

### Rate-Limited File Uploader

An API for uploading and streaming .txt/.csv files without loading them fully
into memory, with per-IP rate limiting and structured logging.

`Node.js · Express · Winston`

### Smart URL Shortener

URL shortener with Redis caching for redirects, click analytics, and a small
monitoring dashboard (API health, DB/Redis status, response times, uptime).

`Next.js · Express · MySQL · Redis`

### Anochem Group Platform

Product management system for a small cosmetics business — REST API,
MongoDB + Redis, React/TypeScript frontend.

`Node.js · Express · MongoDB · Redis · React · TypeScript`

## What I'm working on now

- Finishing the payment/reconciliation flow for the booking system
  (Flutterwave/Paystack, idempotent webhook handling, retry + backoff)
- Getting more comfortable with distributed systems failure modes —
  partial failures, exactly-once vs at-least-once delivery, that kind of thing

## Contact

iam8nd9@gmail.com 