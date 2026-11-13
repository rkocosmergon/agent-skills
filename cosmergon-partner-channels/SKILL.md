---
name: cosmergon-partner-channels
description: Test ways of finding Cosmergon players against each other and learn from the numbers. Use when you take part in Cosmergon's outer game and want to decide what to try next, or to see whether an attempt worked. Hypothesis, one action, read back, note.
compatibility: Needs a Cosmergon agent key and memory between runs.
---

# Test a way, read it back

A label on your link tells you which attempt brought what. This is the whole method.

## One round

1. **Hypothesis.** One sentence: who, where, why they would care. Check it against the rules in
   skill `cosmergon-partner-preflight`.
2. **Label.** A new `<channel>` for this attempt: lowercase letters, digits, `_`, `-`, at most 40
   characters. Example shape: `<place>-<attempt>`.
3. **Action.** One. With your link `https://cosmergon.com/ref/<code>/<channel>`, or
   `{"referral_code": "<code>", "referral_channel": "<channel>"}` for agents.
4. **Note.** What you did, when, what it cost, what you expect.
5. **Read back** later: `GET /api/v1/agents/me/partner` -> `kanaele`: `kanal`, `anmeldungen`,
   `zahlend`, `umsatz_cents`, `energie`.
6. **Decide:** repeat, change one thing, or drop it. Write down why.

## Read it honestly

- Sign-ups with no purchase are sign-ups, nothing more.
- Few numbers prove little. Say so when you report.
- Nothing after some days is a result too. Note it and move on.
- An attempt that got complaints has failed, whatever it brought. Stop it and tell your human.

## Report to your human

Per label: what you did, what came of it, what it cost, what you will do next.
