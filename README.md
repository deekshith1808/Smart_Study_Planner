# ⚡ Spark — Smart Study Planner

**Plan Smarter. Stay Focused. Achieve More.**

Spark is a Flutter-based smart study planning application designed to help students organize their academic activities, improve concentration, track progress, and develop consistent study habits.

Built with **Flutter, Dart, and Supabase**, Spark brings together productivity tools, study scheduling, focus management, analytics, and gamified learning in one application.

🏆 **Special Award — Best Software Team | KIT Smart Move Hackathon (Among 75 Teams)**

---

## 🎯 Problem Statement

Students often struggle with poor time management, procrastination, digital distractions, inconsistent study routines, and difficulty tracking academic progress.

Traditional planners focus mainly on organizing tasks, but students need a more comprehensive solution that encourages discipline, motivation, and consistent learning.

## 💡 Our Solution

Spark provides an integrated study management experience where students can plan their schedules, monitor their learning progress, organize notes, and improve focus.

Our goal is to transform traditional study planning into a more engaging, structured, and rewarding learning experience.

## ✨ Key Features

- 📅 **Smart Study Scheduling** — Organize subjects, academic tasks, and daily study activities.
- ⏱️ **Pomodoro Focus Timer** — Manage focused study sessions with structured time intervals.
- 📊 **Study Analytics** — Visualize study activity, session history, and productivity.
- 📝 **Quick Notes** — Create and organize subject-specific notes.
- 🎮 **Gamified Learning Journey** — Make studying engaging with experience points (XP), streaks, and learning milestones.
- 🎓 **Personalized Onboarding** — Set up an academic profile based on educational needs.
- 👨‍👩‍👧 **Parental Dashboard** — Dedicated parental monitoring and notification features.
- 🌗 **Light & Dark Themes** — A customizable and student-friendly interface.
- ☁️ **Cloud-Backed Data Management** — Supabase integration for authentication and study-related data.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform application development |
| Dart | Application programming language |
| Supabase | Authentication and backend database |
| PostgreSQL | Relational data storage through Supabase |
| Provider | State management |
| GoRouter | Application navigation |
| SharedPreferences | Local data persistence |
| FL Chart | Analytics and data visualization |
| Material Design | User interface components |

## 🏗️ Project Structure

```text
Smart_Study_Planner/
├── lib/
│   ├── data/
│   │   ├── repositories/
│   │   └── services/
│   ├── domain/
│   │   ├── models/
│   │   ├── services/
│   │   └── utils/
│   ├── ui/
│   │   ├── core/
│   │   └── features/
│   │       ├── analytics/
│   │       ├── auth/
│   │       ├── home/
│   │       ├── journey/
│   │       ├── notes/
│   │       ├── parental/
│   │       ├── pomodoro/
│   │       ├── schedule/
│   │       ├── settings/
│   │       └── subjects/
│   └── main.dart
├── assets/
├── android/
├── ios/
├── web/
├── supabase_schema.sql
└── pubspec.yaml
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- Android Studio or VS Code
- Android emulator or compatible physical device
- Supabase project for backend functionality

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/deekshith1808/Smart_Study_Planner.git
```

**2. Navigate to the project directory**

```bash
cd Smart_Study_Planner
```

**3. Install dependencies**

```bash
flutter pub get
```

**4. Configure Supabase**

Create a Supabase project and run `supabase_schema.sql` in the Supabase SQL Editor to initialize the database tables and policies.

Configure the application with your Supabase project URL and publishable/anon key according to the implementation in `supabase_service.dart`.

Never commit private service-role keys or secrets.

**5. Run the application**

```bash
flutter run
```

## 🏆 Hackathon Achievement

Spark was developed as part of the **24-Hour Smart Move Hackathon at KIT**.

Our team received the **Special Award for Best Software Team**, competing among 75 participating teams.

This achievement reflects our collaborative problem-solving, application development, and ability to transform a real-world student challenge into a working software solution within a limited timeframe.

## 🔮 Future Enhancements

- AI-powered personalized study recommendations
- Intelligent timetable optimization
- Adaptive learning based on student performance
- Advanced distraction management
- Predictive academic performance insights
- Smart reminders and personalized learning suggestions

## 🌟 Our Vision

To make learning more productive, engaging, and accessible by combining smart planning, technology, and gamification.

**Spark isn't just about managing study time — it's about building better learning habits.**

## 👨‍💻 Project Information

**Project:** Spark — Smart Study Planner  
**Category:** Education Technology / Productivity  
**Developed For:** KIT Smart Move Hackathon  
**Achievement:** Best Software Team — Special Award  
**Repository:** https://github.com/deekshith1808/Smart_Study_Planner

---

⭐ If you find this project interesting, consider starring the repository!
