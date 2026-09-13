<div align="center">

# Hi, I'm Abhijit S Kunnel 👋

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3200&pause=1000&color=00D4FF&center=true&vCenter=true&width=900&lines=Building+software+that+removes+friction;Developer+Tools+%7C+Automation+%7C+Systems;Python+%7C+Java+%7C+C+%7C+Kotlin;Always+building%2C+always+learning" />

<br>

**I build software that removes friction: from workflow automation and developer tools to low-level networking systems.**

Computer Science Engineering Student • 🇮🇳 Kerala, India • 🇦🇪 Raised in Dubai

<br>

<a href="https://github.com/ask-io">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/abhijit-s-kunnel">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:abhijit.uni.29@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

# 👨‍💻 About Me

Most of the software I build starts with a simple question:

> **"Can this be engineered to be faster, cleaner, or automated entirely?"**

I focus on two complementary spaces:
- **Developer Tools & Automation:** Designing systems that eliminate tedious, repetitive manual workflows, whether that involves parsing complex BIM coordination matrices or calculating academic thresholds client-side.
- **Systems & Networking:** Working close to the wire, handling low-level socket programming, UDP multicast protocols, and concurrent architectures to connect devices seamlessly without cloud intermediaries.

I'm a Computer Science Engineering student who learns best by building concrete prototypes, diagnosing networking bottlenecks, and shipping tools that are genuinely useful.

---

# 🚀 Featured Projects

<table>

<tr>

<td width="50%" valign="top">

<h3 align="center">🛠 BIM Clash Portal</h3>

<p align="center">
A web application that transforms raw BIM clash detection matrices into organised, colour-coded Excel reports, saving engineers hours of repetitive Excel work.
</p>

---

### 💡 Why I built it

I built BIM Clash Portal after watching my dad, a structural engineer and BIM lead, spend hours manually sorting clash detection reports every time project models were merged.

It wasn't an engineering problem, it was an Excel problem.

I wanted to automate that workflow so engineers could spend more time coordinating clashes instead of cleaning spreadsheets.

### ⚡ Engineering Challenges

- Built a parser that automatically detects the boundaries of clash matrices instead of relying on fixed spreadsheet dimensions.
- Different projects export different matrix sizes, so the parser dynamically adapts to each file at runtime.
- Used custom HTTP response headers to send summary statistics directly to the frontend while generating downloadable Excel reports.
- Automatically produces filtered, colour-coded, multi-sheet reports grouped by priority.
<br><br><br>
### ⚙️ Tech

Python • FastAPI • openpyxl • JavaScript • HTML • CSS

<br>

<p align="center">

<a href="https://clash-portal.onrender.com">
<img src="https://img.shields.io/badge/Live%20Demo-00D4FF?style=for-the-badge"/>
</a>

<a href="https://github.com/ask-io/clash-portal">
<img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github"/>
</a>

</p>

</td>

<td width="50%" valign="top">

<h3 align="center">🛡 BunkSafe</h3>

<p align="center">
A retro 8-bit themed Progressive Web App that turns raw attendance percentages into actionable safe bunk and recovery calculations.
</p>

---

### 💡 Why I built it

Like most students, I found myself repeatedly doing stressful mental math before deciding whether I could skip a class.

The first version was a native Android app in Kotlin, but asking users to download APKs created unnecessary friction and locked out iOS users entirely.

I scrapped it and rebuilt it from scratch as an offline-first PWA with an 8-bit arcade aesthetic, installable straight from the browser on any device.

### ⚡ Engineering Challenges

- Engineered dynamic attendance math that calculates safe bunks or required consecutive recovery classes in real time.
- Migrated architecture from native Android (Kotlin) to a build-step-free Vanilla Web Stack.
- Implemented Service Workers and Web App Manifest for native-like offline caching and home screen installation.
- Utilised browser LocalStorage for instant persistence with zero external servers and complete client-side privacy.
- Crafted a responsive, retro pixel-art interface using pure custom CSS.

### ⚙️ Tech

JavaScript • Custom Pixel CSS • HTML5 • Service Workers • Web App Manifest

<br>

