<p align="center">
  <h1 align="center">Control Protocols Outside Lab-Clean Environments</h1>
  <p align="center"><strong>Pilot control-style monitors and protocols under messier, more naturalistic task settings.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Control Protocols Outside Lab-Clean Environments**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Pilot control-style monitors and protocols under messier, more naturalistic task settings.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
