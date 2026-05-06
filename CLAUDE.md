# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This repository is a sandbox for testing and learning GitHub Actions workflows.

## Structure

- `.github/workflows/` - GitHub Actions workflow definitions
- Workflow files use YAML format (`.yaml` or `.yml`)

## GitHub Actions Development

When creating or modifying workflows:
- Workflows are triggered by events defined in the `on:` key
- Jobs run on GitHub-hosted runners specified by `runs-on:`
- Use `actions/checkout@v4` to access repository code in workflows
- Test workflow changes by pushing to a branch and monitoring the Actions tab
