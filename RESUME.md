# Kevin Brey

**Software Architect** | [kevinbrey.com](https://kevinbrey.com) | [LinkedIn](https://linkedin.com/in/breyk) | [GitHub](https://github.com/manbearwiz)

## Education

**B.S. Software Engineering (ABET Accredited)** University of Wisconsin–Platteville, 2015

## Experience

### **KBX** | _Software Architect_ | Mar 2021 – Present | Green Bay, WI

**Tech:** Angular, TypeScript, RxJS, Angular Material, single-spa, Storybook, Webpack, Vite, Datadog, GitHub Actions, Docker, AWS (CloudFront, S3, ECS, OpenSearch)

- Led the frontend platform strategy for a large-scale Transportation Management System (TMS), reducing cross-team dependencies and accelerating delivery cycles.
- Architected a high-performance platform using single-spa, native ES Modules, and Vite, enabling 10+ teams to deploy independently.
- Developed core modules for AuthN/AuthZ, logging, and feature flags, ensuring unified abstractions across the platform.
- Automated major framework migrations across ~70 microfrontends, reducing technical debt with minimal developer intervention.
- Established coding standards, shared tooling, and generative AI instructions to maintain high code quality and increase engineering velocity.
- Collaborated with UX to build a reusable UI library in Storybook with automated visual regression testing.
- Established SLIs/SLOs via Datadog across 500+ production microservices, fostering a culture of proactive incident response.
- Led the Frontend Community of Practice, mentoring senior engineers on RxJS patterns, modern testing best practices, and performance optimization.
- Migrated CI/CD from Azure Pipelines to GitHub Actions, improving security posture, reducing pipeline complexity, and tightening feedback loops.

### **Beacon Technologies** | _Full Stack Software Engineer (Consultant)_ | Feb 2019 – Mar 2021 | Appleton, WI

_Single project contract before transitioning to KBX directly:_

**[KBX Logistics – Visibility](https://kbxtrack.kbxt.cloud/)** • _Full Stack (Angular, RxJS, Elasticsearch, C#, ASP.NET Core, AWS)_

- Developed a real-time freight tracking and supply chain visibility platform serving global logistics operations.
- Designed a scheduled ingestion pipeline to bypass legacy bottlenecks, flattening complex data from "black-box" stored procedures into Elasticsearch.
- Reduced query times from timeouts to milliseconds, enabling real-time search, paging, and filtering across years of historical data.
- Delivered previously unattainable visibility into freight movement, giving the business new actionable insights into logistics operations.

### **Omni Resources** | _Software Engineer (Consultant)_ | Jun 2015 – Feb 2019 | Appleton, WI

_Solutions consultant adapting to various tech stacks and team environments across multiple high-impact projects:_

**[Homesite – Quote Refresh](https://autoinsurance1.progressivedirect.com/0/UQA/Quote/AddressEntryPrefillEdit)** • _Frontend (React, Redux, Material-UI, Storybook, Webpack, Swagger Hub, create-react-app)_

- Developed a responsive web application for quoting and purchasing home and renters insurance.
- Designed a single codebase supporting multiple brands with distinct workflows.

**Bankers' Bank – FireSafe** • _Full Stack (Angular, TypeScript, RxJS, Bootstrap 4, Swagger)_

- Developed a document ingestion and search platform for financial record management.
- Created an interface to extract key data from text and PDFs.
- Leveraged Apache Lucene for efficient search and filtering.

**AbbVie – Safety Hub** • _Frontend (Angular, TypeScript, RxJS, Angular Material, Swagger)_

- Delivered a proof-of-concept analytics dashboard for pharmaceutical adverse event data.
- Designed custom interactive visualizations using Angular directives on SVG elements.

**Renaissance – AWS Migration** • _DevOps (C#, AWS (ECS, EC2, RDS), Docker, Terraform, Packer, Linux, Redis, Jenkins)_

- Led migration of legacy Windows services to containerized linux microservices on AWS, improving reliability, scalability, and cost efficiency.
- Designed and implemented infrastructure as code using Terraform and Packer for repeatable, auditable deployments.
- Built POCs to integrate MongoDB, Redis, Kafka, and RabbitMQ with early ASP.NET Core versions, addressing compatibility gaps.
- Automated CI/CD pipelines with Jenkins to deploy containerized microservices with zero-downtime releases.

**[The Utech Group – illumyx](https://survey.illumyx.com/login)** • _Full Stack (AngularJS, Bootstrap, D3, C#, ASP.NET Core, Azure)_

- Developed a survey and analytics platform that provides insights into corporate culture.
- Built tools for survey distribution, data analysis, and visualization.

**[Miller Welding – Insight Core](https://insight.millerwelds.com/)** • _Full Stack (Knockout, Highcharts, C#, ASP.NET Core, Azure)_

- Enhanced dashboards displaying real-time telemetry data from connected welders.

### **[Mercury Marine – CDS G3](https://service.mercurymarine.com/)** | _Software Developer Intern_ | May 2013 – Dec 2013 | Oshkosh, WI

**Tech:** C#, WPF, .NET, Microsoft SQL Server, C, VMware

- Enhanced a desktop application for configuring and diagnosing engine and vessel control systems.
- Created a CI/CD build server using VMware and JetBrains TeamCity to automate regression testing.
- Debugged applications communicating with embedded systems via CAN bus.

### **[UW Platteville – Economics Research](https://scholar.google.com/citations?user=1ipdzgEAAAAJ&hl=en)** | _Research Software Developer_ | Mar 2011 – May 2013

**Tech:** C++

- Sole developer for an economics research project analyzing the impact of R&D spending.
- Created a console app to generate weighted network models to predict sectoral economic growth based on innovation investment data from IMF and World Bank.

> _More detailed list of employers & projects on [LinkedIn](https://linkedin.com/in/breyk)_

---

## Open Source Contributions

Contributed to major open-source ecosystems to improve developer experience, remove blockers, and modernize tooling.

- **[angular/angular](https://github.com/angular/angular):** Added compiler diagnostics to detect missing imports, aiding standalone component migrations.
- **[microsoft/TypeScript](https://github.com/microsoft/TypeScript):** Corrected compiler documentation to address undocumented conditional default values.
- **[ReactiveX/rxjs](https://github.com/ReactiveX/rxjs):** Fixed type inference in the `partition` operator to preserve type safety.
- **[storybookjs/storybook](https://github.com/storybookjs/storybook):** Resolved Angular-specific bugs in v7 to enable visual regression testing.
- **[compodoc/compodoc](https://github.com/compodoc/compodoc):** Fixed tests and CI issues, expediting a release to support signal-based inputs in downstream storybook.
- **[vitejs/vite](https://github.com/vitejs/vite):** Modernized TypeScript documentation to align with current best practices.

> _Additional contributions on [GitHub](https://github.com/manbearwiz)_

## Technical Skills

### Frontend

- **Languages:** TypeScript, JavaScript, SASS/SCSS
- **Frameworks:** Angular, React, Redux, D3, single-spa
- **Components & Styling:** Tailwind CSS, Angular Material, Material-UI, Bootstrap
- **Tools:** Webpack, Vite, Storybook, create-react-app, esbuild, ESLint, Prettier, Biome
- **Testing:** Jasmine, Jest, Playwright, Karma, Vitest

### Backend

- **Languages:** C#, Python, Node.js, Java
- **Frameworks:** ASP.NET Core, Express, GraphQL, Starlette

### Data & Search

- **Databases:** PostgreSQL, SQL Server, Redis, MongoDB, MySQL, SQLite
- **Search:** OpenSearch, Elasticsearch, Apache Lucene, MongoDB Atlas Search, MarkLogic

### Infrastructure & DevOps

- **Infrastructure as Code:** Terraform, Packer, CloudFormation
- **Containerization & Orchestration:** Docker, Kubernetes
- **CI/CD:** GitHub Actions, Jenkins, Azure Pipelines, TeamCity, Travis CI
- **Source Control:** Git, GitHub, Bitbucket, Azure DevOps, Apache Subversion

### Observability

- **Datadog:** Dashboards, APM, RUM, SLOs

### Cloud Platforms

- **AWS:** EC2, ECS, Lambda, RDS, S3, CloudFront, ElastiCache, OpenSearch, IAM
- **Azure:** App Services, Functions, Blob Storage, CDN, SQL Database
