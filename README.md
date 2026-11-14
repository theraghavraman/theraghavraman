<div align="center">
  <picture>
    <source media="(max-width: 640px)" srcset="./assets/profile-banner-mobile.svg" />
    <img src="./assets/profile-banner.svg" width="100%" alt="Hey, I’m Raghav Raman. I build ETL pipelines that stay healthy, browser tools that run locally, and a document retrieval system built with RAG and FAISS." />
  </picture>
</div>

<p align="center">
  <a href="https://theraghavraman.github.io/the_raghav_raman/"><img src="./assets/cta-portfolio.svg" width="180" alt="Portfolio" /></a>&nbsp;
  <a href="https://linkedin.com/in/theraghavraman"><img src="./assets/cta-linkedin.svg" width="180" alt="LinkedIn" /></a>&nbsp;
  <a href="https://orcid.org/0009-0006-6026-0674"><img src="./assets/cta-orcid.svg" width="180" alt="ORCID" /></a>
</p>

## What I do

I’m a Senior Software Engineer in data engineering at Capgemini, working on ETL and data integration. That covers everything from keeping scheduled loads healthy to designing SCD Type 1/2, file-processing and hierarchy-parsing pipelines. My everyday stack is Informatica IICS/IDMC, PowerCenter, SSIS, Azure Synapse, Oracle, DB2 and SQL.

After hours I build browser-based data tools and Python services, including a document Q&A system using FastAPI, LangChain, RAG and FAISS.

## Things I’ve built

The cards below link to live demos and source. The document Q&A system below them is source available, with local setup instructions.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/etl-validation-toolkit/"><img src="./assets/projects/etlguard.svg" width="100%" alt="ETLGuard, open the live app" /></a>
      <p>A Python data-quality toolkit for CSV, Excel and API feeds. Pydantic validation, rejected-row reports, transactional MySQL loads, SCD Type 2 history and safe batch retries. The browser demo runs the same validator through Pyodide.<br /><br />See the repository’s CI and release notes for current test and compatibility results.</p>
      <p><sub>Python, Pydantic, SQLAlchemy, MySQL, Pytest, Pyodide</sub></p>
      <p><a href="https://theraghavraman.github.io/etl-validation-toolkit/">Try the demo</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/etl-validation-toolkit">Source</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/etl-validation-toolkit/releases/latest">Latest release</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/redata/"><img src="./assets/projects/redata.svg" width="100%" alt="ReData, open the live app" /></a>
      <p>A browser-first analytics workspace powered by local DuckDB. It pulls data from databases, S3 and REST APIs into staging tables with full, append and upsert syncs.</p>
      <p><sub>JavaScript, Python, DuckDB, SQL</sub></p>
      <p><a href="https://theraghavraman.github.io/redata/">Open the app</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/redata">Source</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/codeproof/"><img src="./assets/projects/codeproof.svg" width="100%" alt="CodeProof, open the live app" /></a>
      <p>A local-first code verification lab: static checks, sandboxed test runs, Python grammar checks, SBOM generation and supply-chain audits.</p>
      <p><sub>JavaScript, TypeScript, Pyodide, GitHub Actions</sub></p>
      <p><a href="https://theraghavraman.github.io/codeproof/">Open the app</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/codeproof">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/omni_suite_light/"><img src="./assets/projects/omniconverter.svg" width="100%" alt="OmniConverter Studio, open the live app" /></a>
      <p>A private file and data toolkit for PDF, OCR, media and format conversion in the browser, with optional local Python and desktop engines.</p>
      <p><sub>JavaScript, Python, Electron</sub></p>
      <p><a href="https://theraghavraman.github.io/omni_suite_light/">Open the app</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/omni_suite_light">Source</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/space/"><img src="./assets/projects/space.svg" width="100%" alt="SPACE, open the live app" /></a>
      <p>An interactive observatory for exploring space-mission datasets.</p>
      <p><sub>JavaScript</sub></p>
      <p><a href="https://theraghavraman.github.io/space/">Open the app</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/space">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://theraghavraman.github.io/mindgames/"><img src="./assets/projects/mindgames.svg" width="100%" alt="Mind Games, open the live app" /></a>
      <p>Sudoku variants, logic puzzles and brain games in the browser.</p>
      <p><sub>HTML, JavaScript, CSS</sub></p>
      <p><a href="https://theraghavraman.github.io/mindgames/">Open the app</a> &nbsp;|&nbsp; <a href="https://github.com/theraghavraman/mindgames">Source</a></p>
    </td>
  </tr>
</table>

### Document retrieval: RAG Document Q&A

