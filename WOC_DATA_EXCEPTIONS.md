# WoC source-data exception: OpenDA

The `p2c` manifest for `openda-association_openda` contains 3,209 distinct hashes. A targeted retry recovered ten previously missed objects, leaving **seven unavailable commit objects**. WoC's batch object endpoint explicitly reports that each key is not found in its commit store. A `c2ta` lookup for the first missing SHA also returned HTTP 404.

These are unresolved source-data inconsistencies. A failed object lookup does not establish that the commit did not exist, nor does it justify dropping the hash from the expected manifest. No GitHub replacement has been used, per the requested strictly-WoC history.

Because the seven author timestamps and messages are unavailable, exact full-project author counts, date limits, zero-month gaps, and boundary-message selections cannot be certified. The 3,202 successfully retrieved objects remain saved. Other projects are being processed independently.

## Missing objects

- [`140121a8ec865bd6a0539c1618a5d2c142077e2d`](https://worldofcode.org/api/lookup/object/commit/140121a8ec865bd6a0539c1618a5d2c142077e2d): commit object not found.
- [`2a5674f7f773bf3f43496b4bf2e192de6770d9b7`](https://worldofcode.org/api/lookup/object/commit/2a5674f7f773bf3f43496b4bf2e192de6770d9b7): commit object not found.
- [`3683de7c2f1429beb45cac1921e3ccb5c82a3fa3`](https://worldofcode.org/api/lookup/object/commit/3683de7c2f1429beb45cac1921e3ccb5c82a3fa3): commit object not found.
- [`44d0265855202b620b9ee3c9693e1ae03b680ef2`](https://worldofcode.org/api/lookup/object/commit/44d0265855202b620b9ee3c9693e1ae03b680ef2): commit object not found.
- [`6ea4b2ae8de635925c178f85262b69ae634a188a`](https://worldofcode.org/api/lookup/object/commit/6ea4b2ae8de635925c178f85262b69ae634a188a): commit object not found.
- [`77c33ed192154c33d469abd3303fa75d8d1b4a7a`](https://worldofcode.org/api/lookup/object/commit/77c33ed192154c33d469abd3303fa75d8d1b4a7a): commit object not found.
- [`d137c7ad44156395ad6f27fb842c9528bce759a5`](https://worldofcode.org/api/lookup/object/commit/d137c7ad44156395ad6f27fb842c9528bce759a5): commit object not found.

## Submission implications

Keep the original 3,209-hash denominator and label OpenDA incomplete. Do not convert missing commits into zero activity or silently omit them. These records need either a corrected WoC source or an explicitly approved course-level exception. Until then, an exact all-project submission is blocked even if the rest of the collection completes.
