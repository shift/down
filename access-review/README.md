# The Access Review

> 📍 Late Game · 9 decisions made

Security audit. "Who has SSH access to production?"

Everyone. Including 12 people who left the company. Including 3 who were fired. Including one who was fired for cause and still has their SSH key.

*The Capital One breach (2019): a former AWS employee exploited an SSRF vulnerability to access 100M customer records. She had legitimate access to the infrastructure — the vulnerability was in the application layer. Access control failed at the boundary between what the cloud allowed and what the application should have exposed.*

---

- [Revoke all access, re-issue to current team only](../harden)
- [Clean it up quietly before the report is filed](../harden)
- [That's an IT problem](./notmyjob)
