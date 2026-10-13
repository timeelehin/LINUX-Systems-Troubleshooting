# LINUX-Systems-Troubleshooting
A hands-on engineering lab documenting my journey through Linux administration. This repository contains practical exercises, lab notes, troubleshooting reports, scripts, and projects focused on understanding how systems work, diagnosing failures, and building reliable technical skills through practice.

My approach is built around a simple cycle:

**Learn → Build → Break → Fix → Document**

The goal is not just to learn commands or complete tutorials, but to develop practical skills, understand the reasoning behind system behaviour, and build evidence of that understanding through reproducible work.

## Learning Objectives

- Develop confidence working in Linux environments and the command line.
- Understand filesystem organisation, permissions, processes, services, and system administration.
- Build foundational knowledge of computer systems, operating systems, and networking.
- Develop shell scripting and automation skills.
- Learn to investigate system failures methodically using logs, diagnostic tools, and testing.
- Use Git and GitHub to document technical work and manage changes.
- Build practical projects that demonstrate progressively deeper systems and infrastructure knowledge.

## Repository Structure

```text
LINUX-Systems-Troubleshooting/
├── README.md
├── .gitignore
├── docs/
│   ├── setup.md
├── linux/
│   ├── week-01/
│   │   ├── README.md
│   │   ├── lab-notes.pdf
│   │   └── assignments/
│   ├── week-02/
│   └── ...
├── scripts/
│   └── README.md
├── troubleshooting/
│   └── README.md
└── projects/
    └── README.md
```

*The structure will evolve as new topics and projects are introduced. Not every directory or file listed above may exist yet.*

### Directory Guide

| Directory | Purpose |
|---|---|
| `docs/` | Environment setup, learning roadmap, and general documentation. |
| `linux/` | Weekly Linux lessons, exercises, lab notes, and assignments. |
| `scripts/` | Shell scripts and other utilities developed during practice. |
| `troubleshooting/` | Records of technical problems, investigations, fixes, and lessons learned. |
| `projects/` | Larger practical projects that combine multiple concepts. |

## Learning Methodology

Each topic is approached through practical work rather than passive consumption alone.

1. **Learn:** Study the underlying concepts, commands, tools, and system behaviour.
2. **Build:** Apply the concepts in a Linux virtual machine or another suitable lab environment.
3. **Break:** Introduce controlled faults or test failure scenarios where appropriate.
4. **Fix:** Investigate symptoms, identify root causes, and verify corrective actions.
5. **Document:** Record the process, commands, observations, mistakes, and conclusions.
6. **Review:** Revisit the work and test whether the concepts can be applied independently.

All destructive experiments are performed in controlled environments with appropriate precautions.

## Current Focus

### Linux Foundations and Administration

Current work focuses on becoming comfortable with the Linux command line and understanding the filesystem.

Topics include:

- Navigating the filesystem and understanding absolute and relative paths.
- Creating, copying, moving, renaming, and deleting files and directories.
- Reading files and working with command output.
- Using pipes and redirection.
- Understanding the Linux filesystem hierarchy.
- Managing file permissions and ownership.
- Writing and executing basic shell scripts.
- Using Git to track changes and document work.
- Connecting to systems using SSH.
- Investigating common Linux errors and failures.

The next stages will build on these foundations with more advanced system administration, processes and services, networking, automation, and infrastructure-related projects.

## Lab Notes and Assignments

Each learning unit may include:

- **Lab notes:** Summaries of concepts, commands, and observations.
- **Practical assignments:** Tasks completed independently to apply the material.
- **Command explanations:** Descriptions of what commands do and why they produce particular results.
- **Troubleshooting records:** Real errors encountered, diagnostic steps, root causes, and solutions.
- **Reflections:** Lessons learned, remaining questions, and areas requiring further practice.

The emphasis is on understanding and explaining the work, not simply recording commands that happened to succeed.

## Troubleshooting Documentation

Troubleshooting reports follow a consistent structure where applicable:

1. **Problem:** What was observed, and what was expected?
2. **Environment:** What system, tools, and conditions were involved?
3. **Investigation:** Which commands, logs, or tests were used?
4. **Diagnosis:** What was identified as the root cause, if known?
5. **Resolution:** What changes were made?
6. **Verification:** How was the fix tested?
7. **Lessons learned:** What did the investigation reveal about the system?

This approach helps develop systematic diagnostic skills instead of relying on guesswork or applying commands without understanding their effects.

## Tools and Environment

Tools will vary according to the exercise, but the learning environment may include:

- **Operating system:** Ubuntu Linux.
- **Virtualisation:** A virtual machine for isolated experimentation and recovery.
- **Shell:** Bash and standard Linux command-line utilities.
- **Version control:** Git and GitHub.
- **Scripting:** Bash, with Python where appropriate.
- **Networking:** Linux networking utilities and network simulation tools as topics progress.
- **Documentation:** Markdown and terminal-based notes.

Additional tools will be introduced when they serve a clear learning objective.

## Engineering Principles

The following principles guide the work in this repository:

- **Understand before automating.** Learn the underlying operation before writing a script to perform it.
- **Verify assumptions.** Check paths, permissions, command output, and system state rather than assuming success.
- **Investigate before fixing.** Collect evidence before changing system configuration.
- **Practise safely.** Use isolated lab environments for potentially destructive operations.
- **Document honestly.** Distinguish between what was attempted, what worked, and what remains unresolved.
- **Prefer reproducibility.** Record enough context for another person to understand or repeat an exercise.
- **Build progressively.** Develop reliable foundations before moving to more complex systems.

## Progress and Future Work

This repository is a work in progress. Its contents reflect my actual learning and practical development, rather than a completed curriculum or a claim of professional mastery.

As the lab develops, I intend to expand it with work involving:

- Linux system administration and troubleshooting.
- Processes, services, logs, and resource management.
- Shell scripting and task automation.
- Computer networking and network diagnostics.
- System programming and operating system fundamentals.
- Virtual machines and infrastructure management.
- Configuration management, containers, and deployment workflows.
- Cloud infrastructure and infrastructure as code.

These are learning directions, not claims that every topic has already been completed.

## About

I am a Computer Engineering graduate building practical foundations in systems engineering, Linux administration, and networking.

This repository serves as a record of that process: the exercises I complete, the problems I investigate, the tools I develop, and the understanding I gain along the way.

**The objective is to build demonstrable competence through consistent practice, careful investigation, and clear technical documentation.**
