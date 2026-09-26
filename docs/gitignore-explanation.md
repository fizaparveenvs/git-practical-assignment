# Gitignore Explanation

## `.env`

`.env` files commonly contain environment variables such as passwords, API keys and database credentials.

These values should generally not be committed to a public repository.

## `.env.*`

This pattern ignores environment-specific files such as:

```text
.env.local
.env.development
.env.production