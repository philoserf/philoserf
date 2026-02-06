# philoserf/philoserf

GitHub profile README repository for Mark Ayers (@philoserf).

## Repository purpose

This is a single-file repo containing only `README.md`. It renders as the GitHub profile page at <https://github.com/philoserf>. There is no code, build system, tests, or CI/CD.

## Key constraint

Keep this a single-file repo. Do not add files unless explicitly asked.

## README structure

The README uses a centered HTML layout (`<div align="center">`) with these sections in order:

1. Header — name, tagline, personal philosophy statement, motto
2. Technologies & Tools — shield badges
3. Philosophy — guiding principles
4. GitHub Stats — profile summary card images

## Content guidelines

- Maintain the personal voice and philosophy already established
- Keep the centered layout and existing section order
- Use shield.io badges for technologies
- GitHub stats cards come from `github-profile-summary-cards.vercel.app`

## Formatting

Markdown must pass `prettier`. Format with:

```bash
bunx prettier --write README.md
```
