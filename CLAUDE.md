# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Claude Code development template repository providing a pre-configured DevContainer environment. The repository is currently empty and serves as a starting point for development projects.

## Development Environment

This repository uses DevContainer for consistent development environments:

- **Base Environment**: Ubuntu-based container with Docker-in-Docker support
- **Pre-installed Tools**: 
  - Node.js LTS
  - Python 3 with pip and venv
  - Git, build tools, and common utilities
  - Claude Code CLI (`@anthropic-ai/claude-code`)
  - Docker CLI and Docker Compose

## Developer Scripts

The `scripts/` directory contains useful developer and maintainer commands:

- **`scripts/reuse`** - Wrapper for the REUSE license compliance tool using Docker container

Usage: `./scripts/reuse [command]` (e.g., `./scripts/reuse lint`)

## Getting Started

Since this is a template repository, you'll typically want to:

1. Initialize your specific project type (e.g., `npm init`, `cargo init`, `python -m venv`)
2. Add your project-specific dependencies and configuration files
3. Update this CLAUDE.md file with your project's specific build, test, and lint commands

## Current Project Status

This repository contains only DevContainer configuration and no actual project code. Once you add your project files, you should update this document with:

- Build commands for your specific technology stack
- Test commands and testing framework information
- Lint/formatting commands
- Project architecture and structure details