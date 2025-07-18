# Solana Curriculum Repository

This repository contains a collection of courses and materials for learning Solana development. It is structured as a Turborepo monorepo to manage the different course modules and shared utilities.

## Repository Structure

The main content is organized within the `courses` directory. Each subdirectory in `courses` represents a specific course:

- [`courses/blockchain-basics`](courses/blockchain-basics/course-plan.md): Blockchain Basics
- [`courses/rust-basics-for-solana-development`](courses/rust-basics-for-solana-development/course-plan.md): Rust Basics for Solana Development
- [`courses/anchor-and-programs`](courses/anchor-and-programs/course-plan.md): Anchor and Programs
- [`courses/spl-tokens-2022-and-extensions`](courses/spl-tokens-2022-and-extensions/course-plan.md): SPL Tokens, 2022 and Extensions
- [`courses/web-for-solana-development-101`](courses/web-for-solana-development-101/course-plan.md): Web for Solana Development 101

The monorepo also includes standard Turborepo packages:

- `@repo/eslint-config`: ESLint configurations.
- `@repo/typescript-config`: TypeScript configurations.

### Utilities

This Turborepo has some additional tools already set up:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) (LTS version recommended)

### Installation

1. Clone the repository:
   ```sh
   git clone TODO add repo url
   cd solana-curriculum-repository
   ```
2. Install dependencies using Bun:
   ```sh
   bun install
   ```
