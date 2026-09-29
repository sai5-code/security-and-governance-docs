# Enterprise API Versioning & Deprecation Policy (v1.2)

## 1. Endpoint Sunset Schedule
- `/v1/payments/*` REST endpoints: Sunset Date November 1st, 2026.
- Migration Target: `/v2/checkout/gRPC` Protobuf schemas.
- Backward compatibility proxy limit: 50 requests/sec maximum throughput per client API key.