<p align="center">

<a href="https://ask-io.github.io/BunkSafe/">
<img src="https://img.shields.io/badge/Live%20Demo-00D4FF?style=for-the-badge"/>
</a>

<a href="https://github.com/ask-io/BunkSafe">
<img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github"/>
</a>

</p>

</td>

</tr>

<tr>

<td colspan="2" valign="top">

<h3 align="center">📡 LANDrop (Java Network Testbed & Core Engine)</h3>

<p align="center">
<img src="https://img.shields.io/badge/Status-Under%20Construction-FFA500?style=for-the-badge&logo=statuspage&logoColor=white"/>
<img src="https://img.shields.io/badge/Coursework-S3%20OOP%20Group%20Project-blueviolet?style=for-the-badge"/>
</p>

<p align="center">
A high-performance local network file sharing and peer-to-peer discovery suite built for cross-platform LAN environments with zero cloud dependencies, developed as an Object-Oriented Programming (S3) group project.
</p>

---

### 💡 Why we're building it

Cloud drives and messaging apps add latency, compress files, and require active internet just to push data across two devices on the same desk. 

As part of our Semester 3 Object-Oriented Programming coursework, our team is building an open-source LAN drop utility from scratch. I spearheaded the core networking and discovery engine to enable instant, zero-configuration local peer detection and direct device-to-device communication across subnets without third-party signaling servers.

### ⚡ Engineering Challenges & Progress

- Engineered an autonomous UDP multicast discovery engine on `230.0.0.1:4446` with dynamic network interface binding to handle multi-adapter setups (Wi-Fi, virtual adapters, LAN).
- Built thread-safe active peer registries using `ConcurrentHashMap` with periodic background sweeps to gracefully detect device dropouts.
- Designed an interactive terminal chat testbed and verification benchmark to stress-test real-time bidirectional packets, loopback filtering, and latency.
- Implemented stealth modes to instantly pause beacons and suppress incoming discovery probes on demand.

### ⚙️ Tech

Java • UDP Multicast • Socket Programming • Concurrency • Object-Oriented Design

<br>

<p align="center">

<a href="https://github.com/rxjith/LANDrop/tree/abhijit">
<img src="https://img.shields.io/badge/Project%20Branch-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://github.com/ask-io/LANDrop-Testbed">
<img src="https://img.shields.io/badge/Testbed%20Repo-00D4FF?style=for-the-badge&logo=github"/>
</a>

</p>

</td>

</tr>

</table>

---

# 💻 Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,java,c,javascript,kotlin&theme=dark"/>

<br><br>

### Frameworks & Tools

<img src="https://skillicons.dev/icons?i=fastapi,tailwind,html,css,bash,git,github,linux,vscode&theme=dark"/>

<br><br>

<img src="https://img.shields.io/badge/Socket%20Programming-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/UDP%20Multicast-00D4FF?style=for-the-badge&logo=wireshark&logoColor=black"/>
<img src="https://img.shields.io/badge/Autodesk%20Revit-0696D7?style=for-the-badge&logo=autodeskrevit&logoColor=white"/>
<img src="https://img.shields.io/badge/SketchUp-005F9E?style=for-the-badge&logo=sketchup&logoColor=white"/>

</div>

---

# 📈 GitHub Activity

<div align="center">

<img width="80%" src="https://github-readme-streak-stats.herokuapp.com/?user=ask-io&theme=github-dark&hide_border=true" />

<br><br>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ask-io/ask-io/output/github-snake-dark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ask-io/ask-io/output/github-snake.svg">
<img src="https://raw.githubusercontent.com/ask-io/ask-io/output/github-snake-dark.svg">
</picture>

</div>

---

<div align="center">

### Thanks for stopping by!

If you have feedback, an interesting project, or just want to chat, feel free to connect.

<a href="https://www.linkedin.com/in/abhijit-s-kunnel">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
</a>

<a href="mailto:abhijit.uni.29@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail"/>
</a>

<br><br>

![](https://komarev.com/ghpvc/?username=ask-io&style=flat-square&color=00D4FF&label=Profile+Views)

</div>
