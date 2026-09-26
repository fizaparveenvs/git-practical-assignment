# Git Practical Assignment

## Overview

This repository demonstrates practical Git and GitHub workflows used in software development.

The assignment covers repository setup, branching, commits, pull requests, merge conflicts, rebasing, stashing, cherry-picking, reverting, resetting, reflog recovery, Git bisect, tags, releases, GitHub Issues and code review.

## Project Structure

```text
git-practical-assignment/
├── README.md
├── .gitignore
├── src/
│   ├── app.txt
│   ├── users.txt
│   └── payments.txt
└── docs/
    └── architecture.md

## Payment Module

The payment module stores payment information in `src/payments.txt`.

Each payment record contains:

- Payment ID
- User ID
- Amount
- Currency
- Status

The payment module supports sample payment statuses including:

- SUCCESS
- PENDING
- FAILED