# 😌

## Summary

This is a permissioned file storage system that uses Cloudflare R2 as a dynamic backend.

## Admin notes

- Deployments to Cloudflare Wrangler triggered on push to `main`.
- New users: update `api/policy.json` and `scripts/kv.sh` then apply with `scripts/r2.sh`.
