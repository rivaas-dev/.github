<p align="center">
  <img src="https://raw.githubusercontent.com/rivaas-dev/artwork/main/dist/svg/logo-alpine.svg" alt="Rivaas" width="200">
</p>

<h3 align="center">A fast, ready-to-use API framework for Go</h3>

<p align="center">
  <a href="https://rivaas.dev">Website</a> •
  <a href="https://rivaas.dev/docs/">Docs</a> •
  <a href="https://pkg.go.dev/rivaas.dev/app">pkg.go.dev</a>
</p>

---

**Rivaas** is a Go web framework that comes with everything you need to build APIs.
You write your handlers — Rivaas takes care of the rest.

It gives you fast routing, input validation, automatic API docs, and built-in observability with OpenTelemetry. No need to glue together a dozen libraries.

### What you get

- **Very fast routing** — handles over 15 million requests per second
- **Automatic API docs** — generates OpenAPI specs and comes with Swagger UI
- **Observability built in** — metrics, tracing, and structured logging, ready from the start
- **12 middleware included** — things like CORS, rate limiting, compression, and auth
- **Works great with Kubernetes** — health probes, graceful shutdown, and config reload
- **Use what you need** — pick the full framework or just the packages you want

### Our repositories

| Repository | What it is |
|---|---|
| [rivaas](https://github.com/rivaas-dev/rivaas) | The framework itself — routing, validation, config, observability, and more |
| [docs](https://github.com/rivaas-dev/docs) | Source for the [documentation site](https://rivaas.dev/docs/) |
| [rivaas.dev](https://github.com/rivaas-dev/rivaas.dev) | Source for the [project website](https://rivaas.dev) |
| [artwork](https://github.com/rivaas-dev/artwork) | Logos, icons, and brand assets |

### Try it out

```go
go get rivaas.dev/app@latest
```

### License

Apache License 2.0
