# obsidian-redirect

Tiny static page that redirects `https://mgguinne.github.io/obsidian-redirect/?vault=...&file=...`
to `obsidian://open?vault=...&file=...`.

Used to make Obsidian deep-links clickable from contexts that do not auto-link custom URL schemes
(e.g. Telegram messages).

Vault defaults to `mikez_claude_code` if `?vault=` is omitted.
