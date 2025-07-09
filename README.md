# Medbuddy
# 🏥 Doctors Appointment Platform

A full-stack doctor appointment booking application built using **Next.js**, **Tailwind CSS**, **Prisma**, and **Shadcn UI**. It allows patients to browse doctors, book appointments, and join live video/audio consultations powered by **Vonage**.

Inspired by the [RoadsideCoder YouTube tutorial](https://www.youtube.com/watch?v=ID1PRFF1dlw).

---

## 🚀 Features

- 🔐 Role-based authentication (Doctor & Patient)
- 📅 Appointment booking with availability filtering
- 🎥 Integrated video/audio calls using Vonage
- 📬 Email notifications (optional)
- 📊 Patient & Doctor dashboards
- 🧑‍⚕️ Doctor search by specialty, rating, and more
- 📱 Fully responsive UI with Tailwind + Shadcn

---

## 🛠️ Tech Stack

| Layer         | Technology                          |
|---------------|--------------------------------------|
| Frontend      | Next.js, Tailwind CSS, Shadcn UI     |
| Backend       | Next.js API Routes, Prisma ORM       |
| Database      | PostgreSQL (hosted on Neon)          |
| Realtime Calls| Vonage API (Video/Audio)             |
| Auth          | Clerk or NextAuth                    |
| Deployment    | Vercel                               |

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/doctors-appointment-platform.git
cd doctors-appointment-platform
