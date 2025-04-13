# vaam-store Organization

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  <!-- Add your license file -->
[![GitHub Issues](https://img.shields.io/github/issues/vaam-store/.github)](https://github.com/vaam-store/.github/issues)
[![GitHub Pull Requests](https://img.shields.io/github/pulls/vaam-store/.github)](https://github.com/vaam-store/.github/pulls)

## Overview

Welcome to the `vaam-store` GitHub organization's `.github` repository!  This repository serves as a central hub for configuration, documentation, and tooling that affects all repositories within the `vaam-store` organization.  It's *not* the code for the vaam store itself, but rather supports its development and deployment.  It's the foundation for building a robust and scalable e-commerce platform.

This repository primarily contains:

*   **Organizational Configuration:** Settings and configurations that apply across all `vaam-store` repositories (e.g., issue templates, pull request templates, codeowners).
*   **Reusable Workflows:** GitHub Actions workflows that can be used in other repositories for CI/CD, testing, and deployment.
*   **Documentation:** Information about our development processes, standards, and infrastructure.
*   **Scripts & Tools:** Utility scripts and tools that are used to automate tasks related to the vaam store project.
*   **Kubernetes Manifests (Example):** Example or base Kubernetes manifests for local development/staging environments (not production).

**Important Note:** This repository focuses on *infrastructure* and *organization-level configuration*. The actual application code for vaam store lives in separate repositories.

## Goals

Our primary goals for the `vaam-store` organization (and reflected in this repository's contents) are:

*   **Standardize Development Practices:**  Ensure consistent development practices across all vaam store repositories.
*   **Automate CI/CD:** Streamline the CI/CD process for faster and more reliable deployments.
*   **Improve Code Quality:** Enforce code quality standards and best practices.
*   **Simplify Infrastructure Management:**  Make it easier to manage the infrastructure for the vaam store.
*   **Foster Collaboration:**  Create a collaborative environment where developers can easily share code and knowledge.

## Technologies & Infrastructure

The vaam store is built using the following core technologies:

*   **Backend:** Rust (with frameworks like Actix or Rocket)
*   **Databases:** PostgreSQL, Redis
*   **Frontend:** React (with Vite and/or Next.js)
*   **DevOps:** Kubernetes (for development and staging; production details may vary), GitHub Actions for CI/CD
*   **Other Tools:** Docker, Terraform (potentially for infrastructure provisioning)

This repository uses technologies like:

*   **YAML:** For configuration files (e.g., GitHub Actions workflows, Kubernetes manifests).
*   **Shell Scripting:** For utility scripts and automation tasks.
*   **Markdown:** For documentation.

## Getting Started

To use the resources in this repository:

1.  **Clone the repository:** `git clone git@github.com:vaam-store/.github.git`
2.  **Explore the contents:**  Familiarize yourself with the different directories and files.
3.  **Use the workflows:**  Copy and adapt the GitHub Actions workflows to your own repositories.
4.  **Refer to the documentation:**  Read the documentation to learn about our development processes and standards.
5.  **Adapt Kubernetes manifests:** Use/adapt the manifest files for local development.  *These are examples and likely need modification to fit your specific setup.*

**Example Structure:**
