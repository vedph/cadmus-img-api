﻿# Cadmus Imaging API

Quick Docker image build:

    docker build . -t vedph2020/cadmus-img-api:3.0.0 -t vedph2020/cadmus-img-api:latest

(replace with the current version).

This is a Cadmus API layer used to test the Cadmus imaging frontend components in their [shell](https://github.com/vedph/cadmus-img-shell).

## History

- 2024-11-20: updated packages.

### 5.0.0

- 2024-11-18: ⚠️ upgraded to .NET 9.
- 2023-11-21: updated packages.

### 4.0.0

- 2023-11-18: ⚠️ Upgraded to .NET 8.

### 3.0.0

- 2023-06-17: moved to PostgreSQL.
- 2023-06-02: updated packages.

### 2.0.0

- 2023-05-24: updated packages (breaking change in general parts introducing [AssertedCompositeId](https://github.com/vedph/cadmus-bricks-shell/blob/master/projects/myrmidon/cadmus-refs-asserted-ids/README.md#asserted-composite-id)).
- 2023-05-16: updated packages.
