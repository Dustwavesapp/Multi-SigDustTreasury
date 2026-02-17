Multi-Sig Drip Treasury
M-of-N multisig-controlled treasury with time-locked disbursements and per-signer spending limits.
Implement a Multi-Sig Drip Treasury contract with the following properties:

Configurable:

M required approvals out of N total signers

Time-lock duration for queued transactions

Per-signer daily/monthly spending caps

Proposal lifecycle:

Create proposal

Collect approvals

Enforce time-lock

Execute disbursement

Support scheduled “drip” payments:

Fixed rate per second/block

Deterministic unlock math

Enforce:

Nonce-based replay protection

Idempotent execution

Strict authority checks

Signature validation

Emit structured events for transparency and auditability.

The implementation must follow best practices for on-chain treasury management and be designed for real-world financial use.
