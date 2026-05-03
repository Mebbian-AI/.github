# Contributing to Mebbian

Mebbian engineering follows one rule:

**No unreviewed changes to production-critical code.**

## Branch naming

Use clear branch prefixes:

- `feature/`
- `fix/`
- `chore/`
- `docs/`
- `infra/`
- `refactor/`
- `test/`

## Pull requests

Every PR should explain:

1. What changed.
2. Why it changed.
3. How it was tested.
4. Risks.
5. Follow-up work.

## Secrets

Never commit secrets.

Use `.env.example` for required variables.
