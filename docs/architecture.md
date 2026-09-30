# Architecture

The platform combines staged TypeScript pipelines with a Next.js operations
interface. Source exports are mirrored, normalized and matched before website
and mailbox enrichment. Gmail refresh tokens remain in the operating-system
keychain. Derived signals, evidence, exclusions and suppressions are stored in a
relational database. Export routes independently re-check safety gates before
returning campaign-ready data.

