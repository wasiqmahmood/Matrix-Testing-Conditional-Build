# Matrix Testing & Conditional Build Assignment

This project demonstrates GitHub Actions workflow with matrix testing and conditional builds.

## Features

- ✅ Matrix testing across Node.js versions 16, 18, and 20
- ✅ Conditional build on main branch or version tags
- ✅ Artifact storage for test results and build outputs
- ✅ Manual approval before publishing
- ✅ Scheduled nightly tests
- ✅ Workflow dispatch with skip option

## Setup

1. Clone this repository
2. Run `npm install` to install dependencies
3. Run `npm test` to execute tests
4. Run `npm run build` to build the project

## GitHub Actions

The workflow is defined in `.github/workflows/ci.yml` and includes:
- Test matrix across Node.js versions
- Conditional build steps
- Artifact storage
- Manual approval process
