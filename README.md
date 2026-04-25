# DiseasesPlugin

Minecraft Paper/Spigot plugin that adds configurable disease mechanics to a server.

> The repository is currently named `diesease`; the project itself is **DiseasesPlugin**.

## Features

- Disease-related commands
- Admin reload/give/infect/cure permissions
- Configurable plugin resources
- Maven-based Java 17 build

## Requirements

- Java 17+
- Paper/Spigot 1.20+
- Maven

## Build

```bash
mvn clean package
```

The compiled plugin jar will be generated in `target/`.

## Commands

```text
/diseases reload
/diseases give
/diseases infect
/diseases cure
```

## Permissions

```yaml
diseases.admin
diseases.reload
diseases.give
diseases.infect
diseases.cure
```

## Notes

Do not commit generated build output such as `target/`, `.class`, or `.jar` files. Releases should be uploaded through GitHub Releases.
