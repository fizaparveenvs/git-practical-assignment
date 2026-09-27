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

## User Management

The user management module stores basic user information in `src/users.txt`.

Each user record contains:

- User ID
- Name
- Email

The feature branch `feature/user-management` is used to develop and document user-management functionality before merging it into the main branch.

## User Management

The user management functionality allows the system to store and manage user records.

## Account Management

The account management feature allows users to update their account information and preferences.
## Profile Management

The profile management feature allows users to maintain and update their profile information.

## Main Branch Update

This update was made on the main branch.

## Interactive Rebase Demo

This section demonstrates interactive rebase.
