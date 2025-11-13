# Event Management App

A modern, AI-powered event management platform built with React, Vite, and TailwindCSS.

## 🚀 Features

- **Event Management**: Create, edit, and delete events with full CRUD operations
- **AI Interest Prediction**: Predict attendee interest levels using AI
- **AI Copy Generator**: Generate catchy event descriptions and promotional content
- **AI Email Composer**: Create personalized invitation and follow-up emails
- **Dark Mode**: Toggle between light and dark themes
- **Responsive Design**: Fully responsive and mobile-friendly
- **Smooth Animations**: Powered by Framer Motion

## 🛠️ Tech Stack

- React 18
- Vite
- TailwindCSS
- Framer Motion
- React Router DOM
- Zustand (State Management)
- Axios
- OpenAI / Gemini API (for AI features)

## 📦 Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file (optional, for AI features):
```env
VITE_AI_API_KEY=your_api_key_here
VITE_AI_API_BASE=https://api.openai.com/v1
```

4. Run the development server:
```bash
npm run dev
```

5. Build for production:
```bash
npm run build
```

## 🎨 Color Palette

- Primary: #F97316 (Orange)
- Secondary: #10B981 (Green)
- Accent: #111827 (Dark Gray)

## 📁 Project Structure

```
src/
├── components/          # Reusable components
│   ├── EventCard.jsx
│   ├── EventForm.jsx
│   └── AiTools/        # AI tool components
├── pages/              # Page components
│   ├── Home.jsx
│   ├── Dashboard.jsx
│   ├── EventDetails.jsx
│   └── AiTools.jsx
├── lib/                # Utilities and store
│   ├── store.js        # Zustand store
│   ├── ai.js           # AI functions
│   └── api.js          # API utilities
├── routes/             # Routing configuration
├── shared/             # Shared components
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   └── Button.jsx
├── App.jsx
└── main.jsx
```

## 🎯 Usage

1. **Create Events**: Navigate to Dashboard and click "Create Event"
2. **View Events**: Browse upcoming events on the Home page
3. **AI Tools**: Use AI Tools page to predict interest, generate copy, or compose emails
4. **Manage Events**: Edit or delete events from the Dashboard

## 🤖 AI Integration

The app includes AI features that can work with OpenAI or Gemini APIs. If no API key is provided, the app will use fallback mock responses.

To enable AI features:
1. Get an API key from OpenAI or Google Gemini
2. Add it to your `.env` file
3. Restart the development server

## 📝 License

MIT

## 🙏 Credits

Built as part of the 60 Days React AI Challenge.

