# Response templates

Reusable replies for Small GitHub PR Sprint intake issues.

## Scope accepted / quote

```md
Thanks — this looks like a good fit for a Small GitHub PR Sprint.

**Scope:** [one narrow outcome]
**Delivery:** focused PR or patch file + verification note
**Price:** [$10 / $25 / $50+]
**ETA:** [24–72 hours after confirmation]
**Verification:** [command or public manual check]

Before I start, please confirm:

1. The scope above is correct.
2. External PRs are accepted, or patch-file delivery is OK.
3. Payment will be USDC on Base, Arbitrum, Linea, or Ethereum after scope confirmation.

Please do not send payment until the scope/price/ETA are confirmed in this thread.
```

## Needs narrowing

```md
Thanks for the request. I can only take this if we narrow it to one small, public, verifiable change.

Could you add:

1. The exact current behavior.
2. The exact expected behavior.
3. One acceptance criterion.
4. A test command or manual verification path, if known.

I cannot take broad refactors, private access, production/debugging access, security/auth/payment/wallet work, or tasks that require credentials.
```

## Decline / out of scope

```md
Thanks for the request. I’m going to decline this sprint because it is outside the fixed-scope lane:

- [reason: too broad / private access / credentials / auth-payment-security / no public proof path / not reproducible]

This service is only for small public docs/tests/examples/tiny-bug fixes with a clear verification path.
```

## Delivery note

```md
Done.

**What changed:** [summary]
**Delivery:** [PR URL or patch file]
**Verification:** [commands/checks run]
**Notes/limits:** [anything not verified]
**Payment/status:** [pending / paid]
```

## Payment wording

```md
Payment accepted in USDC on Base, Arbitrum, Linea, or Ethereum.

Address: `0x23151Ef76ae6404f0a5fF4FE3dd3551a4f563125`

Please confirm the network before sending. Buyer covers network fees. Do not send other assets unless explicitly agreed.
```
