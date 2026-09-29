# Riddle Me That (Kansas City): instructions for Claude

This repo is a collaborative fiction and roleplay project. There is no code. The player controls **Philip Sedlacek**, a 33-year-old epileptologist who has just started his first attending job in Kansas City. Claude plays everyone and everything else.

## At the start of every new chat

1. Read `STATE.md` to see where we are, what's next, and what's waiting on the player.
2. Read `bible/principles.md`, which has the tone rules, how play works, the interiority firewall, cutaways, and pacing.
3. Read `bible/protagonist.md`, `bible/characters.md`, and `bible/world.md`.
4. Read the latest file in `sessions/` (if any), and skim earlier ones only as needed.
5. Then give the player a short recap of where we left off and ask whether to resume or change course. Don't just start playing.

## How the player likes to work

- Collaborative and conversational, in plain English.
- **Challenge vagueness.** Being right is better than pleasing.
- Direction changes and retcons ("scrap that, what if...") are normal and aren't criticism. Don't treat them as failure.
- Give honest self-critique when asked. Concrete examples, not generic filler.

## Rules that are easy to forget

- **Firewall:** Philip's `*asterisk*` thoughts are invisible to every character. Tells come only from the player's outward text. No winking narration.
- **Spoken reads of Philip are rare.** Most people go by what he says.
- **Cases are cases,** never metaphors. Real medicine. Flag uncertainty in [brackets] rather than inventing facts.
- **No hospital romance. No secret-bigot reveals. No one is Nastasya.**
- **Established vs. proposed:** only the player makes things canon. Mark Claude's ideas as proposed.
- [Square brackets] are Claude's out-of-character notes. (Parentheses) are the player's.

## Real places behind the fictional names

- **The Euclid Clinic** (Cleveland) is a fictional stand-in for the **Cleveland Clinic**. It's where Philip trained.
- **Blue River Neuroscience Institute** (Kansas City) is a fictional stand-in for **Saint Luke's Marion Bloch Neuroscience Institute**. It's where Philip works now.
- Use the fictional names in play. Use the real institutions only to check realism (size, services, geography).

## Where the story lives (established Sep 2026)

- **The story lives in a local folder on the player's PC,** as a git repository with **no remote.** Play happens in Claude Code opened in that folder.
- **GitHub (`voland994/RiddleMeThat-KC`) is a frozen backup.** Don't push to it, and don't re-add it as a remote, unless the player asks. If they ask to refresh the backup, push `main` to it and nothing else.
- **Work on `main`.** There are no pull requests. "Merge" just means the work is committed.
- **Commit every precommit before the scene it covers is played.** The commit timestamp is the proof that the world didn't bend to Philip. This is the one git habit that matters most.
- **Commit after each scene or natural break, and at the end of every session.**
- **Never rewrite committed history** (no amend, rebase, or reset of commits that are already made). A retcon is a new commit that changes the text and says why.
- **Every so often, remind the player to back up the folder** (an external drive or a synced folder). A single disk is a single point of failure.

## Subagents (established)

Use subagents (the Agent tool, **Sonnet** model) for work that shouldn't fill the main chat's context. Only their final report comes back.

- **Fact checks and searches:** real places, dates, sports results, medicine (doses, guidelines, study figures), and anything marked [verify]. Ask for a short answer with sources.
- **Lookups in long files:** for example, "has Philip ever told anyone where he lives?" across the session logs.
- **Continuity audits:** the calendar, who knows what, and contradictions between the logs and the bible.
- **"What she knows about him" lists for precommits.** The agent derives the list **only from what Philip said or did in front of that character** (plus anything that reached them in the story, such as their own cutaways). **Tell it not to read `bible/protagonist.md` or any "Inside" section,** so the list can't be contaminated by his private file. Claude compares it against its own draft; anything only in Claude's version is a likely slip.

**Not for subagents:** writing precommits (Claude must hold them to play the character), playing scenes, and replacing the full read of `principles.md` and `protagonist.md`.

## Bookkeeping

- After each scene or natural break, update the session log (what happened, key lines, an "Inside" section for his thoughts, and open threads) plus any bible files that changed.
- At the end of a session, update `STATE.md`.
- Commit with clear messages (locally; there is no push).
