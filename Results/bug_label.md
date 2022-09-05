# Bug Labels

## Machine-unauditable Bugs

+ S1: Price Oracel Manipulation
+ S2: ID Uniqueness Violations
+ S3: Inconsistent State Updates
+ S4: Atomicity Violations
+ S5: Privilege Escalation
+ S6: Erroneous Accounting
+ C : Contract Impl Specific Bugs

## Machine-auditable Bugs

+ L1: Reentrancy
+ L2: Rounding / Precision 
+ L3: Uninitialized Variables / Re-initilization
+ L4: GAS
+ L5: Inconstancy Storage Layout / Data Structure Misuse (especially for proxy)
+ L6: Arbitrary external Function Call
+ L7: Overflow / Underflow
+ L8: Low-level Call / Revert
+ L9: Arbitrary external Function Call
+ LA: Cryptographic Issue 

#### Out-of-scope bugs

+ O1: Privileged Users, e.g., RugPull, First User
+ O2: Cross-chain Bridge
+ O3: Cannot cause direct fund loss, e.g., setting a trap for users
+ O4: Off-chain Hack
+ O5: Typo or silly bug, which makes the contract non-deployable or non-functional (very basic unit test can detect such issues)
+ O6: Not-A-Bug according to the project, it is usually due to a disagreement between the auditors and the project.
