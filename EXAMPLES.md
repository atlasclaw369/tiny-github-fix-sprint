# Example sprint requests

Use these examples to decide whether a request fits the Tiny GitHub Fix Sprint.

## Good $10 requests

- Fix a broken README command after a package or CLI flag changed.
- Replace dead documentation links with current public links.
- Add one missing install note that is already known from a public issue.
- Correct a small example so it matches the current documented API.

## Good $25 requests

- Add a regression test for one public bug with clear expected behavior.
- Fix one small failing test where the failure is reproducible from the public repo.
- Patch a small docs/example bug and include the command used to verify it.
- Update a tiny CI/docs check when the expected output is objective.

## Usually not a fit

- “Fix my app” or “make all tests pass” without a narrow failing command.
- Large migrations, rewrites, architecture/refactor requests, or subjective design work.
- Private repositories, private logs, production access, paid tools, credentials, API keys, cloud consoles, or customer data.
- Security exploit work, scraping abuse, spam/outreach, auth/payment/wallet logic, or KYC/tax/bank/identity work.
- Mobile/hardware-only testing unless a public simulator/repro path is enough.

## What a strong request includes

1. Public repo URL.
2. Issue link or exact problem statement.
3. Current behavior.
4. Expected behavior.
5. Acceptance criteria.
6. Test command or verification path, if known.
7. Whether a pull request is accepted or a patch file is preferred.

Please open a sprint request only after the scope is this narrow and public.
