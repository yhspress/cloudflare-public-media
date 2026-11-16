# Cloudflare public media preservation

Original, unchanged public images preserved from img.autumnkyoto.com and img.autumnjapan.com. Manifest records original keys, public URLs, sizes and SHA-256 hashes.

No passwords, OAuth tokens, private bucket contents or application databases are included. Cloudflare originals remain until GitHub byte verification and public-route migration are verified. Future uploads and publication workflows must remain operational.

## Migration verification — 2026-11-16

266 images (272,559,595 bytes) were independently downloaded from immutable GitHub URLs and matched the manifest SHA-256 hashes. All 266 original public URLs now return a 302 to those images; final HTTP responses are 200 and byte hashes match. Exact-match redirects are recorded in `migration/redirects-20261116.csv`; unrelated and future upload paths remain on their existing routes. R2 source deletion is pending action-time confirmation.
