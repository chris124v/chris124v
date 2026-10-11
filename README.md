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

<p align="center">
  <img src="assets/pymeboost.png" alt="PymeBoost" width="300">
</p>

<h3 align="center">PymeBoost</h3>

<p align="center">
  🏆 <b>Winner of the CRTW Hackathon 2026</b> · Participant in the <a href="https://diprovid.ucr.ac.cr/auge/"><b>AUGE</b></a> program · Team of 4
</p>

PymeBoost is a platform that connects Costa Rican SMEs with high-performance business advisors through a results-driven model. Many SMEs struggle to identify which areas of their business need improvement and whom to trust to fix them, so the platform analyzes each SME's context, challenges, and goals with an AI matching system that recommends the most suitable advisors. From there, both sides negotiate through structured messaging, generate a contract with clear and measurable objectives, and track its progress phase by phase with reports and a shared dashboard. Onboarding validates legal documents with OCR against the official MEIC registry, and the interface was refined through stakeholder interviews and usability tests with heatmaps on a prototype deployed on Vercel.

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-0d1117?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/React-0d1117?style=flat&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat&logo=typescript&logoColor=3178C6" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-0d1117?style=flat&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Zustand-0d1117?style=flat&logo=react&logoColor=white" alt="Zustand">
  <img src="https://img.shields.io/badge/TanStack%20Query-0d1117?style=flat&logo=reactquery&logoColor=FF4154" alt="TanStack Query">
  <img src="https://img.shields.io/badge/Zod-0d1117?style=flat&logo=zod&logoColor=3E67B1" alt="Zod">
  <img src="https://img.shields.io/badge/React%20Hook%20Form-0d1117?style=flat&logo=reacthookform&logoColor=EC5990" alt="React Hook Form">
  <img src="https://img.shields.io/badge/Radix%20UI-0d1117?style=flat&logo=radixui&logoColor=white" alt="Radix UI">
  <img src="https://img.shields.io/badge/Vitest-0d1117?style=flat&logo=vitest&logoColor=6E9F18" alt="Vitest">
  <img src="https://img.shields.io/badge/ESLint-0d1117?style=flat&logo=eslint&logoColor=4B32C3" alt="ESLint">
  <img src="https://img.shields.io/badge/Prettier-0d1117?style=flat&logo=prettier&logoColor=F7B93E" alt="Prettier">
  <img src="https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat&logo=githubactions&logoColor=2088FF" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Vercel-0d1117?style=flat&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/Maze-0d1117?style=flat" alt="Maze">
</p>

<p align="center">
  <a href="https://pymeboost-v1.vercel.app/"><img src="https://img.shields.io/badge/LIVE%20PROTOTYPE-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live prototype"></a>
  <a href="https://github.com/IsaacVil/PymeBoost"><img src="https://img.shields.io/badge/REPOSITORY-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="Repository"></a>
</p>

<br>

<p align="center">
  <img src="assets/smartreserve.png" alt="SmartReserve" width="360">
</p>

<h3 align="center">SmartReserve</h3>

<p align="center">
  Team of 2
</p>

SmartReserve is a distributed backend for managing restaurant reservations and orders, with a complete analytics layer on top. Clients book tables and place orders while administrators manage their restaurants and menus, all through a FastAPI REST API secured with AWS Cognito JWT tokens and role-based access control. A DAO pattern lets the system switch between PostgreSQL and a sharded MongoDB cluster with replica sets by changing a single configuration variable, Redis caches frequent responses, and an independent microservice indexes the menus in Elasticsearch for full-text search. Everything runs on Kubernetes behind an Nginx load balancer, with a GitHub Actions pipeline that runs the test suite with a 90% coverage gate and publishes the Docker images. A daily Airflow pipeline loads a star-schema data warehouse in Hive, runs Spark analyses of consumption trends, peak hours, and monthly growth for Metabase dashboards, and a Neo4j graph models orders and delivery zones to find co-purchase patterns and shortest delivery routes.

<p align="center">
  <img src="https://img.shields.io/badge/Python-0d1117?style=flat&logo=python&logoColor=3776AB" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat&logo=fastapi&logoColor=009688" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MongoDB-0d1117?style=flat&logo=mongodb&logoColor=47A248" alt="MongoDB">
  <img src="https://img.shields.io/badge/Redis-0d1117?style=flat&logo=redis&logoColor=DC382D" alt="Redis">
  <img src="https://img.shields.io/badge/Elasticsearch-0d1117?style=flat&logo=elasticsearch&logoColor=00BFB3" alt="Elasticsearch">
  <img src="https://img.shields.io/badge/AWS%20Cognito-0d1117?style=flat&logo=amazonwebservices&logoColor=FF9900" alt="AWS Cognito">
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat&logo=docker&logoColor=2496ED" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Nginx-0d1117?style=flat&logo=nginx&logoColor=009639" alt="Nginx">
  <img src="https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat&logo=githubactions&logoColor=2088FF" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Pytest-0d1117?style=flat&logo=pytest&logoColor=0A9EDC" alt="Pytest">
  <img src="https://img.shields.io/badge/Airflow-0d1117?style=flat&logo=apacheairflow&logoColor=017CEE" alt="Airflow">
  <img src="https://img.shields.io/badge/Spark-0d1117?style=flat&logo=apachespark&logoColor=E25A1C" alt="Spark">
  <img src="https://img.shields.io/badge/Hive-0d1117?style=flat&logo=apachehive&logoColor=FDEE21" alt="Hive">
  <img src="https://img.shields.io/badge/Metabase-0d1117?style=flat&logo=metabase&logoColor=509EE3" alt="Metabase">
