# Perfect Repo

A standards-compliant demo project — the positive case for [swe-standards](https://github.com/jkordick/swe-standards) compliance checks.

## Prerequisites

- [Node.js](https://nodejs.org/) >= 18
- npm >= 9

## Quick Start

```bash
git clone https://github.com/jkordick/perfect-repo.git
cd perfect-repo
npm install
npm start
```

## API Endpoints

| Method | Endpoint       | Description         |
|--------|---------------|---------------------|
| GET    | `/health`     | Health check        |
| GET    | `/api/items`  | List all items      |
| POST   | `/api/items`  | Create a new item   |

## Project Structure

```
perfect-repo/
├── src/
│   ├── controller/     # Route handlers
│   ├── service/        # Business logic
│   ├── repository/     # Data access
│   └── model/          # Domain models
├── docs/
│   └── architecture.md
├── .github/
│   └── copilot-instructions.md
├── CONTRIBUTING.md
├── SECURITY.md
├── LICENSE
└── README.md
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT — see [LICENSE](LICENSE).
