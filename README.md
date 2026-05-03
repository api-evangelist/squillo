# Squillo

Squillo is a Software as a Utility (SaaU) platform that enables integration and automation of entire IT systems and human processes in minutes, not months. It provides a low-code/no-code approach to connecting enterprise applications, automating workflows, and orchestrating complex IT processes without traditional development overhead.

- **Website:** https://squillo.io/
- **Documentation:** https://squillo.io/

## APIs

### Squillo Platform API

The Squillo Platform API provides programmatic access to Squillo's integration and automation capabilities. Enables developers to manage workflows, connectors, integrations, and automation tasks programmatically. The API supports creating and managing integration flows, monitoring execution status, and configuring system connections.

- **Base URL:** https://api.squillo.io/v1
- **Documentation:** https://squillo.io/
- **OpenAPI:** [squillo-platform-openapi.yml](openapi/squillo-platform-openapi.yml)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [squillo-platform-openapi.yml](openapi/squillo-platform-openapi.yml) | Squillo Platform API for workflow and automation management |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [squillo-rules.yml](rules/squillo-rules.yml) | Spectral rules for Squillo API conventions |

### Capabilities

#### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [workflow-automation.yaml](capabilities/workflow-automation.yaml) | Unified workflow automation management capability |

#### Shared Definitions

| Shared | Description |
|--------|-------------|
| [platform.yaml](capabilities/shared/platform.yaml) | Squillo Platform API consumer definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [squillo-workflow-schema.json](json-schema/squillo-workflow-schema.json) | Workflow automation definition schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [squillo-workflow-structure.json](json-structure/squillo-workflow-structure.json) | Workflow structure documentation |

### JSON-LD

| Context | Description |
|---------|-------------|
| [squillo-context.jsonld](json-ld/squillo-context.jsonld) | JSON-LD context for Squillo platform vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [squillo-list-workflows-example.json](examples/squillo-list-workflows-example.json) | List active workflows example |
| [squillo-execute-workflow-example.json](examples/squillo-execute-workflow-example.json) | Execute workflow with input data example |

### Vocabulary

| Vocabulary | Description |
|-----------|-------------|
| [squillo-vocabulary.yml](vocabulary/squillo-vocabulary.yml) | Squillo platform domain vocabulary and terminology |
