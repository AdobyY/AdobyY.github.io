---
title: Resume
layout: resume
icon: fas fa-id-card
order: 5
toc: false
---

# Bohdan Yarinko

<div class="resume-hero">
  <p class="resume-role">Software Engineer | Python Backend &amp; Data Engineering</p>
</div>

<p class="resume-contact"><i class="fas fa-envelope" aria-hidden="true"></i> <a href="mailto:yarinko.b@gmail.com">yarinko.b@gmail.com</a><span>·</span><i class="fab fa-linkedin" aria-hidden="true"></i> <a href="https://www.linkedin.com/in/bohdan-yarinko-338816269/">LinkedIn</a><span>·</span><i class="fab fa-github" aria-hidden="true"></i> <a href="https://github.com/AdobyY">GitHub</a></p>

## <i class="fas fa-user-tie resume-section-icon" aria-hidden="true"></i> Summary

Software Engineer with hands-on experience designing, building, deploying, and operating production systems end-to-end - from high-volume data pipelines and backend services to frontend applications, infrastructure, CI/CD, monitoring, and business automation.

Since 2024, I have been building software for Europarts Ukraine, where my responsibilities grew from data engineering and supplier integrations into architecture and technical ownership of the company's core product-data, pricing, PIM, ecommerce, and infrastructure systems.

Built and maintain systems operating with approximately 2-3 million products and more than 10 million price records, including automated supplier-data pipelines, pricing engines, product-information management, large-scale web scraping and data enrichment, AI-assisted translation, internal business applications, high-volume search, and two production B2B ecommerce platforms.

Technical ownership of several production systems; coordinated implementation with another developer.

Since May 2026, I have also been one of the key engineers behind Pascore, a commercial product-data automation platform being developed from the company's internal engineering experience into a reusable product for other businesses.

Comfortable taking ownership of a technical problem from requirements and architecture through implementation, deployment, monitoring, and production support. Coordinate project implementation and the work of an assisting developer.

## <i class="fas fa-briefcase resume-section-icon" aria-hidden="true"></i> Experience

### Software Engineer / Technical Project Lead

**Europarts Ukraine** · March 2024 - Present

Design and develop internal software platforms, data infrastructure, automation systems, and B2B ecommerce applications used across the company's product-data and sales operations. My role covers data engineering, backend and frontend development, system architecture, integrations, infrastructure, production operations, technical planning, and project coordination.

- Designed and built the core data architecture used to process supplier information for a catalog of approximately 2-3 million products.
- Built automated pipelines that receive and process millions of supplier product records on a recurring basis, significantly reducing the amount of manual product-data processing required.
- Developed data-processing and ecommerce systems operating with 10+ million price records.
- Designed systems covering the complete product-data lifecycle: supplier ingestion, normalization, matching, enrichment, translation, pricing, search, PIM management, ecommerce publishing, and external feeds.
- Built production systems used by internal managers, pricing specialists, customers, and external business partners.
- Took ownership not only of application development but also of production deployment, Linux infrastructure, databases, monitoring, and troubleshooting.
- Coordinate development work with an assisting developer, break business requirements into implementation tasks, and make architecture and technology decisions.

### Software Engineer / Technical Project Lead

**Commercial Product Initiative - Europarts Ukraine (Pascore)** · May 2026 - Present

Alongside continued development and support of Europarts Ukraine systems, currently designing and building Pascore, a commercial Product Data Automation System intended for deployment at other companies.

