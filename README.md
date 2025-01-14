# FastAPI Users - Database adapter for Sync SQLAlchemy ORM

<p align="center">
  <img src="https://raw.githubusercontent.com/frankie567/fastapi-users/master/logo.svg?sanitize=true" alt="FastAPI Users">
</p>

<p align="center">
    <em>Ready-to-use and customizable users management for FastAPI</em>
</p>

[![build](https://github.com/furkan-guvenc/fastapi-users-db-sync-sqlalchemy/workflows/Build/badge.svg)](https://github.com/fastapi-users/fastapi-users/actions)
[![codecov](https://codecov.io/gh/furkan-guvenc/fastapi-users-db-sync-sqlalchemy/branch/master/graph/badge.svg)](https://codecov.io/gh/furkan-guvenc/fastapi-users-db-sync-sqlalchemy)
[![PyPI version](https://badge.fury.io/py/fastapi-users-db-sync-sqlalchemy.svg)](https://badge.fury.io/py/fastapi-users-db-sync-sqlalchemy)
[![Downloads](https://pepy.tech/badge/fastapi-users-db-sync-sqlalchemy)](https://pepy.tech/project/fastapi-users-db-sync-sqlalchemy)
<p align="center">
<a href="https://github.com/sponsors/frankie567"><img src="https://md-buttons.francoisvoron.com/button.svg?text=Buy%20me%20a%20coffee%20%E2%98%95%EF%B8%8F&bg=ef4444&w=200&h=50"></a>
</p>

---

**Documentation**: <a href="https://fastapi-users.github.io/fastapi-users/" target="_blank">https://fastapi-users.github.io/fastapi-users/</a>

**Source Code**: <a href="https://github.com/fastapi-users/fastapi-users" target="_blank">https://github.com/fastapi-users/fastapi-users</a>

---

Add quickly a registration and authentication system to your [FastAPI](https://fastapi.tiangolo.com/) project. **FastAPI Users** is designed to be as customizable and adaptable as possible.

**Sub-package for SQLAlchemy ORM support in FastAPI Users.**

## Development

### Setup environment

We use [Hatch](https://hatch.pypa.io/latest/install/) to manage the development environment and production build. Ensure it's installed on your system.

### Run unit tests

You can run all the tests with:

```bash
hatch run test
```

### Format the code

Execute the following command to apply `isort` and `black` formatting:

```bash
hatch run lint
```

## License

This project is licensed under the terms of the MIT license.
