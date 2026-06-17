# Environment Files

.env files often store private keys or API keys.

Rules:
- Never upload .env to GitHub.
- Add .env to .gitignore.
- Use separate keys for testing.
- Rotate keys if exposed.
- Never put seed phrases in a public repository.

A leaked private key should be considered compromised.
