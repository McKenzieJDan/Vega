# Vega - Standardized Development Guidelines for Cursor

A comprehensive collection of standardized development guidelines implemented as Cursor rules that can be applied across all your projects, ensuring consistency and quality regardless of technology stack.

[![Cursor](https://img.shields.io/badge/Cursor-Rules-blue.svg)](https://cursor.sh/docs/rules)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen.svg)](https://github.com/yourusername/Vega/graphs/commit-activity)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](https://github.com/yourusername/Vega/pulls)

## 🔑 Features

* 📏 **Technology-agnostic guidelines** that work across all programming languages and frameworks
* 🔄 **Cursor rules integration** for AI-assisted development with context-aware guidance
* 🚀 **Ready-to-use rule templates** for common development scenarios
* 📊 **Comprehensive coverage** of coding style, git workflow, code review, and documentation
* 🔧 **Easily customizable** to fit your team's specific needs and preferences

## Overview

Vega provides a structured approach to maintaining consistent development practices across all your projects by leveraging Cursor's rules system. Instead of recreating guidelines for each new project, you can reference these standardized rules and customize them as needed.

### Rule Categories

* `.cursor/rules/coding-style.md` - General coding style guidelines
* `.cursor/rules/git-commits.md` - Conventional Commits format for git messages
* `.cursor/rules/code-review.md` - Guidelines for code review process
* `.cursor/rules/development-philosophy.md` - Core development principles
* `.cursor/rules/documentation.md` - Standards for project documentation

### Configuration

* `.cursor/settings.json` - Cursor IDE configuration settings

## Installation

### Option 1: Copy the Rules

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Vega.git
   ```

2. Copy the `.cursor` directory to your project root:
   ```bash
   cp -r Vega/.cursor /path/to/your/project/
   ```

3. Customize the rules as needed for your specific project

### Option 2: Reference as a Submodule

1. Add this repository as a submodule to your project:
   ```bash
   git submodule add https://github.com/McKenzieJDan/Vega.git .vega
   ```

2. Create a symbolic link to the `.cursor` directory:
   ```bash
   ln -s .vega/.cursor .cursor
   ```

## License

If you find Vega helpful, consider [buying me a coffee](https://www.paypal.com/paypalme/mckenzio) ☕

## License

[MIT License](LICENSE)

Made with ❤️ by [McKenzieJDan](https://github.com/McKenzieJDan)