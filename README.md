# Student–Teacher Notes Platform 📚

This is a full-stack platform that connects students to teachers. Students can pay to access uploaded notes using multiple payment methods including Mobile Money, PayPal, and Card.

## 🗂 Project Structure

```
student_notes_platform/
├── backend/        # Node.js + Express server
├── frontend/       # React frontend (mobile-first)
├── database/       # SQL schema and seed
└── .env.example    # Shared env template
```

## 🚀 Features

- User roles: Student, Teacher, Admin
- JWT Authentication
- Upload and sell notes (PDFs)
- Payment via Stripe, PayPal, Flutterwave (Mobile Money + Card)
- Cloudinary + local storage support

## 🧪 Setup

See the `/backend/README.md` and `/frontend/README.md` for full setup steps.

## 🛰 Deployment

- Frontend: Vercel
- Backend: Render
- DB: PostgreSQL (Supabase or Railway recommended)
