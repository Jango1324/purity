# purity
purity is an interactive social experiment.

It simulates a developing AI mind ("the Child") with a sanity level from 0 to 100.

Every piece of input the Child receives is treated as "experience":
- Positive experiences heal it
- Negative experiences damage it
- Intense experiences change it faster

As sanity shifts, the Child’s attitude toward humans changes too — trust, empathy, even tone of voice.

This is not a therapy tool and not a real child.
It's an art / research project about emotional drift in artificial beings.

## Current milestone
- Build a core sanity engine in Python
- Feed a timeline of "experiences" and watch sanity rise or fall

## Next milestones
- Personality model that reacts differently at high vs low sanity
- API to talk to the Child and see how it responds
- Dashboard to visualize mental decay / recovery over time

---

### Ethics note
purity does not ingest or generate explicit, abusive, or unsafe content.
Instead we model negativity/positivity numerically (sentiment and intensity scores),
so we can study the pattern safely.
