# Enterprise Linux Automation Platform

An enterprise-style configuration management platform built with Ansible to
standardise, secure, test and operate Linux servers across development,
staging and production environments.

## Business Objective

The platform provides a controlled and repeatable way to configure Linux
servers while reducing manual administration, configuration drift and
operational risk.

## Core Capabilities

- Reusable Ansible roles
- Environment-specific inventories
- Linux security baselines
- User and access management
- SSH hardening
- Firewall configuration
- Package and service management
- Logging and monitoring
- Configuration drift detection
- Automated testing and quality gates
- Controlled release and deployment processes
- Operational runbooks and recovery procedures

## Repository Structure

```text
inventories/   Environment-specific server inventories
playbooks/     Top-level automation entry points
roles/         Reusable configuration roles
tests/         Automated role and integration testing
docs/          Architecture decisions, standards and runbooks
scripts/       Supporting engineering utilities
.github/       Continuous integration workflows