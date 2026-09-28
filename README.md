# QuizCraft

QuizCraft is a modern web application that enables students to generate and practice multiple-choice quizzes on any topic.

## Features
- **Quiz Setup:** Custom subject, topic, difficulty (Easy, Medium, Hard), and question count (5, 10, 15, 20).
- **Built-in & Dynamic Question Bank:** Instant quizzes for pre-loaded topics or dynamically generated topics.
- **Interactive Quiz Runner:** Real-time progress tracking, single question focus, and answer confirmation.
- **Results & Performance Review:** Detailed score summary, percentage calculation, correct answer highlights, and step-by-step explanations.
- **Retake & Reset:** Easy buttons to re-try or start a new quiz setup.

## Tech Stack
- React 18
- Vite
- Tailwind CSS
- Lucide React

---

## Run Locally

1. **Clone or download this repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/quizcraft.git
   cd quizcraft
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run development server:**
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`.

---

## Deploy to GitHub & Vercel

### 1. Upload to GitHub
Initialize your Git repository and push your project:
```bash
git init
git add .
git commit -m "Initial QuizCraft website commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/quizcraft.git
git push -u origin main
```

### 2. Host Publicly on Vercel
1. Log into [Vercel](https://vercel.com).
2. Click **Add New** > **Project**.
3. Select and import your `quizcraft` GitHub repository.
4. Keep default settings (Framework: **Vite**, Build Command: `npm run build`).
5. Click **Deploy**. Vercel will create your public live website URL.