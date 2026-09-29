# Daniel Schiavoni

**Product data engineer · Python · Ruby on Rails · REST APIs · PostgreSQL**

📍 Florianópolis, SC (BRT) · ✉️ daniel.schia@gmail.com · 💼 [linkedin.com/in/daniel-schiavoni](https://www.linkedin.com/in/daniel-schiavoni/)

---

## About

Backend developer with **13 months inside Salsify**, working on the product data
layer of a live PIM tenant: a Ruby on Rails application that ingested enterprise
client CSV files and generated adaptive, client-specific product forms inside the
platform — imports, mapping, attribute validation, required-field and completeness
rules, and bulk data processing. That is the domain most PIM and e-commerce
platform teams talk about, seen from the vendor side.

Now works in Python and Django, and builds tools for the same problems:
`pimlint` below validates a product feed against a channel schema and reports
every violation with line, column and reason.

Before tech, I worked as a journalist. It still shows up: I translate technical
problems clearly, work well with cross-functional teams, and write documentation
that actually helps the next person.

---

## Selected work

**[pimlint](https://github.com/danielschia/pimlint)** · Python, PyYAML, pytest
A product feed validator. Reads a CSV of products, compares it against a
declarative YAML schema per channel (required attributes, types, enums, length
limits, regex patterns) and reports each violation with line, column and reason,
ordered by severity. Computes a completeness score, detects columns outside the
schema, and returns non-zero exit codes for CI. 29 tests, CI across Python
3.11–3.13.

**[controle_epi](https://github.com/danielschia/controle_epi)** · Django, pytest, GitHub Actions
Inventory and loan management for personal protective equipment. Enforces record
validity at the model layer — stock-availability and date-consistency rules raise
`ValidationError`, backed by a database-level `CheckConstraint`. Also covers
role-based access via Django Groups and Permissions, a custom email auth backend,
idempotent management commands for repeatable data loads, and a pytest suite in CI.

**[trackrr-api](https://github.com/danielschia/trackrr-api)** · Flask, Flask-SQLAlchemy, Flask-JWT-Extended, Flask-OpenAPI3
REST API with JWT authentication, OpenAPI-generated documentation, and a service
layer that keeps business logic out of the route handlers.

---

## Experience

**Technical Support Engineer** · Duda Inc. *(Oct 2024 – Present)*
Diagnoses editor bugs and REST API integration issues on a website-builder
platform, reading and debugging code across multiple languages and frameworks to
find root causes. Documents and escalates defects with reproducible evidence —
logs, request/response traces — and acts as the technical reference for the
support queue.
`JavaScript` `REST APIs` `HTML` `CSS`

**Channel Support Engineer** · Salsify *(Sep 2023 – Oct 2024)*
Adapted a Ruby on Rails application that ingested enterprise client CSV files and
generated adaptive, client-specific product forms inside the Salsify platform —
the import, mapping and data-quality layer of a live PIM tenant in production use.
Owned data quality day to day: attribute validation, required-field and
completeness checks, and bulk import/export processing. Traced data discrepancies
back to the attribute or file causing them, and kept data-flow and platform
documentation current as client requirements changed.
`Ruby` `Rails` `SQL` · *PIM: Salsify, product data, CSV import/export, validation*

**Web Developer** · Business-monitor.ch *(Jun 2022 – Jul 2023)*
Evolved a 10-year-old Rails codebase for enterprise clients. Built an RSpec +
Cucumber suite from scratch reaching **85% coverage**, significantly reducing
regression bugs. Integrated Stripe payments and custom PostgreSQL queries.
`Ruby` `Rails` `PostgreSQL` `RSpec` `Cucumber` `Stripe`

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Ruby_on_Rails-D30001?style=flat-square&logo=ruby-on-rails&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square&logo=sqlite&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-6BA539?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Sidekiq](https://img.shields.io/badge/Sidekiq-DC382D?style=flat-square&logo=sidekiq&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![RSpec](https://img.shields.io/badge/RSpec-3B6427?style=flat-square&logo=rubygems&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-555?style=flat-square&logo=linux&logoColor=white)

---

## Also on GitHub

[mew_app](https://github.com/danielschia/mew_app) — Flask + React full-stack app
with a test suite and Render deploy config ·
[ped_mais](https://github.com/danielschia/ped_mais) — Ruby API project ·
[BM_test](https://github.com/danielschia/BM_test) and
[challenge-daniel-2022](https://github.com/danielschia/challenge-daniel-2022) —
take-home projects for Business-monitor.ch ·
[desenvolvimento_full_stack_puc](https://github.com/danielschia/desenvolvimento_full_stack_puc) —
PUC-Rio coursework

---

## Education

**Postgraduate Degree in Software Engineering** — PUC-Rio *(in progress; emphasis on Python)*
**Technical Course in Systems Development** — Senai-SC (2024–2026)
**Web Development Bootcamp** — Le Wagon
**Bachelor's Degree in Journalism** — Universidade do Vale do Itajaí (2012–2016)

---

## Languages

🇧🇷 Portuguese — Native · 🇬🇧 English — Fluent *(primary working language with U.S. enterprise clients at Salsify)* · 🇫🇷 French — Intermediate · 🇪🇸 Spanish — Intermediate

