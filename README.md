<a href="https://aiunlocked-sdk.vercel.app">
  <h1 align="center">🔓 AIUNLOCKED SDK</h1>
</a>

<p align="center">
  A production-ready, extensible AI chatbot platform built with <strong>Next.js</strong>, <strong>Vercel AI SDK</strong>, and <strong>DeepInfra</strong>.
</p>

<p align="center">
  <a href="#-features"><strong>🚀 Features</strong></a> ·
  <a href="#-deploy-your-own"><strong>📦 Deploy Your Own</strong></a> ·
  <a href="#-running-locally"><strong>💻 Running Locally</strong></a> ·
  <a href="#-secure-deployment-practices"><strong>🔐 Security</strong></a> ·
  <a href="#-authors"><strong>👨‍💻 Authors</strong></a> ·
  <a href="#-license"><strong>📜 License</strong></a>
</p>

---

## 🚀 Features

- 🔁 **Streaming Responses**: Powered by the [Vercel AI SDK](https://sdk.vercel.ai/docs) for seamless integration with multiple LLM providers.
- 🛠️ **Tool Integrations**: Easily extend capabilities (includes a working weather tool example).
- 🧠 **Model Flexibility**: Compatible with DeepInfra, OpenAI, and more.
- 🎨 **Modern UI/UX**: Built with [shadcn/ui](https://ui.shadcn.com) and [Tailwind CSS](https://tailwindcss.com).
- 🔗 **Vercel-Optimized**: Zero-config deployment with edge functions and App Router support.
- 🧩 **Modular Architecture**: Plug-and-play components for fast iteration and innovation.

---

## 📦 Deploy Your Own

Deploy a live version instantly via Vercel:

<p align="center">
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/Boomchainlab/aiunlocked-sdk&project-name=aiunlocked-sdk&repository-name=aiunlocked-sdk&demo-title=AIUNLOCKED+Chatbot&demo-url=https%3A%2F%2Faiunlocked-sdk.vercel.app&demo-description=A+modern+AI+chatbot+powered+by+Vercel+SDK+and+DeepInfra&products=%5B%7B%22type%22%3A%22integration%22%2C%22integrationSlug%22%3A%22deepinfra%22%2C%22productSlug%22%3A%22api-token%22%2C%22protocol%22%3A%22ai%22%7D%5D">
    <img src="https://vercel.com/button" alt="Deploy with Vercel" />
  </a>
</p>

---

## 💻 Running Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Boomchainlab/aiunlocked-sdk.git
cd aiunlocked-sdkp

2. Install Dependencies
npm install
# or
yarn install
# or
pnpm install


3. Add Environment Variables

Create a .env.local file in the root directory:
DEEPINFRA_API_KEY=your_deepinfra_api_key

4. Start the Dev Server
npm run dev
# or
yarn dev
# or
pnpm dev

Then open http://localhost:3000 in your browser.


🔐 Secure Deployment Practices
	•	🔑 Do not hard-code your API keys in the repo.
	•	🌐 Use Vercel’s Environment Variables dashboard for production secrets.
	•	🔁 Rotate keys periodically from DeepInfra/OpenAI dashboards.
	•	🧪 Use .env.example to guide contributors.


👨‍💻 Authors

AIUNLOCKED SDK is adapted from the official Vercel Labs AI SDK Starter, customized and extended by:
	•	Boomchainlab
	•	DeepInfra
	•	Vercel AI SDK

🧠 Unlock Possibilities

“The future isn’t just AI — it’s AI you control.”
— AIUNLOCKED Team