</p>

<p align="center">
  <a href="https://github.com/chris124v/SmartReserve"><img src="https://img.shields.io/badge/REPOSITORY-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="Repository"></a>
</p>

<br>

<p align="center">
  <img src="assets/merkadit.png" alt="Merkadit" width="170">
</p>

<h3 align="center">Merkadit</h3>

<p align="center">
  Team of 2
</p>

Merkadit is a management system for gastronomic markets and the businesses that operate inside them. Its 56-table MySQL database models markets, buildings, commercial spaces, businesses, contracts, inventory, products, point-of-sale sales, invoicing, and finances. Stored procedures register complete sales with tax calculation inside a transaction and settle each business at the end of the month, applying its commission and rent. A FastAPI REST API with a 4-layer architecture (handler, controller, service, repository) exposes sales and settlements, documented with Swagger and tested with Postman, and a Power BI dashboard built on a business report view shows the monthly sales, commissions, and net balance of every business.

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-0d1117?style=flat&logo=mysql&logoColor=4479A1" alt="MySQL">
  <img src="https://img.shields.io/badge/Python-0d1117?style=flat&logo=python&logoColor=3776AB" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat&logo=fastapi&logoColor=009688" alt="FastAPI">
  <img src="https://img.shields.io/badge/Pydantic-0d1117?style=flat&logo=pydantic&logoColor=E92063" alt="Pydantic">
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat&logo=docker&logoColor=2496ED" alt="Docker">
  <img src="https://img.shields.io/badge/Power%20BI-0d1117?style=flat&logo=powerbi&logoColor=F2C811" alt="Power BI">
  <img src="https://img.shields.io/badge/Postman-0d1117?style=flat&logo=postman&logoColor=FF6C37" alt="Postman">
  <img src="https://img.shields.io/badge/MySQL%20Workbench-0d1117?style=flat&logo=mysql&logoColor=white" alt="MySQL Workbench">
</p>

<p align="center">
  <a href="https://github.com/chris124v/Merkadit"><img src="https://img.shields.io/badge/REPOSITORY-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="Repository"></a>
</p>

<br>

<p align="center">
  <img src="assets/promptsales.png" alt="PromptSales" width="340">
</p>

<h3 align="center">PromptSales</h3>

<p align="center">
  Team of 5
</p>

PromptSales is the data platform of an AI-powered marketing and sales company made up of three sub-companies: PromptContent generates creative content for campaigns, PromptAds runs and optimizes advertising campaigns, and PromptCRM follows leads until the sale is closed. Each sub-company has its own database (MongoDB for content and SQL Server for ads and CRM), and an incremental ETL pipeline built with SSIS and MongoDB aggregation pipelines consolidates them every 11 minutes into a central PostgreSQL data warehouse, loading only new and modified records through delta views and watermarks. All databases run in their own Kubernetes namespaces with secrets, persistent volumes, and one-command PowerShell deploy scripts, and the project also includes concurrency and encryption demos in SQL Server and an MCP server that lets an AI assistant query the databases in natural language.

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQL%20Server-0d1117?style=flat&logo=microsoftsqlserver&logoColor=CC2927" alt="SQL Server">
  <img src="https://img.shields.io/badge/MongoDB-0d1117?style=flat&logo=mongodb&logoColor=47A248" alt="MongoDB">
  <img src="https://img.shields.io/badge/Redis-0d1117?style=flat&logo=redis&logoColor=DC382D" alt="Redis">
  <img src="https://img.shields.io/badge/SSIS-0d1117?style=flat&logo=microsoftsqlserver&logoColor=white" alt="SSIS">
  <img src="https://img.shields.io/badge/SQL%20Server%20Agent-0d1117?style=flat&logo=microsoftsqlserver&logoColor=white" alt="SQL Server Agent">
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat&logo=docker&logoColor=2496ED" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
  <img src="https://img.shields.io/badge/PowerShell-0d1117?style=flat&logo=powershell&logoColor=5391FE" alt="PowerShell">
  <img src="https://img.shields.io/badge/pgAdmin-0d1117?style=flat&logo=postgresql&logoColor=white" alt="pgAdmin">
</p>

<p align="center">
  <a href="https://github.com/chris124v/PromptSales-Data-Platform"><img src="https://img.shields.io/badge/REPOSITORY-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="Repository"></a>
</p>

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

<p>
  <a href="mailto:cdvv12@gmail.com"><img src="https://img.shields.io/badge/EMAIL-cdvv12%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/christopher-daniel-vargas-villalta-433529317/"><img src="https://img.shields.io/badge/LINKEDIN-Christopher%20Vargas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/chris124v"><img src="https://img.shields.io/badge/GITHUB-chris124v-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>
