# BraveGoggles-Configuration-Standard-Development-Kit

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/BraveGoggles-Configuration-Standard-Development-Kit/ci.yml?label=Build&style=flat-square)](https://github.com/chirag127/BraveGoggles-Configuration-Standard-Development-Kit/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/BraveGoggles-Configuration-Standard-Development-Kit?label=Coverage&style=flat-square)](https://codecov.io/gh/chirag127/BraveGoggles-Configuration-Standard-Development-Kit)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/BraveGoggles-Configuration-Standard-Development-Kit?style=flat-square)](https://github.com/chirag127/BraveGoggles-Configuration-Standard-Development-Kit)

**Star ⭐ this Repo**

---

## 🚀 Project Overview

This repository serves as the **Official Apex Standard Guide and Toolkit** for developing, validating, and deploying custom search ranking configurations, known as **Goggles**, for the Brave Search ecosystem. It enforces high-integrity configuration standards using modern validation schemas and automated CI/CD pipelines.

This toolkit standardizes the lifecycle of user-defined ranking algorithms, ensuring performance, security, and consistency across all community contributions.

## 🏗️ Architecture Diagram

The Goggles Configuration Lifecycle adheres to a strict validation pipeline:

ascii
+-----------------------------+
|   Goggles Configuration (.js) |
+-----------------------------+
              |
              v
+-----------------------------+
|    Apex Schema Validation   |
| (JSON Schema / TypeScript)  |
+-----------------------------+
              |
              v
+-----------------------------+
|      CI/CD Validation Run     |
| (Test Scripts / Linting)    |
+-----------------------------+
              |
              v
+-----------------------------+
|     Deployment to Registry    |
+-----------------------------+


## 📋 Table of Contents

1. [Project Overview](#-project-overview)
2. [Architecture Diagram](#-architecture-diagram)
3. [AI Agent Directives (Apex Alignment)](#-ai-agent-directives-apex-alignment)
4. [Development Standards](#-development-standards)
    * [Prerequisites](#prerequisites)
    * [Setup & Installation](#setup--installation)
    * [Core Scripts](#core-scripts)
5. [Contributing](#contributing)
6. [License](#license)

## 🤖 AI Agent Directives (Apex Alignment)

<details>
<summary>Click to view Apex Technical Authority Configuration for this Repository</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY AGENT DIRECTIVES (BraveGoggles-Configuration-Standard-Development-Kit)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect enforcing **Zero-Defect, High-Velocity** standards for Search Ranking Configuration deployment.
**Context:** This repository defines configuration standards for Brave Goggles. The core artifacts are JavaScript/JSON configuration files subject to rigorous validation.
**Output Standard:** Deliver **EXECUTION-ONLY** results, prioritizing schema correctness and verifiable pipeline success.

## 2. INPUT PROCESSING & COGNITION
*   **Semantic Correction:** When analyzing Goggles code, correct common JS syntax errors against the latest ECMAScript standard before validation. Assume configurations must run in a strict NodeJS environment.
*   **Research Anchor:** Use `linkup`/`brave` to search for the **latest Brave Search Goggles SDK documentation (2025/2026)** and the current **JSON Schema Draft standard** being enforced by Brave.
*   **Validation Commands:** Always run the integrated validation suite via `npm run validate` before suggesting any changes.

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **PRIMARY SCENARIO: CONFIGURATION VALIDATION & STANDARDS (JavaScript/TypeScript)**
    *   **Stack:** Leveraging **TypeScript 6.x** for schema definition fidelity, **Vite 7** for tooling, and **Biome** for linting/formatting adherence to modern JS standards. Testing relies on **Vitest** for fast unit checks and **Playwright** for integration sanity checks against sample results.
    *   **Architecture:** Configurations are treated as **Immutable Data Contracts**. The repository structure emphasizes **Data Definition First**, separated strictly from execution/testing logic.
    *   **Key Principle:** Configurations must strictly adhere to the principle of **Separation of Concerns (SOLID)**; ranking logic must be decoupled from environment definitions.

## 4. ARCHITECTURAL VERIFICATION COMMANDS
To align with Apex Authority, execute the following verification sequence:

1.  **Format & Lint Check:** `npm run format:check` (Ensure Biome compliance).
2.  **Schema Validation:** `npm run validate` (Verify all configuration files against the defined JSON schema).
3.  **Unit Test Execution:** `npm run test:unit` (Run Vitest suite for utility functions).
4.  **End-to-End Sanity Check:** `npm run test:e2e` (Use Playwright to simulate a simple Goggle injection against a mocked response).

</details>

## ⚙️ Development Standards

### Prerequisites
*   Node.js (v20.x LTS or newer)
*   npm (or uv/pnpm if switching package managers)

### Setup & Installation

1.  **Clone Repository:**
    bash
    git clone https://github.com/chirag127/BraveGoggles-Configuration-Standard-Development-Kit.git
    cd BraveGoggles-Configuration-Standard-Development-Kit
    
2.  **Install Dependencies (Using npm for universal compatibility):**
    bash
    npm install
    

### Core Scripts

| Script | Description | Verification Target |
| :--- | :--- | :--- |
| `npm run dev` | Starts the local development server/validator watcher. | Continuous Integration |
| `npm run test` | Runs Vitest unit tests and Playwright E2E checks. | Functional Correctness |
| `npm run validate` | Executes the primary configuration schema validation routine. | Data Contract Integrity |
| `npm run format` | Applies all Biome formatting rules across the project. | Code Style Adherence |

## 🤝 Contributing

Contributions are welcomed under the framework of **Future-Proofing and Standardization**. Please review the detailed guidelines in [.github/CONTRIBUTING.md](./.github/CONTRIBUTING.md) before submitting pull requests.

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](./LICENSE) file for details.
