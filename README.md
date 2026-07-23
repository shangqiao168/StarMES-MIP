# StarMES-MIP

\# StarMES MIP Enterprise Edition



Manufacturing Intelligence Platform



Version: V1.0.0 Alpha



\---



\## Overview



StarMES MIP Enterprise Edition 是基于 Delphi XE7 + SQL Server 开发的新一代制造智能平台（Manufacturing Intelligence Platform）。



系统兼容传统 MES，并提供：



\- Work Order Management

\- Production Execution

\- Station Control

\- Anti-Theft System

\- SN Traceability

\- Workflow Engine

\- Rule Engine

\- Dashboard

\- Knowledge Center

\- AI Assistant

\- Digital Twin

\- REST API

\- Plugin Platform



\---



\## Architecture



```

Client (Delphi XE7)

&#x20;       │

&#x20;       ▼

Application Layer

&#x20;       │

&#x20;       ▼

Domain Layer

&#x20;       │

&#x20;       ▼

Infrastructure

&#x20;       │

&#x20;       ▼

SQL Server

```



\---



\## Project Structure



```

StarMES-MIP



apps/

core/

database/

sdk/

plugins/

deploy/

docs/

tests/

tools/

```



\---



\## Applications



\### Client



Delphi XE7 Desktop Client



\### API



REST API



\### Background Service



Windows Service



\### Dashboard



Realtime Dashboard



\---



\## Technology



Language



Delphi XE7



Database



Microsoft SQL Server



Pattern



DDD



Repository



Unit Of Work



Event Bus



Workflow Engine



Rule Engine



Plugin Framework



RESTful API



\---



\## Modules



System



Permission



Dictionary



Configuration



Manufacturing



Work Order



SN



Route



Station



Carrier



Repair



Alarm



Warehouse



Equipment



Quality



Knowledge



Dashboard



AI



Decision



Plugin



\---



\## Database



SQL Server



Database Name



StarMES\_MIP



Encoding



Unicode



\---



\## Coding Standard



Pascal Naming



Camel Case



No SQL in Forms



Repository Pattern



No Business Logic in UI



Use EventBus



Use Workflow Engine



Use Rule Engine



\---



\## Branch Strategy



main



develop



feature/\*



release/\*



hotfix/\*



\---



\## Version



V1.0.0 Alpha



