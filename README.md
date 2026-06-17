<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Adarsh%20Yadav&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Problem%20Solver%20%C2%B7%20Builder&descAlignY=58&descColor=a78bfa&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=60&lines=B.Tech+CSE+%40+IIIT+Guwahati+%C2%B7+CGPA+9.27;Turning+ideas+into+real%2C+working+systems)](https://git.io/typing-svg)

</div>

---

<table>
<tr>


## `whoami`

```java
public class Adarsh {

    String  degree   = "B.Tech CSE @ IIIT Guwahati";
    String  batch    = "2028";
    double  cgpa     = 9.27;
    String  location = "Lucknow, Uttar Pradesh";

    String[] passionateAbout = {
        "Backend Systems & APIs",
        "System Design",
        "Clean Architecture",
        "ML & AI Applications"
    };
}
```


</tr>
</table>

---

## `achievements`

<div align="center">

| 🧠 DSA Problems | 📊 CGPA | ⚡ Codeforces | 🍛 CodeChef |
|:-:|:-:|:-:|:-:|
| **500+** | **9.27 / 10** | **1344 Max** | **3 ★** |
| LeetCode · CF · GFG | IIIT Guwahati | Specialist Path | Active |

</div>

---

## `tech_stack`

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**ML / Data**

![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## `featured_projects`

<table>
<tr>

<td width="50%" valign="top">

### 🔐 Multi-Tenant Isolation Engine
> Production-grade SaaS backend infrastructure with **physical database isolation per tenant**, token-bucket rate limiting via Redis/Bucket4j, and dynamic HikariCP pool routing. Built with Spring Boot 3, Flyway, Docker, and a full CI/CD pipeline publishing to GHCR.

**What makes it different:**
- Every tenant = own MySQL database (zero cross-contamination possible)
- Rate limits enforced per-tier in Redis (FREE: 60 req/min → Enterprise: 2000 req/min)
- Datasources added at runtime with zero downtime
- GitHub Actions: build → test → multi-arch Docker image → GHCR

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adarsh-yadav1/multitenant-isolation-engine)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>

<td width="50%" valign="top">

### 🏥 Hospital Management API
> Production-style REST API with **JWT authentication**, role-based access control (Doctor / Patient / Admin), appointment conflict detection, and DTO-based pagination architecture.

**What makes it different:**
- Conflict detection prevents double-booking at DB level
- Role hierarchy enforced at filter chain, not controller level
- Full audit trail on every appointment change

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adarsh-yadav1/hospital-management)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

</td>

</tr>
<tr>

<td width="50%" valign="top">

### 🤖 FinBot — AI Loan Automation
> Hackathon project automating the end-to-end loan application process using AI — reducing manual review overhead and accelerating credit decisions.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adarsh-yadav1/FinBot)
![AI](https://img.shields.io/badge/AI-FF6F00?style=flat-square&logo=openai&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>

<td width="50%" valign="top">

### 💬 Talk-To-Data
> Natural language interface for querying structured datasets. Ask questions in plain English, get data-driven answers via NL2SQL pipeline.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adarsh-yadav1/Talk-To-Data)
![LLM](https://img.shields.io/badge/LLM-412991?style=flat-square&logo=openai&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>

</tr>
<tr>

<td width="50%" valign="top">

### 📧 Email Triage System
> Automated NLP pipeline to classify and prioritize incoming emails — reducing inbox noise and improving response efficiency using text classification.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/adarsh-yadav1/EmailTriageSystem)
![NLP](https://img.shields.io/badge/NLP-FF6C37?style=flat-square&logo=python&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>

<td width="50%" valign="top">

### 🏠 House Price Prediction
> Linear Regression model on 545+ records with full data pipeline: cleaning, encoding, feature scaling. **R² 0.61 · RMSE ~1M**. Key predictors: area, bathrooms, air-conditioning.

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

</td>

</tr>
</table>

---

## `github_activity`

<div align="center">

![Streak](https://github-readme-streak-stats.herokuapp.com?user=adarsh-yadav1&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA)

</div>

<div align="center">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=adarsh-yadav1&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8)

</div>

---

## `beyond_the_code`

<div align="center">

```
🎭  Club Coordinator @ Afsaane — The Drama Club, IIIT Guwahati
     Led 20+ member team across stage performances & cultural events
     Aug 2025 – Present
```

</div>

---

## `connect`

<div align="center">

[![Email](https://img.shields.io/badge/iamyadavadarsh@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iamyadavadarsh@gmail.com)
[![GitHub](https://img.shields.io/badge/adarsh--yadav1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adarsh-yadav1)
[![Location](https://img.shields.io/badge/Lucknow,_UP-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Lucknow)

<br/>

> *"First, solve the problem. Then, write the code."*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
