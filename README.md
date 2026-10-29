<h1 align="center">Hi, I'm Sanjit Mandal 👋</h1>
<h3 align="center">AI Security Engineer · Ethical Hacker · Penetration Tester · Python Developer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Role-AI%20Security%20Engineer-4b3fe0?style=for-the-badge" alt="Role" />
  <img src="https://img.shields.io/badge/Experience-3%20years-151a2d?style=for-the-badge" alt="Experience" />
  <img src="https://img.shields.io/badge/Based%20in-Nepal-dc143c?style=for-the-badge" alt="Location" />
</p>

---

## 🛡️ About me

- 🔐 **AI Security Engineer at Waft Tech**, securing AI and LLM-powered systems
- 🎯 About **3 years** in ethical hacking, penetration testing and AI security engineering
- 🏰 Hands-on with **Active Directory attacks**: enumeration, credential attacks, privilege escalation and lateral movement
- 🐍 I write **Python** for security tooling and automation
- 🎓 Bachelor's degree · from Siraha, Nepal
- 🚀 Goal: build a company that makes AI safe to use at scale

## 🧰 What I do

| Area | Focus |
| --- | --- |
| **AI / LLM security** | Prompt injection, jailbreak testing, data leakage, secure AI integration |
| **Penetration testing** | Web apps, networks, mobile apps (APK review) |
| **Active Directory** | Attack-path analysis, Kerberos attacks, privilege escalation |
| **Secure code review** | Leaked secrets, unsafe configs, risky dependencies |
| **Automation** | Python scripts and tools for recon and reporting |

## ⚙️ Tools & tech

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" alt="Kali Linux" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=flat-square" alt="Nmap" />
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=flat-square" alt="Metasploit" />
  <img src="https://img.shields.io/badge/BloodHound-B30000?style=flat-square" alt="BloodHound" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
</p>

## 📌 Projects

### 🛡️ [VulnAgent](https://github.com/s81207169-a11y/vulnagent): break an AI app, then harden it

A deliberately vulnerable AI application across four layers (**LLM chatbot, MCP server, autonomous agent, AI-generated API**), each with a hardened twin. An 11-attack suite runs on every push: every attack compromises the vulnerable version and is blocked by the hardened one.

- **Prompt injection**, direct and indirect, including secret exfiltration by an agent reading a poisoned invoice
- **MCP tool poisoning** and confused-deputy attacks, plus a static scanner that flags poisoned tool descriptions
- **Agent guardrails** that hold even when the model obeys the attacker: tool allowlists, human approval, path confinement, loop limits
- **Vibe-code review**: SQLi, `eval()` RCE, missing auth, hard-coded secrets
- Findings mapped to **OWASP LLM Top 10** and **MITRE ATLAS**

`Python` · `MCP` · `Flask` · `pytest` · `Ollama / OpenAI-compatible APIs`

### 🛰️ [mcp-sentinel](https://github.com/s81207169-a11y/mcp-sentinel): security scanner for MCP servers

Connects to MCP servers the way an AI client does, pulls every tool definition, and flags what the model would silently trust. Installable CLI with **18 rules** and CI-ready output.

- **Tool poisoning**: hidden instruction blocks, concealment, overrides, exfiltration wording, invisible Unicode, in descriptions *and* parameter schemas
- **Cross-server tool shadowing** and name collisions
- **Rug-pull detection**: a lockfile of tool hashes catches servers that change after approval
- **Config audit**: plaintext secrets, unpinned `npx`/`uvx` packages, plain-HTTP remotes, privileged Docker
- Console, JSON and **SARIF** output for GitHub code scanning; zero false alarms on the official GitHub MCP server

`Python` · `MCP SDK` · `SARIF` · `pytest`

## 📊 GitHub stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=s81207169-a11y&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=s81207169-a11y&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

## 🤝 Let's connect

Open to security research collaboration, pentest engagements and AI security work.

<p>
  <a href="https://www.linkedin.com/in/sanjit-mandal-2b1621413"><img src="https://img.shields.io/badge/LinkedIn-Sanjit%20Mandal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

> ⚠️ All my security testing is done ethically, on systems I own or am authorized to test.
