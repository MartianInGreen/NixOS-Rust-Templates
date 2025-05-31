# NixOS Rust Templates

A collection of NixOS development environment templates for Rust projects. This repository provides a standardized development environment setup using Nix flakes, making it easy to get started with Rust development on NixOS.

## Features

- Pre-configured Rust development environment using Nix flakes
- Latest stable Rust toolchain with rust-src
- Essential development tools included:
  - rust-analyzer for IDE integration
  - rustfmt for code formatting
  - clippy for linting
  - lld for linking

## Prerequisites

- Nix package manager installed
- Flakes enabled in your Nix configuration

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/MartianInGreen/NixOS-Rust-Templates.git
   cd NixOS-Rust-Templates
   ```

2. Enter the development shell:
   ```bash
   nix develop
   ```

3. Start developing! The development environment includes:
   - Latest stable Rust toolchain
   - Rust source code for better IDE integration
   - Common development tools

## Development Environment

The development environment is configured in `flake.nix` and includes:

- Latest stable Rust toolchain
- rust-analyzer for IDE integration
- rustfmt for code formatting
- clippy for linting
- lld for linking
