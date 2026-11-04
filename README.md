
<!-- ================================================= -->
<!--              SHIVA SHAKTI DUBEY                  -->
<!--             GITHUB PROFILE README                -->
<!-- ================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:0B1020,45:172554,100:2563EB&text=SHIVA%20SHAKTI%20DUBEY&fontColor=FFFFFF&fontSize=43&fontAlignY=38&desc=Software%20Developer%20%7C%20Java%20Backend%20Enthusiast&descSize=16&descAlignY=58&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=70D6FF&center=true&vCenter=true&width=650&lines=Building+Backend+Applications;Java+%7C+Spring+Boot+%7C+SQL;DSA+in+C%2B%2B+and+Java;Learning+by+Building+Real+Projects" />

<br/><br/>

<a href="https://www.linkedin.com/in/shiva-shakti-dubey-495337259">
<img src="https://img.shields.io/badge/LinkedIn-Connect-2563EB?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/Shivashakti-1">
<img src="https://img.shields.io/badge/GitHub-Follow-172554?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="mailto:shivashaktidubey@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://x.com/Shivashakti0007">
<img src="https://img.shields.io/badge/X-Follow-111827?style=for-the-badge&logo=x&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Shivashakti-1&label=PROFILE%20VIEWS&color=2563EB&style=flat-square"/>

</div>

---

## 👨‍💻 About Me

```java
public class Developer {

    String name = "Shiva Shakti Dubey";
    String degree = "B.Tech in Information Technology";
    String role = "Software Developer";

    String[] languages = {
        "C", "C++", "Java", "Python"
    };

    String[] interests = {
        "Backend Development",
        "Data Structures & Algorithms",
        "System Design",
        "Problem Solving"
    };

    String currentFocus = "Java Backend Development";

    void sayHello() {
        System.out.println(
            "Building, Learning and Improving Every Day!"
        );
    }
}
```

- 🎓 B.Tech graduate in Information Technology (2026).
- 💻 Interested in Software Development and Backend Engineering.
- ☕ Working with Java, Spring Boot and REST APIs.
- 🧠 Practicing DSA in C++ and Java.
- 🛠️ Building practical projects and exploring new technologies.
- 🚀 Focused on writing clean, maintainable and efficient code.

---

## ⚡ Technical Arsenal

### Programming Languages

<p>
<img src="https://skillicons.dev/icons?i=c,cpp,java,python&theme=dark"/>
</p>

### Backend Development

<p>
<img src="https://skillicons.dev/icons?i=spring,maven,postman&theme=dark"/>
</p>

### Database

<p>
<img src="https://skillicons.dev/icons?i=mysql&theme=dark"/>
</p>

### DevOps & Version Control

<p>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,linux&theme=dark"/>
</p>

### Development Tools & Web Technologies

<p>
<img src="https://skillicons.dev/icons?i=vscode,idea,html,css&theme=dark"/>
</p>

### Core Computer Science

<p>
<img src="https://img.shields.io/badge/DSA-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OOP-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DBMS-0EA5E9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Operating%20Systems-334155?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Computer%20Networks-1D4ED8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/High%20Level%20Design-6D28D9?style=for-the-badge"/>
</p>

---

## 🚀 Featured Projects

### 01. College ERP Portal

<div align="left">

<a href="https://github.com/Shivashakti-1/campusflow-erp">
<img src="https://img.shields.io/badge/GitHub-View%20Source-172554?style=for-the-badge&logo=github"/>
</a>
<a href="https://shivashakti-1.github.io/campusflow-erp/">
<img src="https://img.shields.io/badge/Live%20Demo-Open%20Project-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

</div>

**Tech Stack:** HTML, CSS, JavaScript, Supabase, GitHub Actions

A responsive college ERP portal with separate student and admin dashboards.

**Key Features:**

- Independently developed a responsive college ERP portal with student record management.
- Implemented email/password authentication, role-based access control and Supabase Row Level Security (RLS).
- Automated deployment using GitHub Actions and GitHub Pages.

**Architecture Overview**

```mermaid
flowchart TD
    A[User] --> B[College ERP Portal]
    B --> C[Authentication]
    C --> D{User Role}
    D --> E[Student Dashboard]
    D --> F[Admin Dashboard]
    E --> G[Supabase]
    F --> G
    G --> H[Database + RLS]
```

---

### 02. LLM Regression Detector

<div align="left">

<a href="https://github.com/Shivashakti-1/llm-regression-detector">
<img src="https://img.shields.io/badge/GitHub-View%20Source-172554?style=for-the-badge&logo=github"/>
</a>
<a href="https://llm-regression-detector-cyl7hqumg4cstefzqbvt8t.streamlit.app/">
<img src="https://img.shields.io/badge/Live%20Demo-Open%20Project-7C3AED?style=for-the-badge&logo=streamlit&logoColor=white"/>
</a>

</div>

**Tech Stack:** Python, Streamlit, OpenAI API, Docker, GitHub Actions

A Python-based tool that detects regressions in LLM-generated responses by comparing outputs against saved baseline responses.

**Key Features:**

