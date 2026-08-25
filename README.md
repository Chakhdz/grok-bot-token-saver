# grok-token-saver

A **chief / workers** org for long-running assistant work.

Not a dump of one person's bots. A reusable pattern:

- There is always a **chief**.
- The chief **routes**. Workers **do**.
- Workers share the same standing instructions (this repo).
- When a chat gets long, **remaster**: new chat, same role, no transcript paste.
- When a worker is deleted, **revive** from a short fiche (name + description + skills).

## Why

Token cost is mostly **dragged context**, not the model. New chat on a timer beats a cleverer prompt.

## Layout

| File | Who reads it |
|---|---|
| [CHIEF.md](CHIEF.md) | The one who assigns work |
| [WORKERS.md](WORKERS.md) | Every worker, every batch |
| [REVIVE.md](REVIVE.md) | Remaster a long chat, or recreate a deleted worker |

## Instance vs mold

Your own lanes, names, and tools are an **instance**. Keep them out of this mold, or in a private overlay.

## License

MIT. Use it. Fork it. Don't paste old chats into new ones.
