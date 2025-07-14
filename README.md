Got it — you're seeing formatting issues because **GitHub doesn’t render Markdown properly inside code blocks (`...`) when they contain regular Markdown** like `#`, `|`, or `---`.

✅ **Fix**: Make sure only code (commands, config, scripts) goes inside triple backticks. Keep the rest as plain markdown.

---

Here's the **corrected version** of your `README.md` (just copy-paste it directly into your repo’s `README.md` file — no extra code fences):

---

# 🚀 Questly – Your AI-Powered Voice Mentor

**Questly** is a **real-time, voice-driven educational platform** that acts like your **personal AI mentor** — always available, tailored to your learning goals, and built for the future of frictionless, interactive learning.

---

## ✨ Features at a Glance

🎤 **Voice-Based Learning**
Talk, don’t type — interact naturally via **Vapi-powered voice AI** in real time.

🔐 **Secure Auth with Clerk**
Modern, seamless authentication with **Clerk** ensures data privacy and session integrity.

🔁 **Conversation History**
Never lose context — all sessions are saved so you can revisit or resume anytime.

📱 **Fully Responsive UI**
Crafted using **Tailwind CSS** and **shadcn/ui** for pixel-perfect responsiveness across devices.

🔎 **AI-Powered Search**
Smart, **query-based navigation** helps users find content intuitively.

💳 **Flexible Subscriptions**
Integrated **Stripe billing (via Clerk)** supports tiered plans and easy payment flows.

📦 **Scalable Realtime Backend**
Powered by **Supabase** — enjoy instant APIs, Postgres DB, and real-time sync.

---

## 🛠 Tech Stack

| Layer        | Tools & Libraries                            |
| ------------ | -------------------------------------------- |
| **Frontend** | Next.js, TypeScript, Tailwind CSS, shadcn/ui |
| **Backend**  | Supabase (PostgreSQL, Realtime, Storage)     |
| **Auth**     | Clerk                                        |
| **Billing**  | Stripe                                       |
| **Voice AI** | Vapi                                         |

---

## 🚀 Getting Started

Clone the repo and run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

Start editing your app from: `app/page.tsx`

---

## 📚 Learn More

* [Next.js Documentation](https://nextjs.org/docs)
* [Supabase Docs](https://supabase.com/docs)
* [Clerk Docs](https://clerk.dev/docs)
* [Stripe Docs](https://stripe.com/docs)
* [Vapi Docs](https://docs.vapi.ai/)

---

## 🚢 Deploy on Vercel

Deploy instantly with [Vercel](https://vercel.com/new).
Check the [Next.js deployment guide](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

## 💡 Why Questly?

Questly combines **real-time AI**, **voice interaction**, and **modern web tech** to deliver a seamless and intelligent learning experience — tailored to you.

---
