# Engineering Standards

## WordPress Standards

- Follow WordPress coding standards where practical.
- Escape all output.
- Sanitise all input.
- Use nonces for state-changing requests.
- Check capabilities before admin actions.
- Keep database table names prefixed.
- Never store secrets in source control.

## PHP Standards

- PHP 8.0+ minimum.
- Use namespaces.
- Keep classes focused.
- Avoid business logic in templates.
- Prefer small services over large god classes.
- Avoid hard-coded copy where settings or templates are appropriate.

## Database Standards

- Every table must have a clear owner module.
- Every table must document purpose and relationships.
- Use indexes for common lookups.
- Log important activity.
- Avoid storing personally sensitive data unless needed.

## Security Standards

- Principle of least privilege.
- Audit important actions.
- Do not expose private reports publicly without tokens/authentication.
- Treat AI prompts and outputs as potentially sensitive.
- Make export/delete options part of long-term GDPR planning.

## Release Standards

Every release should include:

- changelog
- upgrade notes
- installation notes
- QA checklist
- known limitations
