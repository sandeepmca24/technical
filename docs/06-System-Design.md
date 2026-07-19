# System Design

Key patterns and approaches:
- Layered design: presentation, API, domain, data stores
- CQRS & Event Sourcing where strong auditability and complex workflows are needed
- Cache patterns: CDN for assets, in-memory caches for read-heavy operations
- Data partitioning and sharding for scale

Non-functional requirements (NFRs) drive design decisions: availability targets, RTO/RPO, latency budgets, throughput.
