import pypandoc, os
md = r'''<div align="center">

# `SAVITHYA.MUTHUNIMA`

### IT Undergraduate · Cybersecurity · Computer Science · Artificial Intelligence

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=800&color=00F7FF&center=true&vCenter=true&width=700&lines=Building+secure+digital+experiences;Exploring+AI+and+intelligent+systems;Learning+by+building+real+projects;Curious+mind.+Secure+by+design." alt="Animated typing introduction" />

<p>
  <img src="https://img.shields.io/badge/FOCUS-CYBERSECURITY-00F7FF?style=for-the-badge&labelColor=080B14" alt="Cybersecurity focus" />
  <img src="https://img.shields.io/badge/EXPLORING-ARTIFICIAL%20INTELLIGENCE-8A5CFF?style=for-the-badge&labelColor=080B14" alt="AI focus" />
  <img src="https://img.shields.io/badge/MINDSET-ALWAYS%20LEARNING-FF4FD8?style=for-the-badge&labelColor=080B14" alt="Always learning" />
</p>

[**Explore my projects**](#-featured-projects) · [**My skills**](#-technology-universe) · [**Connect with me**](#-connect)

</div>

---

## `01 / SYSTEM PROFILE`

> I’m an IT undergraduate interested in how technology works, how intelligent systems learn, and how digital environments can be made safer. I enjoy exploring **cybersecurity, computer science, and AI** while building projects that turn ideas into practical experiences.

- **Currently exploring:** Cybersecurity, AI, software development, and systems thinking
- **Research interest:** Social engineering, online privacy, and public trust in digital content
- **Build philosophy:** Learn continuously · Think critically · Design responsibly
- **Current mission:** Turn curiosity into useful, well-documented projects

---

## `02 / TECHNOLOGY UNIVERSE`

<div align="center">

| DOMAIN | AREAS I'M EXPLORING |
|:--|:--|
| 🛡️ **Cybersecurity** | Social engineering · Privacy awareness · Security fundamentals |
| 🧠 **Artificial Intelligence** | AI concepts · Responsible AI · Intelligent applications |
| 💻 **Computer Science** | Programming · Algorithms · Software engineering |
| 🌐 **Web Development** | HTML · CSS · JavaScript · Next.js |
| 📊 **Data & Research** | Python · Data analysis · Research methods |
| 🧰 **Tools** | Git · GitHub · VS Code · Figma |

</div>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,html,css,js,ts,react,nextjs,nodejs,git,github,vscode,figma,mysql,supabase&perline=7" alt="Technology icons" />
</p>

> **Note:** This is an evolving learning stack. Keep only the technologies you have actually used or are actively learning.

---

## `03 / FEATURED PROJECTS`

### 🕹️ Cyber Campus — Spot the Social Engineering Threats
A research-focused interactive learning game designed to help users recognise social engineering tactics and think more carefully about online privacy.

- **Focus:** Phishing · Impersonation · Online scams · Privacy awareness
- **Built with:** Next.js, React, TypeScript, and related web technologies *(edit to match your actual project)*
- **Status:** In development

### 🎨 UI/UX Design Explorations
A collection of interface concepts and digital experiences designed with clarity, usability, and visual consistency in mind.

- **Focus:** Interface design · User journeys · Prototyping
- **Tool:** Figma

### 🔬 Research & Experiments
Small experiments, coursework, and learning projects across computing, AI, security, and data.

- **Focus:** Documenting what I learn and improving through practice

> Replace or remove any project description that does not match your public repositories. Add direct links once your projects are published.

---

## `04 / GITHUB ACTIVITY`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR-GITHUB-USERNAME&show_icons=true&hide_border=true&bg_color=080B14&title_color=00F7FF&text_color=E6EDF3&icon_color=8A5CFF&rank_icon=github" alt="GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-GITHUB-USERNAME&layout=compact&hide_border=true&bg_color=080B14&title_color=00F7FF&text_color=E6EDF3" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=YOUR-GITHUB-USERNAME&hide_border=true&background=080B14&ring=00F7FF&fire=FF4FD8&currStreakLabel=00F7FF&sideLabels=E6EDF3&currStreakNum=E6EDF3&sideNums=E6EDF3&dates=8B949E" alt="GitHub contribution streak" />

</div>

---

## `05 / CURRENT QUESTS`

- [ ] Publish and document more hands-on computing projects
- [ ] Strengthen programming and problem-solving foundations
- [ ] Learn more about cybersecurity and privacy protection
- [ ] Explore practical AI projects and responsible AI
- [ ] Improve project documentation and testing

---

## `06 / CONNECT`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Explore%20my%20work-111827?style=for-the-badge&logo=github)](https://github.com/YOUR-GITHUB-USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR-LINKEDIN-URL)
[![Email](https://img.shields.io/badge/Email-Say%20hello-8A5CFF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)

<br />

### `STAY CURIOUS. BUILD WITH PURPOSE. SECURE THE FUTURE.`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080B14,50:312E81,100:00F7FF&height=120&section=footer" width="100%" alt="Abstract gradient footer" />

</div>
'''
# Write using pypandoc as required; Markdown input to Markdown output.
out = "/mnt/data/GitHub_Profile_README.md"
pypandoc.convert_text(md, "md", format="md", outputfile=out, extra_args=["--standalone"])
print(f"Created: {out}\nSize: {os.path.getsize(out)} bytes")
