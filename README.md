# kilianthemagnificent.github.io

Personal security and formal-verification research notes by **Andre Romero-Carey**.

Live site: [https://kilianthemagnificent.github.io](https://kilianthemagnificent.github.io)

## Published Notes

- **[Adversarial Soundness Testing for AI-Authored Lean 4 Proofs](https://kilianthemagnificent.github.io/notes/lean4-verifier-adversarial-suite.html)** — Architecture of the 5-layer proof verifier in [`open-proofs`](https://github.com/KilianTheMagnificent/open-proofs), its 48-case adversarial bypass test suite, and machine-checked negation proofs uncovering upstream quantified-parameter misformalizations ([`google-deepmind/formal-conjectures#7590`](https://github.com/google-deepmind/formal-conjectures/issues/7590)).
- **[Defensive Screening Before LLM Triage: Untrusted Emails, Attachments, and CSVs](https://kilianthemagnificent.github.io/notes/untrusted-office-input-defenses.html)** — Engineering notes on [`inbox-guard`](https://github.com/KilianTheMagnificent/inbox-guard): magic-byte binary header checks, Unicode bidirectional override (`U+202E`) spoofing detection, accounting-safe OWASP CSV formula neutralization, invisible Unicode Tag (`U+E0000..U+E007F`) & CSS-hidden prompt-override screening, and deterministic session-scoped PII tokenization.
