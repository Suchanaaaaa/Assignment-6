# 💪 FitLog - Workout Library

FitLog is a modern workout library and fitness planning web application built with Next.js. Users can browse exercises, view workout details, add workouts to today's plan, save workouts for later, and track their daily fitness routine through a clean and responsive interface.

---

## 🚀 Live Features

- Browse a collection of workouts from an external API
- View detailed workout information including equipment, duration, calories, rating, sets, reps, and instructions
- Add workouts to Today's Plan
- Save workouts for later
- Track total exercises, duration, and calories in My Plan
- Mark workouts as completed
- Remove workouts from the plan
- Sort workouts by Duration, Calories, and Rating
- Fully responsive design for mobile, tablet, and desktop
- Toast notifications for user actions
- Custom 404 page for invalid routes

---

## 🛠️ Technologies Used

- **Next.js 15**
- **React**
- **TypeScript**
- **Tailwind CSS**
- **Lucide React Icons**
- **React Context API**
- **Local Storage**
- **Vercel Deployment**

---

## ✨ Key Features

### 1. Workout Library
Display all workouts from the API in a responsive card layout with workout image, muscle groups, equipment, duration, calories, and rating.

### 2. Workout Details Page
Provides complete workout information including specifications, instructions, difficulty level, sets, reps, and action buttons.

### 3. Today's Plan Management
Users can add workouts to their daily plan, monitor progress, mark workouts as done, and remove them when needed.

### 4. Save for Later
Users can save workouts separately and access them anytime from the My Plan page.

### 5. Dynamic Statistics
Automatically calculates and updates total exercises, workout duration, and calories burned based on the current plan.

---

## 📂 Project Structure

```bash
app/
components/
context/
lib/
public/
```

---

## 📦 Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Build project:

```bash
npm run build
```

Start production server:

```bash
npm start
```

---

## 🔗 API Used

### All Workouts

```bash
https://api.abcz.workers.dev/api/fitlog
```

### Single Workout Details

```bash
https://api.abcz.workers.dev/api/fitlog/:id
```

---

## 👨‍💻 Developer

Developed as part of the Programming Hero Assignment - FitLog Workout Library.

---

## © Copyright

© 2026 FitLog — Workout Library. Train hard, log honest.
