<h1 align="center">Christopher Daniel Vargas Villalta</h1>

<p align="center">
  Computer Engineering student at the Instituto Tecnológico de Costa Rica (TEC) who builds full-stack and data-intensive software in teams.
  I focus on backend, data, and AI-powered products: designing databases, ETL pipelines, REST APIs, and Kubernetes deployments,
  and I also work on the frontend, like leading the frontend of a hackathon-winning platform.
  I enjoy leading projects, communicating technical decisions clearly, and turning user research into working products.
</p>

<p align="center">
  <b>Computer Engineering @ <a href="https://www.tec.ac.cr/">TEC</a></b>
</p>

<p align="center">
  <img src="assets/thorfinn.gif" alt="Thorfinn" width="160">
</p>

---

## Highlights

- **Winner of the CRTW Hackathon 2026** with PymeBoost, as frontend lead of a team of 4.
- **Participant in the [AUGE](https://diprovid.ucr.ac.cr/auge/) program** with PymeBoost.
- **Academic Excellence Scholarship** at TEC (I Semester 2026), awarded for outstanding academic performance.
- **Cambridge C1 Advanced** certified in English (overall score 190).

---

## Projects

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/pymeboost.png" alt="PymeBoost" height="110">
    </td>
    <td align="center" width="50%">
      <h3>PymeBoost</h3>
      🏆 <b>Winner of the CRTW Hackathon 2026</b><br>
      Participant in the <a href="https://diprovid.ucr.ac.cr/auge/"><b>AUGE</b></a> program
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      Platform that matches Costa Rican SMEs with business advisors using AI.
      As <b>frontend lead</b> of a team of 4, I defined the frontend architecture and standards, organized the app into six feature modules
      (auth, matching, messaging, contracts, dashboard, reports), co-led user research and Maze usability tests,
      and set up CI/CD with GitHub Actions and automatic Vercel deploys.
    </td>
    <td align="center" valign="middle" width="50%">
      <img src="https://img.shields.io/badge/Next.js-0d1117?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/React-0d1117?style=flat&logo=react&logoColor=61DAFB" alt="React">
      <img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat&logo=typescript&logoColor=3178C6" alt="TypeScript">
      <img src="https://img.shields.io/badge/TanStack%20Query-0d1117?style=flat&logo=reactquery&logoColor=FF4154" alt="TanStack Query">
      <br><br>
      <a href="https://pymeboost-v1.vercel.app/"><img src="https://img.shields.io/badge/-live%20prototype-000000?style=flat&logo=vercel&logoColor=white" alt="Live prototype"></a>
      <a href="https://github.com/IsaacVil/PymeBoost"><img src="https://img.shields.io/badge/-repository-6E40C9?style=flat&logo=github&logoColor=white" alt="Repository"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/smartreserve.png" alt="SmartReserve" height="110">
    </td>
    <td align="center" width="50%">
      <h3>SmartReserve</h3>
      Distributed restaurant backend and analytics
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      I built most of the FastAPI REST API with AWS Cognito JWT auth and RBAC,
      using the DAO pattern to switch between PostgreSQL and sharded MongoDB with a single config variable.
      Microservices run on Kubernetes behind an Nginx load balancer with Redis caching, Elasticsearch search, and a 149-test CI pipeline,
      plus a daily Airflow pipeline that loads a Hive star-schema data warehouse with Spark analyses and a Neo4j graph for delivery routes.
    </td>
    <td align="center" valign="middle" width="50%">
      <img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat&logo=fastapi&logoColor=009688" alt="FastAPI">
      <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/MongoDB-0d1117?style=flat&logo=mongodb&logoColor=47A248" alt="MongoDB">
      <img src="https://img.shields.io/badge/Redis-0d1117?style=flat&logo=redis&logoColor=DC382D" alt="Redis">
      <img src="https://img.shields.io/badge/Elasticsearch-0d1117?style=flat&logo=elasticsearch&logoColor=00BFB3" alt="Elasticsearch">
      <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
      <img src="https://img.shields.io/badge/Airflow-0d1117?style=flat&logo=apacheairflow&logoColor=017CEE" alt="Airflow">
      <img src="https://img.shields.io/badge/Spark-0d1117?style=flat&logo=apachespark&logoColor=E25A1C" alt="Spark">
      <br><br>
      <a href="https://github.com/chris124v/SmartReserve"><img src="https://img.shields.io/badge/-repository-6E40C9?style=flat&logo=github&logoColor=white" alt="Repository"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/merkadit.png" alt="Merkadit" height="110">
    </td>
    <td align="center" width="50%">
      <h3>Merkadit</h3>
      Gastronomic market management
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      Management system for gastronomic markets and the businesses inside them. I designed most of the 56-table MySQL database
      (users, contracts, sales, and finance modules), with stored procedures for point-of-sale registration and monthly business settlements,
      a FastAPI REST API with a 4-layer architecture (handler, controller, service, repository), and a Power BI dashboard.
    </td>
    <td align="center" valign="middle" width="50%">
      <img src="https://img.shields.io/badge/MySQL-0d1117?style=flat&logo=mysql&logoColor=4479A1" alt="MySQL">
      <img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat&logo=fastapi&logoColor=009688" alt="FastAPI">
      <img src="https://img.shields.io/badge/Python-0d1117?style=flat&logo=python&logoColor=3776AB" alt="Python">
      <img src="https://img.shields.io/badge/Power%20BI-0d1117?style=flat&logo=powerbi&logoColor=F2C811" alt="Power BI">
      <img src="https://img.shields.io/badge/Postman-0d1117?style=flat&logo=postman&logoColor=FF6C37" alt="Postman">
      <br><br>
      <a href="https://github.com/chris124v/Merkadit"><img src="https://img.shields.io/badge/-repository-6E40C9?style=flat&logo=github&logoColor=white" alt="Repository"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/promptsales.png" alt="PromptSales" height="110">
    </td>
    <td align="center" width="50%">
      <h3>PromptSales</h3>
      Multi-database data platform
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      Multi-database platform for an AI marketing and sales company, built by a team of 5. I designed the central PostgreSQL data warehouse
      (54 tables, six design iterations) and built an incremental ETL pipeline with SSIS and MongoDB aggregations that merges two SQL Server
      databases and one MongoDB database, loading only new records with a delta watermark per source and running every 11 minutes.
      I also set up the team's Kubernetes environment with five database instances, secrets, and PowerShell deploy scripts.
    </td>
    <td align="center" valign="middle" width="50%">
      <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/SQL%20Server-0d1117?style=flat&logo=microsoftsqlserver&logoColor=CC2927" alt="SQL Server">
      <img src="https://img.shields.io/badge/MongoDB-0d1117?style=flat&logo=mongodb&logoColor=47A248" alt="MongoDB">
      <img src="https://img.shields.io/badge/SSIS-0d1117?style=flat&logo=microsoftsqlserver&logoColor=white" alt="SSIS">
      <img src="https://img.shields.io/badge/Redis-0d1117?style=flat&logo=redis&logoColor=DC382D" alt="Redis">
      <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
      <br><br>
      <a href="https://github.com/chris124v/PromptSales-Data-Platform"><img src="https://img.shields.io/badge/-repository-6E40C9?style=flat&logo=github&logoColor=white" alt="Repository"></a>
    </td>
  </tr>
</table>

---

## Other Projects

- **[DUA Streamliner](https://github.com/chris124v/DUA_StreamLiner)**: system design for automating Costa Rica's customs declaration (DUA) with OCR and AI field extraction, with a FastAPI backend using Domain-Driven Design and a React frontend on Google Cloud.
- **[Arkanoid ED](https://github.com/chris124v/Arkanoid-ED)**: remake of the classic Arkanoid in C++ with Allegro 5, with 10 levels, enemies, and blocks managed with linked lists and dynamic memory.
- **[Huffman Compressor](https://github.com/chris124v/Huffman-Compressor)**: C++ console tool that compresses and decompresses any file with the Huffman algorithm and shows compression statistics.
- **[UndercoverParties](https://github.com/chris124v/UndercoverParties)**: Django monolith with server-side rendering to publish parties, accept guests, and find them on a Leaflet map.
- **[Speedboats](https://github.com/chris124v/Speedboats)**: Micronaut microservices with a React and Tailwind frontend to manage community boat tours.
- **[ChatBotProlog](https://github.com/chris124v/ChatBotProlog)**: console chatbot in Prolog that answers questions, handles synonyms, and learns new knowledge through logical inference.

---

## Technology Stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
      <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
      <img src="https://img.shields.io/badge/JAVA-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
      <img src="https://img.shields.io/badge/NEXT.JS-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/TAILWIND%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
      <img src="https://img.shields.io/badge/TANSTACK%20QUERY-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query">
      <img src="https://img.shields.io/badge/ZOD-3E67B1?style=for-the-badge&logo=zod&logoColor=white" alt="Zod">
    </td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
      <img src="https://img.shields.io/badge/SQLALCHEMY-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
      <img src="https://img.shields.io/badge/PYDANTIC-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic">
      <img src="https://img.shields.io/badge/JWT%20%26%20RBAC-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT and RBAC">
    </td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td>
      <img src="https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/SQL%20SERVER-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
      <img src="https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
      <img src="https://img.shields.io/badge/MONGODB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
      <img src="https://img.shields.io/badge/REDIS-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
      <img src="https://img.shields.io/badge/ELASTICSEARCH-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch">
    </td>
  </tr>
  <tr>
    <td><b>Data Engineering</b></td>
    <td>
      <img src="https://img.shields.io/badge/AIRFLOW-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow">
      <img src="https://img.shields.io/badge/SPARK-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Spark">
      <img src="https://img.shields.io/badge/HIVE-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black" alt="Hive">
      <img src="https://img.shields.io/badge/SSIS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SSIS">
      <img src="https://img.shields.io/badge/METABASE-509EE3?style=for-the-badge&logo=metabase&logoColor=white" alt="Metabase">
      <img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
    </td>
  </tr>
  <tr>
    <td><b>Cloud & DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
      <img src="https://img.shields.io/badge/KUBERNETES-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
      <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx">
      <img src="https://img.shields.io/badge/GITHUB%20ACTIONS-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
      <img src="https://img.shields.io/badge/VERCEL-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
      <img src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
    </td>
  </tr>
  <tr>
    <td><b>Testing</b></td>
    <td>
      <img src="https://img.shields.io/badge/PYTEST-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest">
      <img src="https://img.shields.io/badge/VITEST-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest">
      <img src="https://img.shields.io/badge/POSTMAN-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
    </td>
  </tr>
</table>

---

## What I Enjoy as a Developer

- **Leading projects:** taking the lead role, setting the technical direction, and setting goals.
- **Working as a team:** building things together and sharing what each person does best.
- **Being creative:** finding new ways to solve problems and turning ideas into working products.
- **Meeting people:** connecting with developers, users, and people from other fields.
- **Listening to ideas:** hearing other points of view and letting them change my perspective.

---

## Connect with Me

- **Email:** [cdvv12@gmail.com](mailto:cdvv12@gmail.com)
- **LinkedIn:** [linkedin.com/in/christopher-daniel-vargas-villalta-433529317](https://www.linkedin.com/in/christopher-daniel-vargas-villalta-433529317/)
- **GitHub:** [github.com/chris124v](https://github.com/chris124v)
