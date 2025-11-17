# 📘 API Integration Glossary  
**Context:** Insurance Domain • MuleSoft • REST APIs

---

## 1. API (Application Programming Interface)
A set of rules and endpoints that allow two systems to interact programmatically.

## 2. REST (Representational State Transfer)
An architectural style for creating APIs using standard HTTP operations (GET, POST, PUT, DELETE).

## 3. HTTP Methods
- **GET** – Retrieve information
- **POST** – Create new resource
- **PUT** – Update/replace existing resource
- **PATCH** – Partially update a resource
- **DELETE** – Remove a resource

## 4. JSON (JavaScript Object Notation)
Lightweight text-based format for data exchange — commonly used in REST APIs.

## 5. XML (Extensible Markup Language)
Structured markup language used for integration with legacy, regulatory, or enterprise systems.

## 6. MuleSoft Anypoint Platform
Unified platform for building, deploying, managing, and securing APIs and integrations.

## 7. Mule Runtime (MuleSoft Runtime Engine)
Execution environment for Mule applications, flows, transformations, and connectors.

## 8. API-led Connectivity
MuleSoft design approach dividing APIs into:
- **System APIs** – Expose core system data (e.g., PAS, claims, billing)
- **Process APIs** – Orchestrate, enrich, and combine data
- **Experience APIs** – Tailor data for specific channels (mobile, portal, agents)

## 9. PAS (Policy Administration System)
Core insurance platform for policy lifecycle: quote, bind, issue, endorsement, renewal, cancellation.

## 10. Claims Management System
Manages claim lifecycle including FNOL, adjudication, reserves, payments, settlement.

## 11. ESB (Enterprise Service Bus)
Middleware enabling routing, mediation, and transformation between systems (MuleSoft can act as ESB).

## 12. DataWeave
MuleSoft’s transformation language for mapping and converting data formats (JSON, XML, CSV, Java).

## 13. API Gateway
Component enforcing authentication, authorization, throttling, rate limiting, caching, and analytics.

## 14. OAuth / Access Token
Token-based authorization standard for secure client-to-API communication.

## 15. TLS / HTTPS
Encryption protocols used to secure data exchange between API consumers and providers.

## 16. Error Handling / Fault Management
Standardized approach to detect, categorize, log, and return meaningful errors (e.g., 400/401/404/500).

## 17. Orchestration
Combining multiple data calls, business rules, and transformations into one end result.

## 18. Idempotency
Operation property where repeated identical requests produce the same result — critical in payments and claims.

## 19. SLA (Service Level Agreement)
Contract defining uptime, latency, throughput, and reliability commitments for exposed APIs.

## 20. API Contract / RAML / OAS
Formal documentation specifying endpoint structure, payloads, headers, and response codes:
- **RAML** – Common within MuleSoft
- **OpenAPI / Swagger** – Industry-standard interface description

---
