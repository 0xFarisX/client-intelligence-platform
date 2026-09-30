# Design decisions

## Asymmetric error costs

Matching favors exclusion because contacting an actively owned account is more
damaging than losing one candidate from a large pool.

## Deterministic extraction

High-risk communication signals are derived through tested rules, not a model.

## Credential isolation

Mailbox tokens remain outside the application database.

## Dual export gates

SQL selection and the export route independently enforce exclusions.

