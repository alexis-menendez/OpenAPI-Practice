# OpenAPI Practice

This repository is a personal playground for learning and experimenting with the [OpenAPI Specification (OAS)](https://spec.openapis.org/oas/latest.html) — a standard for designing and documenting RESTful APIs in a language-agnostic and machine-readable format.

## ⚠️ Disclaimer

This repository was created as a self-directed learning project to explore OpenAPI on my own time. It is intended purely for experimentation and may contain incomplete, rough, or in-progress specifications. While the examples may not reflect production-ready standards, the goal is to deepen my understanding through hands-on practice.

## Purpose

To gain hands-on experience with:
- Writing OpenAPI 3.0+ specifications in YAML and JSON
- Designing API endpoints and modeling schemas
- Documenting request/response formats, parameters, and status codes
- Exploring versioning and reuse through `$ref` and component objects
- Understanding how OpenAPI integrates with API tooling (e.g., Swagger UI, Redoc)

## Tools & Technologies

- **OpenAPI 3.0+** (specification)
- **YAML / JSON**
- (Optional) **Swagger Editor**
- (Optional) **Redoc**
- (Optional) **VS Code Extensions** like OpenAPI linting plugins

## Getting Started

> These steps will guide you through creating and validating your first OpenAPI document.

### Prerequisites

- Basic knowledge of REST APIs
- Familiarity with YAML or JSON
- A text editor (e.g., VS Code)
- (Optional) [Swagger Editor](https://editor.swagger.io/) or [Redocly CLI](https://github.com/Redocly/cli)

### Steps

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/OpenAPI-Practice.git
   cd OpenAPI-Practice

2. Navigate to the starter spec:
   ```bash
   cd examples/basic-api

3. Open openapi.yaml in your preferred editor and explore the structure.

4. (Optional) Open the spec in Swagger Editor:
- Visit https://editor.swagger.io
- Copy-paste the contents of openapi.yaml into the editor
- View the interactive documentation

5. (Optional) Validate your spec with the Redoc CLI:
   ```bash
   npm install -g @redocly/cli
   redocly lint openapi.yaml

## Folder Structure

```bash
OpenAPI-Practice/
├── examples/
│   ├── basic-api/            # A minimal OpenAPI 3.0 spec
│   └── advanced-components/  # Experiments with reusable schemas and parameters
├── docs/                     # Notes, articles, or reference guides
└── README.md                 # This file
```

## Resources

[**OpenAPI Specification**](https://spec.openapis.org/oas/latest.html)

[**Swagger Editor**](https://editor.swagger.io/)

[**Redocly CLI**](https://redocly.com/docs/cli)

[**OpenAPI Tutorial (by Swagger)**](https://swagger.io/docs/specification/v3_0/about/)

[**OpenAPI Style Guide (Google)**](https://cloud.google.com/apis/design)
