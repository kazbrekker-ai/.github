# Contributing

Every kazbrekker-ai repository follows the portfolio standard in its `docs/PORTFOLIO.md`. Section
10, "How work flows", is the working agreement: the Three Ways from *The Phoenix Project* applied
to a one-owner portfolio.

## Before you start

1. **Open or pick an issue** with the right form. Planned work gets one `work:` label and one
   `phase:` label; unplanned work gets `work:unplanned`.
2. **Respect the work-in-progress limit.** Label what you are working on `flow:in-progress`. If
   the portfolio already has its limit in progress, finish something first. `expedite` (a
   Critical or High finding inside its SECURITY.md due date, or an outage) is the only exception.
3. **Pick from the top of the queue:** `expedite`, then a red check on `main`, then work already
   in progress, then phase 1, the open phase 2 project's next step, then phase 3. Phase 4
   ("thankless") is not started: it is closed and recorded as an accepted risk.

## Making the change

- One change per PR, small enough to review in one sitting (First Way).
- The PR names its work type, links its issue and, for security-relevant changes, maps to
  NIST SP 800-53, CIS v8.1 or the AI crosswalk (portfolio standard section 9).
- It lands with the automated check that proves it keeps working: a test, a CI step, a posture
  check or a Wazuh rule (Second Way).
- Docs move with the code in the same PR.

## Closing

- Close the issue with a link to the PR.
- Unplanned work closes with its cause and its prevention: a new check, or a new issue that
  removes the cause (Third Way).

## Security

Do not report a vulnerability in a public issue. Follow the repository's SECURITY.md.
