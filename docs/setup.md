# Lab Environment Setup

## Overview

This document describes the environment used for the Lab, including the operating system, command-line tools, and version-control workflow.

The lab is designed to provide a practical environment for learning Linux administration, troubleshooting, networking, and systems engineering.

## Current Environment

| Component | Configuration |
|---|---|
| Lab operating system | Ubuntu Linux |
| Virtualisation | Ubuntu running in a virtual machine |
| Shell | Bash |
| Version control | Git |
| Remote repository | GitHub |
| Documentation format | Markdown |

## Linux Environment

Ubuntu is the primary environment for Linux exercises. Using a virtual machine provides an isolated system in which to practise commands, modify configuration, investigate failures, and recover from mistakes without unnecessarily affecting the host computer.

The lab will progressively cover:

- Filesystem navigation and management.
- File permissions and ownership.
- Processes, services, and system logs.
- Shell scripting and automation.
- Networking and troubleshooting.
- Linux system administration.

## Initial Environment Checks

Run the following commands inside the Ubuntu environment to inspect the system.

| Command | Purpose |
|---|---|
| `uname -a` | Display kernel and system information. |
| `uname -r` | Display the running kernel's release version. |
| `cat /etc/os-release` | Identify the Linux distribution and its version information. |
| `echo "$SHELL"` | Display the shell recorded in the environment. |
| `echo "$USER"` | Display the current user's environment variable. |
| `echo "$HOME"` | Display the current user's home directory. |
| `pwd` | Display the current working directory. |
| `git --version` | Display the installed Git version. |

These commands provide a baseline for understanding the environment in which each exercise is performed.

## Repository Workflow

The repository uses Git to track changes and GitHub to host the work remotely.

The typical workflow is:

1. Complete the practical exercise in the lab environment.
2. Document the commands, observations, results, and lessons learned.
3. Inspect changes with `git status` and, when useful, `git diff`.
4. Stage the relevant files with `git add`.
5. Create a descriptive commit with `git commit`.
6. Upload commits using `git push`.
7. Review the published files on GitHub.

## Lab Safety

- Verify the current directory before performing filesystem operations.
- Understand a command and its options before executing it.
- Use disposable test directories for destructive experiments.
- Avoid running commands with elevated privileges unless necessary and understood.
- Take virtual-machine snapshots before risky configuration changes.
- Never commit passwords, private keys, access tokens, or other secrets to GitHub.
