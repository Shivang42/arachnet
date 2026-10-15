# Arachnet

Arachnet is a scalable Web API vulnerability scanner designed to identify security issues based on the OWASP API Security Top 10.
It leverages Celery for distributed task execution and thread orchestration for high-performance concurrent scanning.

Arachnet is built for security engineers, pentesters, and developers who need an automated and extensible way to assess API security at scale.

## Features

  Scans APIs against OWASP API Security Top 10

  Celery-based task queue for distributed and asynchronous execution

  Thread orchestration for high-throughput scanning

  Scalable architecture (single-node or distributed workers)

  Structured vulnerability findings

  Modular and extensible scanner design

  Safe-by-default scanning (non-destructive where possible)

  OWASP API Security Top 10 Coverage

Arachnet focuses on identifying the following classes of vulnerabilities:

  API1: Broken Object Level Authorization (BOLA)
  
  API2: Broken Authentication
  
  API3: Broken Object Property Level Authorization
  
  API4: Unrestricted Resource Consumption
  
  API5: Broken Function Level Authorization (BFLA)
  
  API6: Unrestricted Access to Sensitive Business Flows
  
  API7: Server-Side Request Forgery (SSRF)
  
  API8: Security Misconfiguration

  API9: Improper Inventory Management
  
  API10: Unsafe Consumption of APIs


<img width="961" height="1184" alt="image" src="https://github.com/user-attachments/assets/4d316d75-7cfc-4b9c-af8d-f1c5ad3b4c39" />
