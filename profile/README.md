<p align="center">
    <a href="https://spiral.dev"><img alt="Spiral Framework" src="https://user-images.githubusercontent.com/773481/228578125-8e0ad713-905f-4450-a473-5839bd650472.png" style="width: 6in; display: block"></a>
</p>

<p align="center">A modern PHP framework designed to power faster, cleaner, superior software development</p>

<div align="center">

[![Documentation](https://img.shields.io/badge/Documentation-blue?style=for-the-badge&logo=gitbook&logoColor=white)](https://spiral.dev/docs)
[![Discord](https://img.shields.io/discord/538114875570913290?style=for-the-badge&logo=discord&labelColor=7289d9&logoColor=white&color=39456d)](https://discord.gg/spiralphp)
[![Sponsor](https://img.shields.io/static/v1?style=for-the-badge&label=&message=Sponsor&logo=githubsponsors&logoColor=white&color=%23EA4AAA)](https://github.com/sponsors/spiral)

</div>

<br />

[Spiral Framework](https://github.com/spiral/framework) runs PHP applications in long-living workers on [RoadRunner](https://roadrunner.dev): HTTP, queues, gRPC, Temporal workflows and more, with over sixty PSR-compatible components.

## Get Started

```bash
composer create-project spiral/app my-app
```

The installer asks which application to build — Web, CLI or gRPC — and which components to add, then writes their configs and downloads RoadRunner.

To see the result first, browse [spiral/app](https://github.com/spiral/app): a Web application with Cycle ORM, Stempler templates, queues, cache and sample pages, built by the installer on each release.

## Bridges

Integrations with tools and services that live outside the framework.

| Package | Integrates | Version |
|---|---|---|
| [RoadRunner Bridge](https://github.com/spiral/roadrunner-bridge) | [RoadRunner](https://roadrunner.dev): HTTP, Jobs, KV, gRPC, Centrifugo, Metrics, Logger, Lock | [![](https://img.shields.io/packagist/v/spiral/roadrunner-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/roadrunner-bridge) |
| [Temporal Bridge](https://github.com/spiral/temporal-bridge) | [Temporal](https://temporal.io) workflows and activities | [![](https://img.shields.io/packagist/v/spiral/temporal-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/temporal-bridge) |
| [Cycle ORM Bridge](https://github.com/spiral/cycle-bridge) | [Cycle ORM](https://cycle-orm.dev), database layer and migrations | [![](https://img.shields.io/packagist/v/spiral/cycle-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/cycle-bridge) |
| [OpenTelemetry Bridge](https://github.com/spiral/otel-bridge) | [OpenTelemetry](https://opentelemetry.io) tracing | [![](https://img.shields.io/packagist/v/spiral/otel-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/otel-bridge) |
| [Sentry Bridge](https://github.com/spiral/sentry-bridge) | [Sentry](https://sentry.io) error reporting | [![](https://img.shields.io/packagist/v/spiral/sentry-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/sentry-bridge) |
| [SAPI Bridge](https://github.com/spiral/sapi-bridge) | Classic PHP SAPI, such as PHP-FPM | [![](https://img.shields.io/packagist/v/spiral/sapi-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/sapi-bridge) |
| [Nyholm Bridge](https://github.com/spiral/nyholm-bridge) | [Nyholm](https://github.com/Nyholm/psr7) PSR-7 and PSR-17 implementation | [![](https://img.shields.io/packagist/v/spiral/nyholm-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/nyholm-bridge) |
| [Twig Bridge](https://github.com/spiral/twig-bridge) | [Twig](https://twig.symfony.com) template engine | [![](https://img.shields.io/packagist/v/spiral/twig-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/twig-bridge) |
| [Data Grid Bridge](https://github.com/spiral/data-grid-bridge) | [Data Grid](https://github.com/spiral/data-grid) specifications in Spiral applications | [![](https://img.shields.io/packagist/v/spiral/data-grid-bridge.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/data-grid-bridge) |

## Packages

Standalone packages beyond the framework core.

| Package | Purpose | Version |
|---|---|---|
| [gRPC Client](https://github.com/spiral/grpc-client) | gRPC client with interceptors, retries and connection failover | [![](https://img.shields.io/packagist/v/spiral/grpc-client.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/grpc-client) |
| [Idempotency](https://github.com/spiral/idempotency) | At-least-once leases and exactly-once inbox for operations | [![](https://img.shields.io/packagist/v/spiral/idempotency.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/idempotency) |
| [JSON Schema Generator](https://github.com/spiral/json-schema-generator) | JSON Schema from DTO classes | [![](https://img.shields.io/packagist/v/spiral/json-schema-generator.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/json-schema-generator) |
| [Validator](https://github.com/spiral/validator) | Validation chains with an array-based DSL | [![](https://img.shields.io/packagist/v/spiral/validator.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/validator) |
| [Data Grid](https://github.com/spiral/data-grid) | Filtering, sorting and pagination specifications | [![](https://img.shields.io/packagist/v/spiral/data-grid.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/data-grid) |
| [Attributes](https://github.com/spiral/attributes) | PHP attributes reader | [![](https://img.shields.io/packagist/v/spiral/attributes.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/attributes) |
| [Testing](https://github.com/spiral/testing) | Testing SDK for Spiral applications | [![](https://img.shields.io/packagist/v/spiral/testing.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/testing) |
| [Dumper](https://github.com/spiral/dumper) | Variable dumper for HTML, logs and CLI | [![](https://img.shields.io/packagist/v/spiral/dumper.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/dumper) |
| [Code Style](https://github.com/spiral/code-style) | Shared PHP CS Fixer rules | [![](https://img.shields.io/packagist/v/spiral/code-style.svg?style=flat-square&label=)](https://packagist.org/packages/spiral/code-style) |

More packages from the community — events, scheduler, validators, serializers and others — live in [Spiral Packages](https://github.com/spiral-packages).

## Our other projects

- [RoadRunner](https://roadrunner.dev) — high-performance PHP application server and process manager written in Go and powered with plugins.
- [Cycle ORM](https://cycle-orm.dev) — PHP DataMapper ORM and data modelling engine.
- [Buggregator](https://buggregator.dev) — local debugging server in one binary: errors, dumps, emails, logs, profiles and HTTP requests from your application in development.
