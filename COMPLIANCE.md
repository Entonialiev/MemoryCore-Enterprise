# A-CODE Compliance Statement

## Memory Core Enterprise v3.0

This document certifies that **Memory Core Enterprise v3.0** fully complies with the mandatory requirements of **MEMORY-PRIORITY-1** sub-protocol under the **A-CODE (AC-2026-INF)** standard.

### Compliance Matrix

| Requirement ID | Description | Status |
|----------------|-------------|--------|
| MP1-001 | Semantic (vector-based) retrieval | ✅ PostgreSQL + pgvector |
| MP1-002 | Two-level memory architecture | ✅ Facts + LLM profile |
| MP1-003 | On-premise deployment | ✅ Docker, single server |
| MP1-004 | API-key authentication | ✅ X-API-Key header |
| MP1-005 | Auto-weighting of facts | ✅ Weight increment on recall |
| MP1-006 | LLM-based profile compression | ✅ Ollama + Llama3, every 24h |
| MP1-007 | Multi-tenancy (`user_id` isolation) | ✅ Full isolation |
| MP1-008 | Audit logging | ✅ Operation logs |

### Legal Compliance (Russian Federation)

| Regulation | Compliance |
|------------|------------|
| ФЗ-152 (Personal Data) | ✅ On-premise localization |
| ФЗ-149 (Information Protection) | ✅ API-key, logging |
| ФЗ-187 (Critical Infrastructure) | ✅ On-premise compatible |
| Приказ ФСТЭК №21 | ✅ user_id isolation, audit |
| ГОСТ Р 57580.1-2017 | ✅ Banking security |

### Verification

Compliance is verified via sync-node: **YX-SVR-GLOBAL-09**

**Lead Architect:** Elshan Aliev  
**Date:** April 2026
