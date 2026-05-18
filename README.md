<div align="center">

```
███████╗██╗   ██╗ ██████╗ ███████╗███╗   ██╗██╗ ██████╗
██╔════╝██║   ██║██╔════╝ ██╔════╝████╗  ██║██║██╔═══██╗
█████╗  ██║   ██║██║  ███╗█████╗  ██╔██╗ ██║██║██║   ██║
██╔══╝  ██║   ██║██║   ██║██╔══╝  ██║╚██╗██║██║██║   ██║
███████╗╚██████╔╝╚██████╔╝███████╗██║ ╚████║██║╚██████╔╝
╚══════╝ ╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═══╝╚═╝ ╚═════╝
```

### I build things that should exist but don't yet.

`AI` · `Full-Stack` · `Mobile` · `Automation` · `Real-time`

</div>

---

## About

I'm a builder obsessed with closing the gap between an idea and a working product. My projects range from AI-powered voice assistants and real-time video matchmaking platforms to personal finance tools and mobile social apps — all shipped, all real, all mine.

I care about apps that do something useful immediately. No demos. No mockups. Working software.

---

## Projects

### 🎙️ Voice Calendar AI
> *Say it. It's in your calendar.*

Speak or type a sentence like *"Dentist Thursday at 2pm, gym every Monday 7am"* — the app parses it with Llama 3.3 70B, validates it, and creates the events in Google Calendar. Works from your phone, Mac, Apple Watch, Siri, or Telegram. No subscription, no credit card. **100% free.**

```
Voice note / Text
      │
      ├──▶ Groq Whisper API ──▶ transcript
      │
      └──▶ Llama 3.3 70B ──▶ Pydantic validator ──▶ Google Calendar ──▶ iPhone
```

**Features:** live waveform visualizer · confetti on success · offline queue · Telegram bot · Apple Shortcuts integration · Ollama local mode (no internet) · CSV export · dark/light mode · 14 unit tests

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama_3.3-F55036?style=flat-square)
![Google Calendar](https://img.shields.io/badge/Google_Calendar-4285F4?style=flat-square&logo=googlecalendar&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

---

### 🤝 Startup Match
> *Omegle for investors and startups.*

Real-time video matchmaking between founders and investors. You enter the queue, you get matched, you pitch — live, on video. Built with Next.js App Router, Supabase for auth and real-time presence, and Jitsi for zero-config WebRTC video calls.

**Pages:** dashboard · live match queue · video call · profile · auth

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Jitsi](https://img.shields.io/badge/Jitsi-97979A?style=flat-square&logo=jitsi&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

### 📱 Pitch *(Mobile)*
> *A social app built for mobile-first.*

Full-featured React Native app built with Expo and NativeWind. Tab-based navigation: **Feed · Search · Messages · Activity · Profile**. Auth system, real-time data, and a component library designed to feel native on iOS and Android.

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![NativeWind](https://img.shields.io/badge/NativeWind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

### 💰 Finance Analyzer
> *Your transactions, understood.*

Upload bank transactions and get them automatically categorized (shopping, food, income, etc.) and analyzed by an AI layer. Express + PostgreSQL backend, React dashboard frontend, Python AI microservice. Everything talks to each other.

**Stack:** REST API · AI categorization layer · live dashboard · PostgreSQL transaction store

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

### 🤖 AI Content Automator
> *Paste text. Get insight.*

Flask web app powered by OpenRouter that takes any block of text and returns a structured summary, key insights, and an automatic category — presented in a clean UI. The backbone of a personal content intelligence workflow.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6C47FF?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

---

### 🎾 Social Tennis
> *The club, online.*

Community web platform for a tennis club. Sessions calendar, member gallery, announcements board, and a hero that actually sells the club. Clean React SPA, mobile responsive.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

### 💡 Tips Manager *(Desktop)*
> *Fair splits, no spreadsheet drama.*

Native desktop GUI (PySimpleGUIQt) for managing staff hours and tip distribution. Import hours from CSV, auto-calculate tip splits, visualize with Matplotlib charts, and export PDF reports. Built for a real restaurant.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)

---

### 🌐 Portfolio
> *Dark. Cyber. Mine.*

Futuristic React + Vite portfolio with a full cyber aesthetic. Canvas particle network background. Smooth custom cursor with lerp trail. 3D perspective-tilt project cards. Per-project canvas animations (neural nets, orbit graphs, bar charts). Interactive terminal with tab-complete and command history. Everything configured from a single `portfolioData.js` file.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Canvas API](https://img.shields.io/badge/Canvas_API-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS Modules](https://img.shields.io/badge/CSS_Modules-000000?style=flat-square&logo=cssmodules&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

---

## Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Backend**

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**Data & Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**AI**

![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Llama](https://img.shields.io/badge/Llama_3.3_70B-0467DF?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6C47FF?style=for-the-badge)
![Whisper](https://img.shields.io/badge/Whisper_STT-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=eugeniobrb23&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=eugeniobrb23&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="160"/>

</div>

---

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/eugeniobrb23@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eugeniobrb23@gmail.com)
&nbsp;

</div>

---

<div align="center">
<sub>Built fast. Shipped real. No lorem ipsum.</sub>
</div>
