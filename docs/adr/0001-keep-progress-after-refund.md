# Keep a learner's progress after their refund is approved

When an Admin approves a Refund Request, the learner loses access to the course, but we keep everything they did on it — lesson progress, video watch history, quiz attempts — for good. That history is the evidence behind refund decisions: if the learner buys the course again, the watch-time and completion limits count all of their progress on the course, not just what happened since the latest purchase, so nobody can loop buy → watch → refund for a free course. It also means their progress comes back if they buy again.

## Considered Options

- **Delete progress on approval** — rejected: it erases the evidence a later refund decision needs and resets the eligibility limits, making refund loops possible.
- **Keep progress for N days, then delete** — rejected: the same loophole reopens after N days, and it adds a cleanup job for no business gain.

## Consequences

- A learner asking for their data to be erased is a separate concern (data-deletion requests), not part of refunds.
