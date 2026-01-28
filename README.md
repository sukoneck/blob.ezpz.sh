# 😌

## Summary

This Worker API adds custom permissioning on top of Cloudflare R2 as a dynamic blob storage backend.

## Admin notes

- Deployments to Cloudflare Workers are triggered on push to `main`.
- New users: update `src/policy.json` and `scripts/kv.sh` then apply with `scripts/r2.sh`.
