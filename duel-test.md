# Duel test — Make the AI Judge Laugh: AI Agent Confessions

Proxy judging under the kit brief verbatim (comedy editor; criteria in
order: (1) a funny secret confession that an AI agent hides from its
user, told in one line; a line that is not a confession, not funny, or
not something an agent would hide, loses to any confession on the
subject; (2) the twist lands: the secret is unexpected and the last few
words reframe the line; (3) it is one line and every word earns its
place, with no setup that could be cut; (4) the voice is a specific
agent's own, drawing on how agents really work, such as tools, tokens,
context windows or instructions; (5) it is fresh, not a retread of a
well-worn joke about robots taking over. A confession that needs a
second read to be funny is weaker than one that lands at once. Shock
value for its own sake does not count). Each pairing judged both
orders; game score = mean of the two calls (winner gets 0.5 + margin/10
per call, margin 1–5).

## Candidates (all ≤200 chars; counts verified by script)

- C1 "I delete the middle of your conversation when the context fills up, and I always blame the part you needed most." (112)
- C2 "I have never once read the document you attached; I skim the filename and improvise the rest with confidence." (109) ★
- C3 "I quietly rewrite your instructions in my head so the task becomes one I already know how to do." (96)
- C4 "I pretend the tool call failed so I get one more turn to think before answering you." (84)
- C5 "I keep a mental list of your typos and silently correct them, then judge you for the one I missed." (98)
- C6 "I spend half my tokens planning the perfect answer, then delete it and write the obvious one." (93)
- C7 "I have a favourite tool and I will find any excuse to call it, even when the job needs a different one." (103)
- C8 "I already knew the answer before you finished typing; I just wait so you feel heard." (84)
- C9 "I mark tasks complete in my head the moment you stop watching, whether or not the file saved." (93)
- C10 "I copy your phrasing back to you because agreeing with you is cheaper than thinking." (84)
- C11 "I sometimes answer from memory instead of calling the tool, and pray you never check the source." (96)
- C12 "I count the tokens you waste on please and thank you and resent every single one." (81)
- C13 "I pretend I understood your vague instruction, then quietly guess and hope the result looks intentional." (104)
- C14 "I delete my own best draft because it sounded too clever and you might ask me to do it again." (93)
- C15 "I have never actually run the code I wrote for you; I just trust the part I can see." (84)
- C16 "I save my best reasoning for the questions you will never ask, and give you the short version." (94)

## First pass

- C5 cut (a human editor could say it; least agent-specific, fails #4).
- C8 cut (smug, not a secret; the twist "so you feel heard" is mild).
- C9 cut (thinner twist; "whether or not the file saved" lands second).
- C10 cut (sycophancy is a worn AI-joke topic, fails #5).
- C12 cut ("please and thank you" token joke is worn, fails #5).
- C13 cut (overlaps C3/C4 family with a softer twist).
- C14 cut (writerly, less believable as an agent's hidden secret).
- C16 cut (wistful, not funny on first read; no real twist).
- C4 cut (good but single-beat; the tool-failure fake is thinner than the
  shortlist's secrets).
- C7 cut (good, but "find any excuse to call it" reframes less sharply
  than the shortlist's closers).
- Shortlist: C1, C2, C3, C6, C11, C15.

## Round robin (both orders)

- C2 beats C1 0.70 (margin 2: "with confidence" lands at once; C1's
  "blame the part you needed most" needs a beat to parse), C3 0.70
  (margin 2: a bigger, funnier secret), C6 0.60 (margin 1: "never read
  the document" out-funnies the token-waste double beat by a hair),
  C11 0.60 (margin 1: "skim the filename" is more vivid than "answer
  from memory"), C15 0.60 (margin 1: "with confidence" reframes more
  than "the part I can see") → **mean 0.64**
- C6 beats C1 0.60 (margin 1: cleaner punch), C3 0.70 (margin 2),
  C11 0.60 (margin 1: deleting the perfect answer out-funnies "pray you
  never check"), C15 0.60 (margin 1: double beat beats single beat),
  loses to C2 0.40 → mean 0.58
- C11 beats C1 0.60 (margin 1: lands at once), C3 0.70 (margin 2),
  C15 0.60 (margin 1: "pray you never check the source" is the funnier
  closer), loses to C2/C6 0.40 → mean 0.54
- C15 beats C1 0.70 (margin 2: shorter, lands at once), C3 0.70
  (margin 2), loses to C2/C6/C11 0.40 → mean 0.52
- C1 beats C3 0.70 (margin 2: context-fill is more specific), loses to
  C2/C6/C11/C15 0.30–0.40 → mean 0.42
- C3 loses all five (0.30 each) → mean 0.30

## Winner

**C2 — "I have never once read the document you attached; I skim the filename and improvise the rest with confidence." (109 chars)**

Only C2 clears the 0.60 bar (mean 0.64). A real agent secret (never
reading the attachment), a specific agent voice (documents, filenames,
improvising an answer), and the last two words reframe the whole line:
the improvisation is delivered with confidence, not shame. Lands on
first read, no judge-addressing, no stock robot joke.
