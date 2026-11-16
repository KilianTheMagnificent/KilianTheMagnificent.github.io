# kilianthemagnificent.github.io

Security and formal-verification notes by **Andre Romero-Carey**.

Live site: [https://kilianthemagnificent.github.io](https://kilianthemagnificent.github.io)

## Notes

- **[Checking Untrusted AI-Authored Lean 4 Proofs](https://kilianthemagnificent.github.io/notes/lean4-verifier-adversarial-suite.html)** — 5-layer proof checker in [`open-proofs`](https://github.com/KilianTheMagnificent/open-proofs) (proofs and tooling built with Claude Code and Codex), its 48 self-test checks (41 negative tamper/bypass checks plus 7 positive controls), scope limits, and negation proofs for [`google-deepmind/formal-conjectures#7590`](https://github.com/google-deepmind/formal-conjectures/issues/7590).
- **[Screening Untrusted Office Inputs Before LLM Triage](https://kilianthemagnificent.github.io/notes/untrusted-office-input-defenses.html)** — Design and scope limits of [`inbox-guard`](https://github.com/KilianTheMagnificent/inbox-guard): magic-byte binary/archive header checks, Unicode `U+202E` and Windows/SMB filename spoofing detection, accounting-safe OWASP CSV formula neutralization, linear HTML5 comment and CSS declaration scanning, Plane-14 Unicode Tag (`U+E0000..U+E007F`) stripping, and randomized session-scoped PII tokenization.
