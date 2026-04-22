# Copilot Instructions

## Project Overview

Perfect Repo is a standards-compliant demo API project used as the positive-case reference for the swe-standards compliance automation.

## Tech Stack

- Node.js 18+
- TypeScript
- Express

## Code Conventions

- Follow existing patterns in the codebase
- Use meaningful variable and function names
- Write tests for new functionality
- Controllers go in `src/controller/`, services in `src/service/`, repositories in `src/repository/`

## Architecture

Layered architecture: Controller → Service → Repository → Database.
See `docs/architecture.md` for details.

## Common Tasks

- **Install**: `npm install`
- **Run**: `npm start`
- **Test**: `npm test`