- Pascore takes the experience gained from building internal data pipelines, PIM, pricing, automation, and ecommerce systems and turns it into a reusable software product.
- Designed its modular architecture with separate backend and frontend applications, external APIs, isolated customer environments, infrastructure automation, observability, and AI integrations.
- Responsible for core platform functionality: product management, categories, brands, attributes, product translations, product mappings, pricing, imports, exports, users, roles and permissions, search, integrations, API access, background processing, and automation.
- Designed integrations for external APIs, databases, FTP, XML, CSV, XLSX, and supplier feeds.
- Designed a reusable pricing engine with multiple price types, configurable pricing rules, supplier coefficients, category- and brand-based conditions, currencies, configurable coefficients, and manual overrides.
- Built separated frontend/backend architecture using React, TypeScript, and REST APIs.
- Designed API-first integration with Django REST Framework, OpenAPI, authentication, authorization, and integrations.
- Implemented and continue developing Model Context Protocol (MCP) support, exposing selected functionality as controlled tools for AI systems.
- Designed an AI assistant integrated directly with Pascore data and business functionality.
- Designed multi-customer infrastructure: isolated environments, separate databases, containerized deployments, centralized observability, secure administrative access, automated provisioning, repeatable deployments, and backups.
- Automated cloud infrastructure provisioning and Linux configuration using Terraform / OpenTofu and Ansible.
- Built current Pascore infrastructure on Hetzner, with WireGuard private administrative access, self-hosted Coolify, GitHub CI/CD, and centralized Grafana, Loki, and Promtail observability.
- Developed, designed and deployed the [Pascore product website](https://pas-core.com).
- Designed a reusable B2B ecommerce storefront to be offered together with Pascore.

## <i class="fas fa-project-diagram resume-section-icon" aria-hidden="true"></i> Selected Projects

### Product Data Platform & Data Warehouse

Designed the company's product-data processing architecture for receiving heterogeneous supplier data and converting it into a normalized internal product model.

- Designed database structures supporting millions of products, prices, supplier offers, categories, brands, stock records, and related product information.
- Built automated ETL/ELT pipelines with Python, SQL, dbt, and Apache Airflow.
- Set up scheduled synchronization and transformation workflows for continuously updating product information.
- Integrated internal and external data sources through databases, APIs, FTP, CSV, XLSX, XML, and other feeds.
- Built a DuckDB-based processing and data-warehouse layer for transforming large datasets.
- Migrated heavy data transformations from MySQL-based processing to DuckDB, reducing pipeline runtime from approximately 2 hours to around 2.5 minutes.
- Developed stable product-identification mechanisms across heterogeneous supplier systems.
- Built product, brand, and category normalization and mapping processes.
- Optimized multi-million-row processing jobs and resolved production memory and performance issues.

<p class="project-diagram-intro">The diagram below outlines the end-to-end flow from supplier ingestion and orchestration through data-warehouse transformations, internal business systems, APIs, and B2B delivery.</p>

<a class="project-diagram" href="{{ '/img/resume/data-platform-delivery-architecture.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open Data Platform and Delivery Architecture diagram in full size"><img src="{{ '/img/resume/data-platform-delivery-architecture.png' | relative_url }}" alt="Data Platform and Delivery Architecture diagram" loading="lazy"></a>

### Pricing Management Platform

Designed and developed an internal system used by employees responsible for company pricing.

- Designed the pricing data model and calculation architecture.
- Built configurable pricing rules based on category, brand, supplier, supplier coefficients, currency, customs costs, transportation costs, VAT, category-specific margins, and other business conditions.
- Implemented multiple price types, rule priorities, and manual pricing overrides.
- Developed interfaces that let responsible employees change pricing behaviour without changing application code.
- Integrated the pricing engine directly into product-data processing pipelines.

### Product Information Management Platform

Expanded the product-data and pricing systems into a centralized PIM platform for company employees.

- Built centralized management of millions of product records.
- Implemented product, category, brand, attribute, description, and translation management.
- Developed user accounts, roles, permissions, and access-control mechanisms.
- Built supplier-import and product-export functionality.
- Implemented background processing with Redis and Celery.
- Integrated Meilisearch for high-performance product search.
- Built APIs for external and internal applications.

### [euro-parts.com.ua](https://euro-parts.com.ua)

Designed, developed, deployed, and maintain a production B2B ecommerce platform connected directly to the company's product-data infrastructure.

- Operates with approximately 2-3 million products and more than 10 million price records.
- Implemented Meilisearch product search for fast full-text retrieval across a multi-million-product catalog.
- Implemented customer-specific pricing and multiple price types connected to internal pricing and product-data systems.
- Implemented search analytics and collaborated on technical SEO requirements with an external SEO company.
- Personally deployed and operate Linux servers, PostgreSQL, Redis, Celery, Meilisearch, Docker, Nginx, Gunicorn, logging, monitoring, backups, and deployment updates.

<p class="project-diagram-intro">The diagram below shows the production architecture behind the B2B application, including application services, infrastructure, observability, and external integrations.</p>

<a class="project-diagram" href="{{ '/img/resume/b2b-application-production-architecture-final-clean.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open B2B Application Production Architecture diagram in full size"><img src="{{ '/img/resume/b2b-application-production-architecture-final-clean.png' | relative_url }}" alt="B2B Application Production Architecture diagram" loading="lazy"></a>

### [findtechsupply.com](https://findtechsupply.com)

Designed, developed, and deployed a second production B2B ecommerce platform built around the same product-data engineering experience.

- Backend development, product catalog integration, search, pricing, product synchronization, and external integrations.
- Infrastructure configuration, deployment, production operation, and troubleshooting.

### [pas-core.com](https://pas-core.com)

Developed and deployed the product website, including development, deployment, server and domain configuration, CI/CD, and production operation.

<p class="project-diagram-intro">The diagram below presents the Pascore platform architecture, connecting product-data workflows, business services, integrations, infrastructure, and delivery channels.</p>

<a class="project-diagram" href="{{ '/img/resume/pascore-full-platform-architecture.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open Pascore platform architecture diagram in full size"><img src="{{ '/img/resume/pascore-full-platform-architecture.png' | relative_url }}" alt="Pascore platform architecture diagram" loading="lazy"></a>

### [Military Aircraft Image Classification](https://github.com/AdobyY/ImageClassificationSystem)

Developed an image-classification system capable of recognizing different types of military aircraft.

- Computer-vision datasets and image preprocessing.
- Neural networks, deep learning, model training, validation, classification metrics, and model evaluation.

### NLP Classification & Model Fine-Tuning

Worked on NLP classification tasks where models had to be adapted to task-specific labelled datasets.

- Text preprocessing, labelled datasets, and classification.
- Model fine-tuning, training and validation workflows, evaluation metrics, and experimentation with model performance.

### Kaggle & Machine Learning Competitions

Worked with Kaggle datasets and participated in machine-learning and NLP competitions.

- Exploratory data analysis, dataset cleaning, feature and input preparation.
- Model training, evaluation, classification tasks, NLP, experiment iteration, and competition metric improvement.

## <i class="fas fa-layer-group resume-section-icon" aria-hidden="true"></i> Technical Skills

<div class="tech-groups" aria-label="Technical stack">
  <section class="tech-group">
    <p class="tech-group-label"><i class="fas fa-code" aria-hidden="true"></i> Application & APIs</p>
    <div class="tech-chip-list">
      <span class="tech-chip"><img src="https://cdn.simpleicons.org/python/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Python</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/django/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Django</span><span class="tech-chip"><i class="fas fa-plug" aria-hidden="true"></i>Django REST Framework</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/flask/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Flask</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/react/8ab4f8?viewbox=auto" alt="" aria-hidden="true">React</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/javascript/8ab4f8?viewbox=auto" alt="" aria-hidden="true">JavaScript</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/typescript/8ab4f8?viewbox=auto" alt="" aria-hidden="true">TypeScript</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/html5/8ab4f8?viewbox=auto" alt="" aria-hidden="true">HTML</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/css/8ab4f8?viewbox=auto" alt="" aria-hidden="true">CSS</span><span class="tech-chip"><i class="fas fa-code" aria-hidden="true"></i>REST APIs</span><span class="tech-chip"><i class="fas fa-file-code" aria-hidden="true"></i>OpenAPI</span><span class="tech-chip"><i class="fas fa-shield-alt" aria-hidden="true"></i>OAuth2</span><span class="tech-chip"><i class="fas fa-window-maximize" aria-hidden="true"></i>API-driven frontend</span>
    </div>
  </section>

  <section class="tech-group">
    <p class="tech-group-label"><i class="fas fa-database" aria-hidden="true"></i> Data, Search & Processing</p>
    <div class="tech-chip-list">
      <span class="tech-chip"><img src="https://cdn.simpleicons.org/postgresql/8ab4f8?viewbox=auto" alt="" aria-hidden="true">PostgreSQL</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/mariadb/8ab4f8?viewbox=auto" alt="" aria-hidden="true">MariaDB</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/redis/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Redis</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/meilisearch/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Meilisearch</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/duckdb/8ab4f8?viewbox=auto" alt="" aria-hidden="true">DuckDB</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/apacheairflow/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Apache Airflow</span><span class="tech-chip"><i class="fas fa-database" aria-hidden="true"></i>dbt</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/celery/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Celery</span><span class="tech-chip"><i class="fas fa-table" aria-hidden="true"></i>SQL</span><span class="tech-chip"><i class="fas fa-exchange-alt" aria-hidden="true"></i>ETL/ELT</span><span class="tech-chip"><i class="fas fa-warehouse" aria-hidden="true"></i>Data warehouse</span><span class="tech-chip"><i class="fas fa-sitemap" aria-hidden="true"></i>Data modelling</span><span class="tech-chip"><i class="fas fa-clock" aria-hidden="true"></i>Batch processing</span><span class="tech-chip"><i class="fas fa-sync-alt" aria-hidden="true"></i>Data synchronization</span><span class="tech-chip"><i class="fas fa-search" aria-hidden="true"></i>Data normalization</span>
    </div>
  </section>

  <section class="tech-group">
    <p class="tech-group-label"><i class="fas fa-server" aria-hidden="true"></i> Infrastructure & Operations</p>
    <div class="tech-chip-list">
      <span class="tech-chip"><img src="https://cdn.simpleicons.org/linux/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Linux</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/docker/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Docker</span><span class="tech-chip"><i class="fas fa-layer-group" aria-hidden="true"></i>Docker Compose</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/nginx/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Nginx</span><span class="tech-chip"><i class="fas fa-server" aria-hidden="true"></i>Gunicorn</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/hetzner/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Hetzner Cloud</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/coolify/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Coolify</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/ansible/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Ansible</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/terraform/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Terraform</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/opentofu/8ab4f8?viewbox=auto" alt="" aria-hidden="true">OpenTofu</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/wireguard/8ab4f8?viewbox=auto" alt="" aria-hidden="true">WireGuard</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/grafana/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Grafana</span><span class="tech-chip"><i class="fas fa-stream" aria-hidden="true"></i>Loki</span><span class="tech-chip"><i class="fas fa-file-alt" aria-hidden="true"></i>Promtail</span><span class="tech-chip"><i class="fas fa-file-alt" aria-hidden="true"></i>Application logging</span><span class="tech-chip"><i class="fas fa-eye" aria-hidden="true"></i>Infrastructure monitoring</span><span class="tech-chip"><i class="fas fa-cubes" aria-hidden="true"></i>Containerized development</span><span class="tech-chip"><i class="fas fa-rocket" aria-hidden="true"></i>Production deployment</span><span class="tech-chip"><i class="fas fa-bug" aria-hidden="true"></i>Production troubleshooting</span>
    </div>
  </section>

  <section class="tech-group">
    <p class="tech-group-label"><i class="fas fa-robot" aria-hidden="true"></i> Automation, AI & Delivery</p>
    <div class="tech-chip-list">
      <span class="tech-chip"><img src="https://cdn.simpleicons.org/n8n/8ab4f8?viewbox=auto" alt="" aria-hidden="true">n8n</span><span class="tech-chip"><i class="fab fa-microsoft" aria-hidden="true"></i>Microsoft 365</span><span class="tech-chip"><i class="fas fa-bolt" aria-hidden="true"></i>Power Automate</span><span class="tech-chip"><i class="fas fa-envelope" aria-hidden="true"></i>Outlook</span><span class="tech-chip"><i class="fas fa-key" aria-hidden="true"></i>Microsoft Entra ID</span><span class="tech-chip"><i class="fas fa-brain" aria-hidden="true"></i>LLM integrations</span><span class="tech-chip"><i class="fas fa-robot" aria-hidden="true"></i>AI-assisted automation</span><span class="tech-chip"><i class="fas fa-language" aria-hidden="true"></i>AI translation</span><span class="tech-chip"><i class="fas fa-toolbox" aria-hidden="true"></i>MCP</span><span class="tech-chip"><i class="fas fa-cogs" aria-hidden="true"></i>Machine learning</span><span class="tech-chip"><i class="fas fa-network-wired" aria-hidden="true"></i>Deep learning</span><span class="tech-chip"><i class="fas fa-language" aria-hidden="true"></i>NLP</span><span class="tech-chip"><i class="fas fa-image" aria-hidden="true"></i>Image classification</span><span class="tech-chip"><i class="fas fa-microchip" aria-hidden="true"></i>Model fine-tuning</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/git/8ab4f8?viewbox=auto" alt="" aria-hidden="true">Git</span><span class="tech-chip"><img src="https://cdn.simpleicons.org/github/8ab4f8?viewbox=auto" alt="" aria-hidden="true">GitHub</span><span class="tech-chip"><i class="fas fa-code-branch" aria-hidden="true"></i>CI/CD</span>
    </div>
  </section>
</div>

## <i class="fas fa-bolt resume-section-icon" aria-hidden="true"></i> Automation & Business Integrations

Experience building automated business workflows using n8n, Microsoft 365, APIs, and AI. One production-oriented workflow processes incoming customer product requests:

> Incoming email → AI classification → product search → result analysis → AI-generated response → Outlook draft → employee review.

Experience includes n8n, Microsoft Power Automate, Microsoft 365, Outlook, Microsoft Entra ID, OAuth2, REST APIs, AI integrations, internal product-search APIs, and human-in-the-loop automation.

## <i class="fas fa-drafting-compass resume-section-icon" aria-hidden="true"></i> Technical Leadership & Project Ownership

Translate business needs into technical solutions; design architecture; select technologies; break projects into tasks; coordinate implementation with an assisting developer; review approaches; make decisions across backend, data, infrastructure, and frontend; plan and perform deployments; investigate production failures; prioritize improvements; maintain systems after launch; own projects from requirements through production operation.

## <i class="fas fa-chart-line resume-section-icon" aria-hidden="true"></i> Selected Engineering Scale

2-3 million products in production systems; 10+ million price records; millions of product translations; scraping and enrichment on millions of products; recurring processing of millions of supplier records; multi-source integrations; production full-text search at catalog scale; two production B2B ecommerce platforms; full-stack scope across data, backend, frontend, infrastructure, and monitoring; multiple production Linux servers and containerized services.

## <i class="fas fa-graduation-cap resume-section-icon" aria-hidden="true"></i> Education

### National Technical University of Ukraine "Igor Sikorsky Kyiv Polytechnic Institute"

**Master's Degree - Systems Analysis** · 2024 - 2025

Studied software systems, mathematical and systems modelling, data analysis, programming, machine learning, and deep learning. Focus areas included systems analysis, programming, data processing, machine learning, deep learning, mathematical modelling, model training and evaluation, and working with structured and unstructured datasets.

### National Technical University of Ukraine "Igor Sikorsky Kyiv Polytechnic Institute"

**Bachelor's Degree - Economic Cybernetics** · 2020 - 2024

Studied the intersection of economics, information systems, quantitative analysis, and programming. Focus areas included programming, information systems, economics, statistics, quantitative analysis, mathematical modelling, business-process analysis, and data analysis.

## <i class="fas fa-award resume-section-icon" aria-hidden="true"></i> Professional Strengths

End-to-end ownership of software systems; strong Python and backend foundation with practical data-engineering experience; systems design around real business processes; ability to work across backend, data, frontend, infrastructure, and deployment layers; production experience with large catalogs and high-volume pricing data; Linux and production troubleshooting; integration-heavy systems; strong software and business/data workflow understanding; experience coordinating another developer and taking technical ownership.
