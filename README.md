# MemorAI

MemorAI is a full-stack AI-powered learning assistant. Upload PDFs, chat with your documents, and generate memory quizzes using OpenAI—all in your browser.

---

## ✨ Features

- Upload PDF files and extract content
- Chat with your document using AI (OpenAI GPT)
- Generate and take quizzes based on your content
- Modern UI with Next.js, Tailwind CSS, and shadcn/ui
- Express.js backend for file processing and AI endpoints

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/memorai.git
cd memorai
```

### 2. Install Dependencies

```bash
npm install
cd backend
npm install
cd ..
```

### 3. Configure Environment Variables

- Copy `.env.example` to `.env` in `backend/`
- Add your OpenAI API key:

```env
# backend/.env
PORT=5000
FRONTEND_URL=http://localhost:3000
OPENAI_API_KEY=sk-...
```

### 4. Start the Backend

```bash
cd backend
npm run dev
```
- The backend runs at [http://localhost:5000](http://localhost:5000)

### 5. Start the Frontend

Open a new terminal in the project root:

```bash
npm run dev
```
- The frontend runs at [http://localhost:3000](http://localhost:3000)

---

## 🖥️ Usage

1. **Upload a PDF** using the drag & drop interface.
2. **Chat** with your document using the AI chat box.
3. **Generate quizzes** and test your knowledge.

---

## 🛠️ Project Structure

```
memorai/
├── app/           # Next.js frontend (pages, components)
├── backend/       # Express.js backend (API, file processing)
├── components/    # UI components (shadcn/ui)
├── lib/           # API client and utilities
├── hooks/         # Custom React hooks
├── public/        # Static assets
├── .env           # (backend) Environment variables
├── README.md
└── ...
```

---

## ⚙️ Environment Variables

- `backend/.env`:
  - `PORT` - Backend port (default: 5000)
  - `FRONTEND_URL` - Frontend URL (default: http://localhost:3000)
  - `OPENAI_API_KEY` - Your OpenAI API key

---

## 🧑‍💻 Development

- **Frontend:** Next.js 15, Tailwind CSS v4, shadcn/ui
- **Backend:** Express.js, TypeScript, OpenAI, pdf-parse, multer

---

## 🐳 Deployment

- Deploy frontend (Next.js) to Vercel, Netlify, or your own server.
- Deploy backend (Express) to Render, Railway, Heroku, or your own server.
- Set environment variables on your deployment platform.

---

## 📝 License

MIT

---

## 🤝 Contributing

Pull requests welcome! For major changes, open an issue first to discuss what you’d like to change.

---

## 📫 Contact

Questions? Open an issue or reach out at [your-email@example.com](mailto:your-email@example.com)
