# 🛡️ AI Safe Code Checker

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-Try_It_Now-e91e8c?style=for-the-badge&logo=googlechrome&logoColor=white)](https://dannykadoshi.github.io/ai-safe-code-checker/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Powered by Groq](https://img.shields.io/badge/Powered_by-Groq_Llama_3.3-f55036?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com)
[![No Backend](https://img.shields.io/badge/No_Backend-100%25_Client_Side-blueviolet?style=for-the-badge)](https://dannykadoshi.github.io/ai-safe-code-checker/)

**Paste your code. Get an instant AI-powered security report. No signup, no installation, no data stored.**

[**→ Try it live now**](https://dannykadoshi.github.io/ai-safe-code-checker/)

</div>

---

## What It Does

AI Safe Code Checker scans your code for security vulnerabilities using Groq's Llama 3.3 70B model and returns a prioritized report with:

- **Security score** (0–100) with visual indicator
- **Severity-rated issues** — Critical / High / Medium / Low / Info
- **Concrete fix suggestions** for every issue found
- **OWASP Top 10** vulnerability detection
- **Positive highlights** — what your code does well

---

## Detects

| Vulnerability | Severity |
|---|---|
| SQL Injection | 🔴 Critical |
| Cross-Site Scripting (XSS) | 🟠 High |
| Hardcoded credentials & API keys | 🔴 Critical |
| Broken authentication & session management | 🟠 High |
| Insecure direct object references (IDOR) | 🟠 High |
| CSRF vulnerabilities | 🟠 High |
| Weak cryptography | 🟡 Medium |
| Command injection | 🔴 Critical |
| Insecure deserialization | 🟠 High |
| Missing input validation | 🟡 Medium |
| Insecure dependencies & patterns | 🟡 Medium |
| Code quality & best practice violations | 🟢 Low |

---

## Supported Languages

Python · JavaScript · TypeScript · PHP · Java · Go · Rust · C/C++ · Ruby · SQL · Bash · HTML · CSS · and more

---

## How To Use

1. **Get a free Groq API key** at [console.groq.com/keys](https://console.groq.com/keys) (no credit card needed — works in EU/EEA)
2. **Open the tool** at [dannykadoshi.github.io/ai-safe-code-checker](https://dannykadoshi.github.io/ai-safe-code-checker/)
3. **Paste your API key** into the field at the top (saved to your browser only)
4. **Paste your code** and select the language
5. Click **Analyze Code** (or press `Ctrl+Enter`)
6. Review your security report and copy it as Markdown for PRs or docs

---

## Privacy

- ✅ Your code goes directly from **your browser → Google Gemini API**
- ✅ No server, no database, no logging
- ✅ API key stored in `localStorage` — only on your machine
- ✅ Nothing is stored or tracked anywhere

---

## Run Locally

Just open the file — no build step, no dependencies, no server needed:

```bash
git clone https://github.com/dannykadoshi/ai-safe-code-checker.git
cd ai-safe-code-checker
open index.html
```

---

## Contributing

Contributions welcome! Ideas for improvement:

- [ ] Syntax highlighting in the code editor
- [ ] File upload support (drag & drop)
- [ ] Support for other AI providers (OpenAI, Claude)
- [ ] Dark / light theme toggle
- [ ] History of past scans (localStorage)
- [ ] VS Code extension

Open an issue or submit a PR — all skill levels welcome.

---

## License

MIT — free to use, modify, and distribute.

---

<div align="center">

Built by [Danni Kadoshi](https://github.com/dannykadoshi) · [Portfolio](https://dannykadoshi.github.io) 

If this helped you, consider giving it a ⭐ — it helps others find it.

</div>