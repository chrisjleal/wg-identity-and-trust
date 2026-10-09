# Outstanding Agenda Topics

This file tracks proposed Identity & Trust Working Group presentations and unresolved discussion topics. It complements the [running meeting notes](https://docs.google.com/document/d/1JfVIQBbxpMT28poaEyAwnINXRC9ZuLPg5q08G6CjPCM/edit?usp=sharing), which remain the record of scheduled agendas, discussion, and decisions.

## How to use this list

- Add a topic before a meeting and identify an owner who can drive the next step.
- State the desired outcome: information sharing, design feedback, a documented decision, or a follow-up artifact.
- Update the status when the item is scheduled, discussed, converted to an issue or pull request, or closed.
- Link the resulting notes or artifact so future participants can find the outcome.

## Presentation queue

- **Proofable authority-at-dispatch and portable evidence implementation review** - Owner: Chris Leal (NEUS Network, Inc. / Proofable). Desired outcome: review the #13 implementation evidence as an input to the working group's authority and action-evidence boundary, and determine placement in the Use Cases, Reference Architecture, or Attestation and Evidence work. Content: eight bounded production authority cases on a pinned deployed revision (binding veto, revoked or stale authority with an allowed control, remote-authority-unavailable as not applicable to a local-authority path, and revocation after dispatch), a machine-readable trace and manifest, 11 disclosed CAIP-380 portable envelopes that verify from the published bytes alone (qHash recomputed, EIP-191 signer recovered), and an independent reader PR against the ProbityAI agent-evidence-observer. Evidence: the immutable Proofable packet at proofable/docs 9851059, the open reader PR probityai/agent-evidence-observer#88, and AAIF Identity and Trust issue #13. Scope: implementation input only; author-operated evidence with no independent witness, and no AAIF conformance or independent-execution claim. Status: proposed.