- Developed keyword and overlap-based scoring with configurable quality thresholds.
- Implemented mock and OpenAI API providers for reproducible and live evaluations.
- Integrated GitHub Actions and Docker to automate evaluations, generate reports and send Slack notifications for failed evaluations.

**Architecture Overview**

```mermaid
flowchart TD
    A[Input Prompt] --> B[LLM Provider]
    B --> C[Generated Response]
    C --> D[Baseline Comparison]
    D --> E[Keyword and Overlap Scoring]
    E --> F[Quality Threshold]
    F --> G{Evaluation Result}
    G -->|Pass| H[Pass Report]
    G -->|Fail| I[Failure Report]
    I --> J[Slack Notification]
```

---

## 🏆 Achievements

<div align="center">

<img src="https://img.shields.io/badge/450%2B-Problems%20Solved-2563EB?style=for-the-badge&logo=leetcode&logoColor=white"/>
<img src="https://img.shields.io/badge/5%20Star-C%20%26%20C%2B%2B-7C3AED?style=for-the-badge&logo=hackerrank&logoColor=white"/>
<img src="https://img.shields.io/badge/Rank-226%20CodeChef%20Starters%20262-0EA5E9?style=for-the-badge&logo=codechef&logoColor=white"/>

</div>

- Solved 450+ coding problems across LeetCode, GeeksforGeeks, NeetCode and HackerRank.
- Earned 5-star badges in C and C++ on HackerRank.
- Secured Rank 226 in CodeChef Starters 262.
- Achieved top ranks in multiple college-level coding competitions.

---

## 📜 Certifications

| Certification | Issuing Organization |
|---|---|
| AWS Academy Graduate – Cloud Foundations | Amazon Web Services |
| AWS Academy Graduate – Generative AI Foundations | Amazon Web Services |
| Advanced Software Engineering Job Simulation | Walmart USA – Forage |
| Python Essential Training | LinkedIn Learning |
| Advance Your Skills in HTML | LinkedIn Learning |

---

## 📊 GitHub Analytics

<div align="center">

<!-- GITHUB STATS -->

<img width="49%"
src="https://github-stats-extended.vercel.app/api?username=Shivashakti-1&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=70D6FF&icon_color=7C3AED&text_color=C9D1D9"
alt="GitHub Statistics"/>

<!-- TOP LANGUAGES -->

<img width="49%"
src="https://github-stats-extended.vercel.app/api/top-langs/?username=Shivashakti-1&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=70D6FF&text_color=C9D1D9&langs_count=8"
alt="Top Programming Languages"/>

<br/><br/>

<!-- STREAK STATS -->

<img width="75%"
src="https://streak-stats.demolab.com?user=Shivashakti-1&theme=tokyonight&hide_border=true&background=0B1020&ring=2563EB&fire=7C3AED&currStreakLabel=70D6FF"
alt="GitHub Contribution Streak"/>

<br/><br/>

<!-- ACTIVITY GRAPH -->

<img width="100%"
src="https://github-readme-activity-graph.vercel.app/graph?username=Shivashakti-1&bg_color=0B1020&color=70D6FF&line=2563EB&point=7C3AED&area=true&hide_border=true"
alt="GitHub Activity Graph"/>

</div>

---

## 🧩 Problem Solving Profiles

<div align="center">

<a href="https://leetcode.com/u/UnknownShiva/">
<img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>

<a href="https://neetcode.io/profile/EagerRayquaza905">
<img src="https://img.shields.io/badge/NeetCode-Profile-2563EB?style=for-the-badge"/>
</a>

<a href="https://www.geeksforgeeks.org/">
<img src="https://img.shields.io/badge/GeeksforGeeks-Practice-16A34A?style=for-the-badge&logo=geeksforgeeks&logoColor=white"/>
</a>

<a href="https://www.codechef.com/">
<img src="https://img.shields.io/badge/CodeChef-Practice-7C3AED?style=for-the-badge&logo=codechef&logoColor=white"/>
</a>

</div>

---

## 🎯 Currently Learning & Exploring

<div align="center">

<img src="https://img.shields.io/badge/Java%20Backend-2563EB?style=for-the-badge&logo=spring&logoColor=white"/>
<img src="https://img.shields.io/badge/System%20Design-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Problem%20Solving-0EA5E9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LLM%20Applications-334155?style=for-the-badge"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm always interested in connecting with developers, discussing technology, learning new things and exploring opportunities.

<a href="https://www.linkedin.com/in/shiva-shakti-dubey-495337259">
<img src="https://img.shields.io/badge/LinkedIn-Shiva%20Shakti%20Dubey-2563EB?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Shivashakti-1">
<img src="https://img.shields.io/badge/GitHub-Shivashakti--1-172554?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:shivashaktidubey@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Contact%20Me-DC2626?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://x.com/Shivashakti0007">
<img src="https://img.shields.io/badge/X-Follow%20Me-111827?style=for-the-badge&logo=x&logoColor=white"/>
</a>

</div>

---

<div align="center">

### 💙 Thanks for visiting my profile!

**"Consistency beats intensity. Keep building. Keep growing."**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:172554,100:0B1020&height=120&section=footer"/>

</div>
