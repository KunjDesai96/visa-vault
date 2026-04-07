# 🛡️ Visa Vault

> An open-source AI-powered immigration copilot for H-1B visa holders.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active%20Development-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen)
![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-black)

---

## 🧭 What is Visa Vault?

Navigating H-1B immigration is stressful, document-heavy, and full of confusing deadlines. Visa Vault is a free, open-source tool that helps H-1B holders take control of their immigration journey — all in one place.

No lawyers. No paywalls. Just clarity.

---

## ✨ Features

- 📅 **Visa Timeline Tracker** — Track every milestone from H-1B filing to Green Card
- 📁 **Document Organizer** — Store and categorize your I-797, LCAs, passports, and more
- ⏰ **Deadline Alerts** — Never miss a critical immigration deadline
- 📊 **Priority Date Tracker** — Monitor USCIS visa bulletin priority dates in real time
- 🤖 **AI Copilot** — Plain-English explanations of immigration documents and RFE assistance
- 📋 **Visa Bulletin Interpreter** — Understand what the monthly bulletin means for *your* case

---

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | [Next.js](https://nextjs.org/) |
| Backend | Next.js API Routes |
| Database | [Supabase](https://supabase.com/) (PostgreSQL) |
| Auth | Supabase Auth |
| Storage | Supabase Storage |
| AI | [Groq API](https://groq.com/) (Llama 3 - free tier) |
| Hosting | [Vercel](https://vercel.com/) |

---

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+
- A free [Supabase](https://supabase.com/) account
- A free [Groq](https://groq.com/) API key

### Installation

```bash
# Clone the repo
git clone https://github.com/KunjDesai96/visa-vault.git
cd visa-vault

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env.local
```

### Environment Variables

Fill in your `.env.local`:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
GROQ_API_KEY=your_groq_api_key
```

### Run Locally

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

---

## 🗺️ Roadmap

- [x] Project setup
- [ ] Authentication (Supabase Auth)
- [ ] Dashboard UI
- [ ] Document upload & organizer
- [ ] Visa timeline tracker
- [ ] Priority date tracker
- [ ] AI document explainer
- [ ] RFE assistance
- [ ] Deadline alerts
- [ ] Mobile responsive polish

---

## 🤝 Contributing

Contributions are welcome! Whether you're fixing a bug, improving docs, or building a new feature — all PRs are appreciated.

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'feat: add your feature'`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## 📄 License

MIT — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

## 💬 Why Open Source?

Immigration is hard enough. Tools that help shouldn't be locked behind paywalls. This project is built in public, for the community, by someone who lives this experience firsthand.

If this helps you, consider giving it a ⭐ — it helps others find it too.

---

<p align="center">Built with ❤️ by <a href="https://github.com/KunjDesai96">KunjDesai96</a></p>
