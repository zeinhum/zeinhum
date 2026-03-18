# Hi, I'm Jameel Ahamad Khan 👋

Software developer based in **Auckland, New Zealand** — MSc Software Engineering, BSc Physics.

I build things that solve real problems under real constraints: offline-first systems for low-connectivity schools, AI-powered HR tools, voice-commanded hardware integrations, and data pipelines that replaced broken workflows.

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | C#, Python, JavaScript (Vanilla) |
| **Frameworks** | ASP.NET Core MVC, Django, Flask |
| **ORM / DB** | Entity Framework Core, SQLite, PostgreSQL, MySQL |
| **AI / ML** | Sentence-BERT, OpenCV, OpenAI API, Edge-TTS, Custom Intent Models |
| **Hardware** | Arduino, Servo Motor, Ultrasonic Sensor |
| **Networking** | LAN Administration, Cisco Meraki |
| **Concepts** | RBAC, Service Layer, Event Delegation, Lazy Loading, MVC, REST |

---

## 🚀 Projects

### 🏫 School Data Intelligence System *(Deployed — Active Use)*
> C# · ASP.NET Core MVC · Entity Framework Core · SQLite · Vanilla JS

A full LAN-based, multi-user school management system built for low-connectivity environments — currently in active daily use at a school.

- **RBAC at the routing layer** — Admin, Teacher, and Finance roles enforced via ASP.NET Areas before requests reach any controller
- **Internal API Router** — a service-dispatch pattern that routes analytics requests (grade sheets, class reports, Teacher Performance Index, School Quality Rating) to dedicated service classes — Open/Closed Principle in practice
- **Vanilla JS NavigationManager** — event delegation + on-demand module loading + explicit teardown, replicating React's component lifecycle with zero framework overhead, optimised for low-spec devices
- Covers attendance, fee & salary records, academic management, and analytics
- **Roadmap:** migrating to multi-tenant cloud architecture with ML-driven features — student learning pattern analysis, subject-wise achievement tracking, and career guidance based on academic and extracurricular data

📁 [View engineering samples →](./School_Data_Intelligence)

---

### 🤖 Smart HR Companion *(Capstone Project)*
> Django · Python · OpenAI API · Edge-TTS · Custom Intent Recognition Model

An AI-powered recruitment tool that takes the grunt work out of CV screening and interviewing.

- Parses uploaded CVs and job descriptions, ranks candidate fit via OpenAI API
- Conducts **voice-based interviews** with real-time text-to-speech (Edge-TTS)
- Trained a custom **intent recognition model** to classify whether a user is answering, asking a question, or expressing doubt — driving adaptive interview flow in real time

---

### 🅿️ Smart Parking System *(Class Project)*
> Python · Sentence-BERT · OpenCV · Arduino

A voice-commanded, hardware-integrated parking system — built end-to-end, physically deployed.

- **SBERT** model interprets voice commands and understands user intent
- **OpenCV** reads number plates for access authorisation
- **Arduino** controls a servo motor gate and reads ultrasonic sensors for real-time parking space monitoring

---

### 📊 Python Grade Processor *(Active Use)*
> Python · Flask

Replaced a broken Excel-based grading workflow for a school that had been struggling with it since 2020.

- Ingests existing Excel grade sheets (preserving years of school data)
- Generates formatted grade sheets, searchable by student symbol number
- LAN-accessible, multi-user desktop application — in daily use

---

## 💼 Currently

**IT Support Engineer (Contractor)** at Rex Technologies, on-site at Dentsu Auckland — supporting ~100 staff, managing device lifecycle, and responding to infrastructure incidents (Cisco Meraki switch management, port-level diagnosis, stable network verification).

---

## 📬 Get in Touch

- 📧 jameelhumn@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/jameel01khan/)

---

*Physics grad who got into software. Builds offline-first, builds for constraints, builds things that actually get used.*