A FastAPI service that ingests documents and indexes their chunks with FAISS. Its retrieval code combines vector search with BM25 and returns source identifiers for cited answers. The [source](https://github.com/theraghavraman/rag-document-qa-production), [retrieval implementation](https://github.com/theraghavraman/rag-document-qa-production/blob/main/app/vector_index.py), and [local setup](https://github.com/theraghavraman/rag-document-qa-production#start-a-local-demo) are public. Its README states that live external-service integration and load testing have not yet been verified.

<details>
  <summary><strong>Still curious? Four more to poke at</strong></summary>
  <br />
  <ul>
    <li><a href="https://theraghavraman.github.io/sandbox/">Redmark Forge Sandbox</a>: steganography and data encoding (<a href="https://github.com/theraghavraman/sandbox">source</a>)</li>
    <li><a href="https://theraghavraman.github.io/periodic_tabularasa/">TabulaRasa</a>: an interactive periodic table (<a href="https://github.com/theraghavraman/periodic_tabularasa">source</a>)</li>
    <li><a href="https://theraghavraman.github.io/philosophy-quote-visualizer/">PHILOGRAPH</a>: a philosophy quote visualizer (<a href="https://github.com/theraghavraman/philosophy-quote-visualizer">source</a>)</li>
    <li><a href="https://theraghavraman.github.io/princeofparadox/">Prince of Paradox</a>: a thought engine (<a href="https://github.com/theraghavraman/princeofparadox">source</a>)</li>
  </ul>
</details>

## What I reach for

<p><strong>Data engineering</strong></p>

<table>
  <tr>
    <td align="center" width="110"><img src="./assets/icons/informatica.svg" width="34" height="34" alt="Informatica" /><br /><sub>Informatica</sub></td>
    <td align="center" width="110"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg" width="34" height="34" alt="SSIS" /><br /><sub>SSIS</sub></td>
    <td align="center" width="110"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" width="34" height="34" alt="Azure Synapse" /><br /><sub>Synapse</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/talend/FF6D70/FF8D8F" width="34" height="34" alt="Talend" /><br /><sub>Talend</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/snowflake/29B5E8/6DD5F5" width="34" height="34" alt="Snowflake" /><br /><sub>Snowflake</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/databricks/FF3621/FF6B5B" width="34" height="34" alt="Databricks" /><br /><sub>Databricks</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/apachekafka/231F20/F3F4F6" width="34" height="34" alt="Apache Kafka" /><br /><sub>Kafka</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/duckdb/FFF000/FFF000" width="34" height="34" alt="DuckDB" /><br /><sub>DuckDB</sub></td>
  </tr>
</table>

<p><strong>Databases</strong></p>

<table>
  <tr>
    <td align="center" width="110"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/oracle/oracle-original.svg" width="42" height="34" alt="Oracle" /><br /><sub>Oracle</sub></td>
    <td align="center" width="110"><img src="./assets/icons/ibm.svg" width="48" height="34" alt="IBM DB2" /><br /><sub>IBM DB2</sub></td>
    <td align="center" width="110"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg" width="34" height="34" alt="SQL Server" /><br /><sub>SQL Server</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/postgresql/4169E1/84ADFF" width="34" height="34" alt="PostgreSQL" /><br /><sub>PostgreSQL</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/mysql/4479A1/72AFC7" width="34" height="34" alt="MySQL" /><br /><sub>MySQL</sub></td>
  </tr>
</table>

<p><strong>Python and AI</strong></p>

<table>
  <tr>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/python/3776AB/75A8D3" width="34" height="34" alt="Python" /><br /><sub>Python</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/fastapi/009688/35C3B2" width="34" height="34" alt="FastAPI" /><br /><sub>FastAPI</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/pydantic/E92063/FF6F9D" width="34" height="34" alt="Pydantic" /><br /><sub>Pydantic</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/langchain/1C3C3C/A7F3D0" width="34" height="34" alt="LangChain" /><br /><sub>LangChain</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/meta/0467DF/73A7FF" width="34" height="34" alt="FAISS" /><br /><sub>FAISS</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/pytest/0A9EDC/67D9F5" width="34" height="34" alt="Pytest" /><br /><sub>Pytest</sub></td>
  </tr>
</table>

<p><strong>Cloud and delivery</strong></p>

<table>
  <tr>
    <td align="center" width="110"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original.svg" width="38" height="34" alt="AWS" /><br /><sub>AWS</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/googlecloud/4285F4/7EADFF" width="34" height="34" alt="Google Cloud" /><br /><sub>Google Cloud</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/docker/2496ED/63B3F4" width="34" height="34" alt="Docker" /><br /><sub>Docker</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/git/F05032/FF8068" width="34" height="34" alt="Git" /><br /><sub>Git</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/linux/FCC624/FCC624" width="34" height="34" alt="Linux" /><br /><sub>Linux</sub></td>
    <td align="center" width="110"><img src="https://cdn.simpleicons.org/githubactions/2088FF/75AEFF" width="34" height="34" alt="GitHub Actions" /><br /><sub>Actions</sub></td>
    <td align="center" width="110"><img src="./assets/icons/servicenow.svg" width="34" height="34" alt="ServiceNow" /><br /><sub>ServiceNow</sub></td>
  </tr>
</table>

## Certifications

- Oracle Cloud Infrastructure 2024 Generative AI Certified Professional
- Informatica IDMC Foundation
- Databricks Generative AI Fundamentals
- Google Advanced Data Analytics
- AWS Cloud Quest: Cloud Practitioner
- Snowflake Data Warehousing Workshop
- Confluent Fundamentals: Apache Kafka

<p align="center">
  <br />
  Got a data problem or an idea worth building? <a href="https://linkedin.com/in/theraghavraman">Say hi on LinkedIn.</a>
</p>
