from pathlib import Path
content = r"""# Hi 👋, I'm Sriram

## 💻 Full-Stack MERN Developer | 🔐 Cybersecurity Enthusiast | 🤖 AI & ML Learner

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Full-Stack+MERN+Developer;Cybersecurity+Enthusiast;AI+%26+ML+Learner;Building+Secure+%26+Scalable+Applications" />
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:0066FF&height=180&section=header&text=Welcome%20to%20My%20GitHub&fontSize=40&fontColor=ffffff"/>
</p>

## 👨‍💻 About Me

- 🎓 Final Year Computer Science Engineering Student
- 💻 Full-Stack MERN Developer passionate about secure software.
- 🔐 Learning Cybersecurity, Ethical Hacking & Secure Coding.
- 🤖 Exploring AI & Machine Learning.
- 🌱 Practicing DSA, LeetCode, TryHackMe & Hack The Box.
- 🚚 Creator of **RouteMind** – Smart Transport Operations Platform.
- 📡 Built **PortScanX** – Python TCP Port Scanner.
- 📫 Email: **ssriramcse23@gmail.com**
- 🌐 Portfolio: https://srirams2006.netlify.app

## 🌐 Connect

- LinkedIn: https://linkedin.com/in/srirams2006
- YouTube: https://www.youtube.com/@sriramcodes
- LeetCode: https://leetcode.com/sriramcse

## 🚀 Tech Stack

### Frontend
React • JavaScript • HTML • CSS • Tailwind CSS • Bootstrap • Vite

### Backend
Node.js • Express.js • MongoDB • REST API • Firebase

### Languages
Python • Java • C • C++

### Cybersecurity
Kali Linux • Burp Suite • Metasploit • Nmap • Wireshark • OWASP ZAP • SQLMap • TryHackMe • Hack The Box

## 🚀 Featured Projects

| Project | Tech |
|---|---|
| RouteMind | MERN |
| AI Intrusion Detection System | Python + ML |
| PortScanX | Python |
| Chat Application | MERN + Socket.IO |

## 📊 GitHub Analytics

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=ssriram-siva&show_icons=true&theme=tokyonight&hide_border=true"/>
<img height="170" src="https://streak-stats.demolab.com?user=ssriram-siva&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ssriram-siva&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ssriram-siva&theme=tokyo-night"/>
</p>

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=ssriram-siva&theme=tokyonight&no-frame=true"/>
</p>

## 📚 Currently Learning

- Advanced React
- System Design
- Secure Coding
- AI & ML
- Ethical Hacking

---

<p align="center"><b>Build • Learn • Secure • Repeat 🚀</b></p>
"""
path="/mnt/data/README.md"
Path(path).write_text(content,encoding="utf-8")
print(path)
