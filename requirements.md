# School LMS Requirements

## Roles

### Developer
- Create Teacher accounts
- Create Student accounts
- Generate IDs and passwords
- Reset passwords
- Force password changes
- View login history
- Manage users
- Access Developer Dashboard

### Teacher
- Upload books (PDF)
- Upload syllabus (PDF)
- Upload notes (PDF, DOCX, TXT)
- Upload videos
- Upload answer keys
- Edit and delete content
- Create quizzes
- View student reports

### Student
- Access books
- Access notes
- Access syllabus
- Watch videos
- Take quizzes
- View progress
- Earn points
- Daily streaks
- Leaderboard
- Unlock titles

## Content Structure

Class → Subject → Chapter → Topic

Example:
Class 10 → Mathematics → Algebra → Quadratic Equations

## Titles

- Good
- Better
- Excellent
- Scholar
- Champion
- Master Learner

## Database

PostgreSQL 17

Database Name:
school_platform

## Storage

Supabase Storage

Buckets:
- books
- syllabus
- notes
- videos
- answer-keys

## Features

- JWT Authentication
- Role Based Access Control
- AI Assistant
- AI Doubt Solver
- Quiz System
- Reports
- Daily Streaks
- Points System
- Leaderboard
- Responsive Design
