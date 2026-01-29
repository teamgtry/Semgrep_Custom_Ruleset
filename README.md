# Semgrep\_Custom\_Ruleset

[SAST\_Automation](https://github.com/teamgtry/SAST_Automation)



# Semgrep Custom Ruleset 🔍



이 저장소는 오픈소스 웹 서비스(CMS)를 대상으로  

보안 취약점을 정적 분석(SAST)하기 위해 제작한 Semgrep 커스텀 룰셋입니다.



기존 Semgrep 기본 룰(Default Rules)로는 탐지하기 어려운  

실제 공격 시나리오 기반 취약점을 중심으로 룰을 설계했습니다.



---



## 🎯 목적 (Purpose)



\- 오픈소스 웹 서비스 보안 분석 자동화

\- 기본 SAST 룰의 한계를 보완하는 도메인 특화 커스텀 룰 제공

\- 실제 취약점 검증(PoC) 가능한 룰 중심 설계



---



## 🧩 대상 기술 스택 (Target)



\- Backend

&nbsp; - Python (Frappe / ERPNext)

&nbsp; - Java (JSP, Spring 기반 프로젝트)

&nbsp; - PHP 기반 CMS

\- Frontend

&nbsp; - JavaScript

\- Framework / Platform

&nbsp; - Paperless-ngx

&nbsp; - ERPNext

&nbsp; - Frappe

&nbsp; - Strapi

&nbsp; - Directus

&nbsp; - Chatwoot

&nbsp; - Mealie

&nbsp; - 기타 오픈소스 CMS 



---



## 🔐 다루는 취약점 유형 (Vulnerability Types)



\- SSRF (Server-Side Request Forgery)

\- XSS (Stored / Reflected / DOM-based)

\- SQL Injection

\- Path Traversal

\- Command Injection

\- Insecure Configuration

\- Authentication / Authorization Misconfiguration



---



## 📁 디렉터리 구조 (Structure)



```text

Semgrep\_Custom\_Ruleset/

├── rules/

│   ├── ssrf/

│   ├── xss/

│   ├── sqli/

│   ├── path\_traversal/

│   └── misc/

├── examples/

│   └── vulnerable\_code\_samples/

├── docs/

│   └── rule\_design\_notes.md

└── README.md



