# Zeno Docs

Bank statements and invoices processing service for the **ZenoN-Cloud** platform.

This service is responsible for:
- Receiving and storing raw bank statements and invoices (GCS)
- Parsing documents (Google Cloud Document AI and custom logic)
- Normalizing transactions and document metadata
- Exposing APIs for ZenoN-Cloud frontends and internal services

## Dependencies

- **Auth / Identity:** [Zeno Auth](https://github.com/ZenoN-Cloud/zeno-auth)
- **Infrastructure:** [Zeno Infra](https://github.com/ZenoN-Cloud/zeno-infra)

## Related services

- **Identity documents:** [Zeno ID Docs](https://github.com/ZenoN-Cloud/zeno-id-docs)
