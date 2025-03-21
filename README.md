# Game Power Hammer

A streamlined, cross-platform GUI client for the Rust-based Game Power Hammer tool, built to simplify environment setup, build management, and source control integration for game developers.

## Overview

This client leverages Tauri for an intuitive and responsive graphical user interface, facilitating efficient interactions with a Rust-powered backend through gRPC.

## Features

### Role-Based Software Installation:
- Automatically fetch and install software tailored for roles such as Artist, Programmer, and Designer.
- Build Management: Initiate, package, and manage builds for Unreal Engine, Unity, and Godot.
- Streamlined client-side uploading and downloading of build artifacts.

### Project Configuration:
- Manage builds and custom actions via easily configurable manifest files (pipeline.toml). Support for custom scripts in Bash, Python, and Rust.

### Source Control Integration:
- Robust integration with Perforce and Git.
- Pre-submit checks and hooks for maintaining code quality and consistency.

##Technology Stack

- Tauri: Cross-platform GUI.
- Rust: Backend logic and CLI tools.
- gRPC: Fast, efficient, strongly-typed communication between client and server.

## Getting Started
- Clone the repository.
- Ensure Rust and Tauri dependencies are installed.
- Run the client:

```
cargo tauri dev
```

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

Designed for simplicity and extensibility, ideal for diverse and dynamic game development teams.
