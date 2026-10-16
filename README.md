# MindSprint — Psychology of Learning Quiz

A responsive React + Vite quiz website built from the supplied Psychology of Learning assignment PDF (Weeks 0–12, 130 questions).

## Features
- Week-by-week assignments (10 questions per week)
- **Study mode:** selecting an answer immediately shows correct/incorrect feedback and the correct answer
- **Exam mode:** answers are hidden until you submit the quiz; then you see score and answer review
- Question navigator, progress bar, previous/next, retry and review
- Saves best scores locally in the browser
- Responsive design for mobile and desktop

## Run locally
```bash
npm install
npm run dev
```

## Deploy to Vercel
1. Create a GitHub repository and upload the contents of this folder.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Framework preset: **Vite**; Build command: `npm run build`; Output directory: `dist`.
4. Click **Deploy**.

No environment variables or backend are required. Quiz progress/best scores are stored in the visitor's browser. Week 12 answers follow the marked choices in the source PDF; the PDF itself notes that Week 12 grading was not visible and Q1 may need verification.
