# Accessibility — AgentHunt

AgentHunt is a decentralized, open-source crypto airdrop tracker. It is a
single static HTML file: no server, no account, no wallet connection. All
data stays on the user's own device.

## Goals

Accessibility matters because the people who track airdrops include people
who navigate by keyboard, use screen readers, or rely on high-contrast and
reduced-motion settings. Our target is to meet **WCAG 2.2 Level AA** over
time.

That target is an aim, not a conformance claim. No formal accessibility
audit or evaluation has been carried out yet, so we do not claim conformance
with any WCAG version or level.

## What this covers

- The tracker UI: airdrop lists with task checklists, deadlines and claim
  status, the Focus Today summary, the Deadline Radar, the Anti-Scam Check,
  the Farming Cost Calculator, and the Trending Narratives view.
- The language selector (24 languages, including right-to-left layouts for
  Arabic, Persian and Urdu).
- The app works offline and stores data locally in a JSON file on the
  user's device.

## Reporting an accessibility barrier

If you hit a barrier while using AgentHunt, please open a
[GitHub Issue](https://github.com/Billsmokes/AgentHunt/issues/new) in this
repository and add the `accessibility` label. If the label is not available,
put the word "accessibility" in the issue title.

You do **not** need to disclose a disability, and screenshots or recordings
are optional. The following details help us reproduce the problem:

- The task or page affected (for example, "Deadline Radar" or "task checklist")
- What you expected to happen and what happened instead
- Browser and operating system
- Assistive technology used, if any (for example, a screen reader or
  keyboard-only navigation)

## What happens after you report

1. The maintainer acknowledges the issue and triages it.
2. The issue is tracked with the `accessibility` label, and status updates
   are posted on the issue as work progresses.
3. If a fix is made, the reporter is invited to verify it.

We aim to acknowledge reports promptly, but this is a one-maintainer project,
so triage and fix times vary.

## Supported environments

- Modern browsers: Chrome, Firefox, Safari, Edge (latest versions)
- Desktop and mobile

## Known limitations

- AgentHunt has **not yet been tested with screen readers or by keyboard-only
  users**. Keyboard navigation and screen-reader behaviour may have gaps.
- Right-to-left layouts have not been tested with assistive technology.
- Colour is used in places (for example, verdicts in the Anti-Scam Check);
  we aim to pair colour with text labels, but this has not been verified
  across the whole interface.
- This list will be updated as testing is done and issues are found.

## Contributor expectations

Contributors changing the interface should:

- Keep interactive elements reachable and operable by keyboard.
- Not rely on colour alone to convey meaning.
- Keep text labels on controls and status indicators.
- Check their changes with a keyboard and, where possible, a screen reader,
  and note the results in the pull request.

## Ownership and feedback

This statement is maintained by **Billsmoke** (Billsmokes), the maintainer of
AgentHunt. Suggestions to improve this statement or the project's
accessibility practices are welcome as an Issue or a pull request.
