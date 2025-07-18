# Contributing Guidelines

Thank you for your interest in contributing to the **Public API Library**! We welcome additions and improvements from the community.

## Adding a New API

1. Ensure the API is **free and publicly accessible** (free tier is acceptable even if paid plans exist).
2. Use official documentation links (primary sources) whenever possible.
3. Open `free_api_library.md` and locate the appropriate category (e.g., Government, Finance, Health).
4. Add a new row to the table with the following columns:
   - **API Name** – the name of the API.
   - **Description** – a concise summary of what the API provides.
   - **Access & Limits** – note whether an API key is required and any notable rate limits or quotas.
   - **Docs Link** – hyperlink to the official documentation (use Markdown link syntax).
5. Keep entries alphabetized within each category.
6. Commit your change with a descriptive message such as `Add Open‑Meteo API`.

## Updating or Fixing an Entry

If you spot an error, outdated information, or a broken link:

1. Update the entry directly in `free_api_library.md`.
2. For broken links, replace them with an updated official link.
3. For changes to rate limits or features, adjust the entry accordingly and include a brief note in the commit message.

## Submitting Pull Requests

1. Fork this repository and create a branch for your changes.
2. Make sure your changes pass the automated link check workflow (see `.github/workflows` for details).
3. Open a pull request describing your changes and reference any related issues.
4. Your changes will be reviewed and merged once approved.

## Code of Conduct

Please be respectful and constructive in all interactions. By participating in this project you agree to uphold a positive and inclusive environment.
