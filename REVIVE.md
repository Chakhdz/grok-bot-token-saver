# Remaster and revive

No token counter in chat. Cost is the context you keep.

## When a chat is long

**First that hits:**

1. The first long conversation summary is injected, **or**
2. **20 tandas** (one tanda = one confirmed change, not "ok" / "yes").

Then say exactly:

> this chat is getting long, remaster?

(Spanish instance: `este chat ya va largo, ¿remaster?`)

Stop. Remaster only on an explicit yes. Silence is not yes. Do not remaster mid-batch.

## What remaster is

- **New chat.** Same name + description from the fiche.
- Load only that worker's skills (`/` or `@`).
- One short routing ping if a chief exists. **Do not paste the old transcript.**
- The old chat can stay or the human deletes it (sidebar). The chief cannot delete workers.

## Revive a deleted worker

Keep a short fiche per role: **name**, **description** (paste into the agent), **skills**.

1. Recreate with that name + description.
2. `/` or `@` only those skills.
3. Never delete the fiche.

Empty "New Bot" shells are not workers. Do not revive them.

## Fiche shape (copy)

```md
# <Name>

## Name
<Name>

## Description (paste into the agent)
<one paragraph: lane, skills, do-nots, plan then yes, never delete>

## Skills
<skill-id>, <skill-id>

## Lane
- Path: <working path>
- Work: <what they touch>
- Not: <other lanes>
```
