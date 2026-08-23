# renovate-config

Shared Renovate preset. Every managed repo extends this via a stub `renovate.json`:

```json
{ "extends": ["github>jrodeiro5/renovate-config"] }
```

Rules mirror the retired self-hosted `~/renovate/config.js` (7-day minimumReleaseAge
cooldown against supply-chain worms, minor/patch automerge, majors manual,
vulnerability alerts bypass the cooldown).
