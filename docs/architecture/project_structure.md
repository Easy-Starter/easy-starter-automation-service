easy-starter-automation-service/
├── .github/
│ ├── workflows/
│ │ ├── ci.yml
│ │ └── security.yml
│ └── pull_request_template.md
│
├── docs/
│ ├── architecture/
│ ├── deployment/
│ ├── development/
│ └── decisions/
│
├── specs/
│ └── README.md
│
├── src/
│ └── easy_starter_automation/
│ ├── api/
│ │ ├── dependencies.py
│ │ ├── errors.py
│ │ ├── router.py
│ │ └── routes/
│ │ ├── health.py
│ │ ├── jobs.py
│ │ └── webhooks/
│ │ └── example.py
│ │
│ ├── core/
│ │ ├── config.py
│ │ ├── constants.py
│ │ ├── exceptions.py
│ │ ├── logging.py
│ │ └── security.py
│ │
│ ├── db/
│ │ ├── base.py
│ │ ├── session.py
│ │ ├── models/
│ │ │ ├── inbound_event.py
│ │ │ └── job_run.py
│ │ └── repositories/
│ │
│ ├── integrations/
│ │ ├── base.py
│ │ ├── http.py
│ │ └── example/
│ │
│ ├── services/
│ │ ├── event_service.py
│ │ └── job_service.py
│ │
│ ├── tasks/
│ │ ├── celery_app.py
│ │ ├── base.py
│ │ ├── routing.py
│ │ ├── schedules.py
│ │ └── example.py
│ │
│ ├── main.py
│ └── **init**.py
│
├── migrations/
│ ├── versions/
│ └── env.py
│
├── tests/
│ ├── unit/
│ ├── integration/
│ ├── factories/
│ └── conftest.py
│
├── scripts/
│ ├── entrypoint.sh
│ ├── wait_for_services.py
│ └── generate_secret.py
│
├── .dockerignore
├── .editorconfig
├── .env.example
├── .gitignore
├── .pre-commit-config.yaml
├── AGENTS.md
├── Dockerfile
├── Makefile
├── compose.yml
├── compose.prod.yml
├── pyproject.toml
├── README.md
└── uv.lock
