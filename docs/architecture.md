# Architecture Overview

This document provides a high-level overview of the system architecture.

## System Components
- **Scanner Engine**: Identifies maintenance opportunities across code, metadata, dependencies, and documentation.
- **Planner**: Generates deterministic, bounded patch plans based on static rules and heuristics.
- **Sandbox Runner**: Executes tests and gate validations in isolated ephemeral environments.
- **Pull Request Manager**: Generates well-attributed, high-confidence maintenance PRs.
